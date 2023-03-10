# README

https://www.theodinproject.com/lessons/ruby-on-rails-rails-final-project

## Project: Building Facebook
1. Use PostgreSQL for your database from the beginning (not SQLite3), 
that way your deployment will go much more smoothly.  -done

2. Users must sign in to see anything except the sign in page.  -done

3. User sign-in should use the Devise gem. Devise gives you all sorts of helpful methods so 
you no longer have to write your own user passwords, sessions, and #current_user methods. 
See the Railscast (which uses Rails 3) for a step-by-step introduction. The docs will be fully current.  -done

4. Users can send Friend Requests to other Users.

5. A User must accept the Friend Request to become friends.

6. The Friend Request shows up in the notifications section of a User’s navbar.
7. Users can create Posts (text only to start).
8. Users can Like Posts.
9. Users can Comment on Posts.
10. Posts should always display with the post content, author, comments and likes.
11. Treat the Posts Index page like the real Facebook’s “Timeline” feature – 
show all the recent posts from the current user and users she is friends with.
12. Users can create a Profile with their personal information and a photo. 
You can use Gravatar for this photo.
13. The User Show page contains their Profile information, photo, and Posts.
14. The Users Index page lists all users and buttons for sending Friend 
Requests to those who are not already friends or who don’t already have a 
pending request.
15. Sign in should use OmniAuth to allow a user to sign in with their real 
Facebook account. See the RailsCast on FB authentication with Devise for a 
step-by-step look at how it works.
16. Set up a mailer to send a welcome email when a new user signs up. Use the 
letter_opener gem (see docs here) to test it in development mode.
17. Deploy your App to a hosting provider.
18. Set up an email provider and start sending real emails.

## Extra Credit
1. Make posts also allow images (either just via a URL or, more complicated, 
by uploading one).
2. Use the Active Storage to allow users to upload a photo to their profile.
3. Make your post able to be either a text OR a photo by using a polymorphic 
association (so users can still like or comment on it while being none-the-wiser).
4. Style it up nicely! We’ll dive into HTML/CSS in the next course.
