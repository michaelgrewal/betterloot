Michael Grewal
100 739 181


    OpenStack IP: 134.117.133.196
    Instance: MichaelGrewal
    username: student
    password: michael1989

    Go to 'FINAL' folder
    run server.js to start the application.
    You may register and login with your own info,
      OR you can login as 'auto1' through 'auto20' pw:tester
        If you choose to login as an auto user, you will notice the automation of orders
        in realtime when in the "LIVE" state (top left corner).
        Sit back and enjoy the 'auto' users.

REST API:
    Many routes support REST API well, especially the GET routes:
      /users/:username
      /stocks                 ?symbol= &minprice= &maxprice=
      /stocks/symbol          ?startday= &endday=
      /stocks/symbol/history  ?startday= &endday=
      /masterStocksList
      /day
      /:uid/orders
      /orders
      /:uid/subscriptions
      /:uid/notifications
      /logout

    The POST routes also work, but you must adhere to exactly what is required as JSON.
      For example you can POST to /login but you need to send:
        {username:yourusername, password:yourpassword} for it to work.
        Same with any other POST, PUT, and DELETE.
