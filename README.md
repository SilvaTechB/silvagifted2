## open source code 
> Warning: non-english
![how to create a new command, annotated using handwriting](res/readme/wleowleo.png)
> English below  
>
>Download and send messages
![Download and send messages](res/readme/message.gif)
>Create new commands
![Create new commands](res/readme/command.gif)
![Create new commands](res/readme/metadata.gif)
> Aaaaand many more
![Aaaaand many more](res/readme/context.gif)

## How to Contribute
Please fork the repository and make changes as you'd like.
Steps to contribute:
1. Fork this repository
2. Create your feature branch (git checkout -b feature/newFeature)
3. Commit your changes (git commit -am 'Add some feature ...')
4. Push to the branch (git push origin feature/newFeature)
5. Create a new Pull Request


## Requirements (Prerequisites)

-   Node.JS
-   Imagemagick
-   FFMpeg
-   Libwebp (for running webpmux and dwebp)

## Cloning
```sh
git clone https://github.com/riozee/miki-whatsapp-bot
cd miki-whatsapp-bot
```

## `.env` Configurations
Before running, make sure to create `.env` file in the bot folder and paste this configurations.

```sh
# the bot number itself (NECESSARY)
BOT_NUMBER="1234567890"
# your number (NECESSARY)
OWNER_NUMBER="1234567890"
# the number people will contact to buy Premium
CUSTOMER_SERVICE_NUMBER="1234567890"
# the number to receive the feedback when a user sent a feedback using /feedback command
# (can be a group) (ends it with @g.us if it's a group)
FEEDBACK_NUMBER="1234567890"
# bot will send a backup copy of the database every minute. This is the number to send to
# (can be a group) (ends it with @g.us if it's a group)
DATABASE_BACKUP_NUMBER="1234567890"
# everytime there is an error in command, bot will send a report to this number
# (can be a group) (ends it with @g.us if it's a group)
ERROR_REPORT_NUMBER="1234567890"
# prefix of the bot
PREFIX="!@#$%^&*"
```

## Run

```sh
npm install
npm run build
npm start
```

## Features

| No  | Name                    | Permission    | Status |
| --- | ----------------------- | ------------- | ------ |
| 1   | about                   | all           | ✔      |
| 2   | addpremium              | all-owner     | ✔      |
| 3   | echo/say                | all           | ✔      |
| 4   | adminonly               | group-admin   | ✔      |
| 5   | premium                 | all           | ✔      |
| 6   | ban                     | all-owner     | ✔      |
| 7   | stats                   | all           | ✔      |
| 8   | getbackup               | all-owner     | ✔      |
| 9   | ev                      | all-owner     | ✔      |
| 10  | feedback                | all           | ✔      |
| 11  | help                    | all           | ✔      |
| 12  | language                | private-admin | ✔      |
| 13  | menu                    | all           | ✔      |
| 14  | premium                 | all-owner     | ✔      |
| 15  | sleep                   | group-admin   | ✔      |
| 16  | sticker/sticker/s       | all           | ✔      |
| 17  | unsticker/unsticker/uns | all           | ✔      |
| 18  | batchsticker            | all (premium) | ✔      |
| 19  | batchunsticker          | all (premium) | ✔      |
