# 23G
This is the final and completed Shop of Maximilian Schwarzmiller's 'Node Js' course,
when finished , the redirection back to the site when the Test Stripe Payment has been
made is unsuccessful , there is something wrong I can't figure out what it is in 
the following code found in shop.js in Controllers:

success_url: req.protocol + '://' + req.get('http://localhost:3005') + '/checkout/success', // => http://localhost:3000
        cancel_url: req.protocol + '://' + req.get('http://localhost:3005') + '/checkout/cancel'
      });

MONGO URI is in app.js ,
Sendgrid API key is in auth Controllers ,
Stripe SK key is in shop Controllers ,
Stripe PK key is in checkout.ejs in the 'shop' subfolder of views.

Obviosuly mine will not work so the fields in that code is empty .
