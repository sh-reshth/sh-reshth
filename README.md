## Hi there 👋

I’m Shreshth Sharma, an Integrated MCA student at Amity University, Noida (2021–2026).
I have strong interests in networking, cybersecurity, data analytics and full-stack development.


📧Email: shershth20036171@gmail.com


📂 Project Structure    
  📦 social-media-dashboard
 ┣ 📂 models          # MongoDB schemas for User, Post, Message
 ┣ 📂 routes          # Express routes (user, analytics, posts)
 ┣ 📂 controllers     # Business logic
 ┣ 📜 app.js          # Main entry point
 ┣ 📜 .env            # Environment variables
 ┣ 📜 package.json    # Dependencies
 ┣ 📜 README.md       # Documentation


⚡ APIs Implemented
Endpoint	Method	Description
/analytics/user/:id/followstats	GET	Fetch follower & following counts
/analytics/user/:id/view	POST	Log a profile view
/analytics/user/:id/viewcount	GET	Get profile views
/analytics/user/:id/dms	GET	Fetch DMs sent & received
/posts/:id/engagement	GET	Fetch likes & comments count
