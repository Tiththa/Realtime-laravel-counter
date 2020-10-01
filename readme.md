# Realtime Counter using Laravel and Pusher

This repository demonstrates the process of showing a realtime counter using Laravel and Pusher. Please follow below steps to have a running version of the app in this repo

1. Clone repo
2. Configure your environment variables for Pusher and Laravel by copying the `.env.example` to `.env`
3. Configure your Pusher key in the `resources/assets/js/bootstrap.js` file
4. Install composer dependencies
5. Run npm install
6. Run the seeder. You will get dummy users. The password for those users will be `secret`

## Configure Pusher 

Configure pusher in your env

```
PUSHER_APP_ID=YOURID
PUSHER_APP_KEY=YOURKEY
PUSHER_APP_SECRET=YOURSECRET
PUSHER_APP_CLUSTER=YOURCLUSTER
```