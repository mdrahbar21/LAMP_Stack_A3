<h1> Virtual Hosting and Security </h1>

<h3>Tasks</h3>
- Create 2 sample HTML websites (choose any template that you want) <br>
- Create 4 users: user1/2/3/4
  <hr>
  
<strong> Website 1 configuration and accesses </strong>

- Website 1's home page should be named as website1.html
- Website 1 should be available from 2 IPs
  - From 1<sup>st</sup> IP, it should be directly accessible
  - But when you hit the 2<sup>nd</sup> IP, it should be redirected to Website 2 (Do this task after we have covered Redirect module)
  - Website 1 should be accessible from client c10 and should not be accessible from c20
  - Website 1 should listen on port 15
  - Website 1 should be accessible to user1 and user3
  - When you open them through user2 and user4 they should show you a custom made error Forbidden page which should contain the following message: <br>"You should be an Authenticated user. Contact web gawd!" <br> with title as "Web Gawd can stop you anywhere"
  <hr>

<strong> Website 2's configuration and accesses </strong>

- Website 2's home page should be named as index.html
- Website 2 should be available from 2 IPs
  - From 1<sup>st</sup> IP, it should be directly accessible
  - But when you hit the 2<sup>nd</sup> IP, it should be redirected to Website 1 (Do this task after we have covered Redirect module)
  - Website 2 should be accessible from client c20 and should not be accessible from c10
  - Website 2 should listen on port 80
  - Website 2 should be accessible to user1 and user2
  - When you open them through user3 and user4 they should show you a custom made error Forbidden page which should contain the following message: <br>"You should be an Authenticated user. Contact web gawd!" <br> with title as "Web Gawd can stop you anywhere"
  <hr>
