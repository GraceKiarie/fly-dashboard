what you built and what you didn't build
  Done:
    1. Query app status using fetch_app_status  -client.ex
    2. display app status info on -app_live/show.html.heex
    3. Add a timer on mount that invokes an internal event: handle_info(:refresh,socket)  -app_live/show.ex
    4. style the dashboard

  Not done:
    - a page to display more details on instances
    - sidebar for easy navigation


how you'd determine if this feature is successful
1. User is able to see real time and conclusive info about an application.
2. a clean dashboard

what you'd improve or fix if you had more time
1. Group applications according to organizations
2. Allow actions like scale, restart an instance, delete an instance  ...etc on the dashboard.
3. Logs for the application
4. Allow users to map appurl(https://1.4.7.8) to domain names (https://fly.io)
5 
