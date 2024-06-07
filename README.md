# Borcelle-admin:

cd to file
npm start
npm run dev

.env:
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY
CLERK_SECRET_KEY
ECOMMERCE_STORE_URL
ADMIN_DASHBOARD_URL
MONGODB_URL
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME
NEXT_PUBLIC_STRIPE_SECRET_KEY
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY
STRIPE_WEBHOOK_SECRET
NEXT_PUBLIC_CLERLK_SIGN_IN_URLsign-in
NEXT_PUBLIC_CLERLK_SIGN_UP_URLsign-up
NEXT_PUBLIC_CLERLK_AFTER_SIGN_IN_URL
NEXT_PUBLIC_CLERLK_AFTER_SIGN_UP_URL

To connect to stripe locally:
open cmd: go to stripe.exe copy address
cd address
stripe login (if for first time)
stripe listen --forward-to localhost:3000api/webhooks
#   a d m i n _ e c o m  
 