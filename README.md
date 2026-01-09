### Task Description

1. **Fetch Events Data**
   - Retrieve events from the following endpoint: [https://playback-app-28d68.web.app/match.json](https://playback-app-28d68.web.app/match.json).
   - The response will be a list of event objects with the following structure:
     ```json
     {
       "id": "1",
       "title": "Liverpool v Porto",
       "subtitle": "UEFA Champions League",
       "date": "2024-05-27T01:25:08.098Z",
       "imageUrl": "https://firebasestorage.googleapis.com/v0/b/dazn-recruitment/o/310176837169_image-header_pDach_1554579780000.jpeg?alt=media&token=1777d26b-d051-4b5f-87a8-7633d3d6dd20",
       "videoUrl": "https://firebasestorage.googleapis.com/v0/b/dazn-recruitment/o/promo.mp4?alt=media"
     }
     ```
   
2. **Implement Events List View**
   - Create a list view to display the events fetched from the above API.
   - Each list item should display the event's title, subtitle, and (optinally) date.
   - (Optinally) Use the `imageUrl` to display a relevant image for each event.

3. **Handle List Item Tap for Playback**
   - Implement functionality to start video playback when an event in the list is tapped.
   - Use the `videoUrl` from the event object as the source for the video playback.
