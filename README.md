

Here’s how you might use these endpoints:

1. **Get All Autobots:**
   ```
   GET /api/autobots
   ```

2. **Get Posts for a Specific Autobot:**
   ```
   GET /api/autobots/{autobotId}/posts
   ```

3. **Get Comments for a Specific Post:**
   ```
   GET /api/posts/{postId}/comments
   ```


Visit `http://localhost:8000` to see the Vue component displaying the real-time count of Autobots.

This setup ensures that 500 Autobots are created every hour with associated posts and comments. The API endpoints provide developers access to Autobots, their posts, and post comments with rate limiting and pagination to control the data flow.