Download Link: https://assignmentchef.com/product/solved-cs50-project4-social-network-that-allows-users-to-make-posts
<br>
Using Python, JavaScript, HTML, and CSS, complete the implementation of a social network that allows users to make posts, follow other users, and “like” posts. You must fulfill the following requirements:

<ul>

 <li><strong>New Post</strong>: Users who are signed in should be able to write a new text-based post by filling in text into a text area and then clicking a button to submit the post.

  <ul>

   <li>The screenshot at the top of this specification shows the “New Post” box at the top of the “All Posts” page. You may choose to do this as well, or you may make the “New Post” feature a separate page.</li>

  </ul></li>

 <li><strong>All Posts</strong>: The “All Posts” link in the navigation bar should take the user to a page where they can see all posts from all users, with the most recent posts first.

  <ul>

   <li>Each post should include the username of the poster, the post content itself, the date and time at which the post was made, and the number of “likes” the post has (this will be 0 for all posts until you implement the ability to “like” a post later).</li>

  </ul></li>

 <li><strong>Profile Page</strong>: Clicking on a username should load that user’s profile page. This page should:

  <ul>

   <li>Display the number of followers the user has, as well as the number of people that the user follows.</li>

   <li>Display all of the posts for that user, in reverse chronological order.</li>

   <li>For any other user who is signed in, this page should also display a “Follow” or “Unfollow” button that will let the current user toggle whether or not they are following this user’s posts. Note that this only applies to any “other” user: a user should not be able to follow themselves.</li>

  </ul></li>

 <li><strong>Following</strong>: The “Following” link in the navigation bar should take the user to a page where they see all posts made by users that the current user follows.

  <ul>

   <li>This page should behave just as the “All Posts” page does, just with a more limited set of posts.</li>

   <li>This page should only be available to users who are signed in.</li>

  </ul></li>

 <li><strong>Pagination</strong>: On any page that displays posts, posts should only be displayed 10 on a page. If there are more than ten posts, a “Next” button should appear to take the user to the next page of posts (which should be older than the current page of posts). If not on the first page, a “Previous” button should appear to take the user to the previous page of posts as well.

  <ul>

   <li>See the <strong>Hints</strong>section for some suggestions on how to implement this.</li>

  </ul></li>

 <li><strong>Edit Post</strong>: Users should be able to click an “Edit” button or link on any of their own posts to edit that post.

  <ul>

   <li>When a user clicks “Edit” for one of their own posts, the content of their post should be replaced with a textareawhere the user can edit the content of their post.</li>

   <li>The user should then be able to “Save” the edited post. Using JavaScript, you should be able to achieve this without requiring a reload of the entire page.</li>

   <li>For security, ensure that your application is designed such that it is not possible for a user, via any route, to edit another user’s posts.</li>

  </ul></li>

 <li><strong>“Like” and “Unlike”</strong>: Users should be able to click a button or link on any post to toggle whether or not they “like” that post.

  <ul>

   <li>Using JavaScript, you should asynchronously let the server know to update the like count (as via a call to fetch) and then update the post’s like count displayed on the page, without requiring a reload of the entire page.</li>

  </ul></li>

</ul>