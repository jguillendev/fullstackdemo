# fullstack demo :wave:
my fullstack project to participate in  xaldigital

# pre requirements :technologist:

- you need to have docker installed

# how to run :brain:

to run local with docker compose
- open cmd console at root folder :footprints:
- docker-compose up --build :footprints:
- wait for it to finish creating all the images
- be patient, it takes a while :sweat_smile: :snail: :snail:

the images that will be created are the following:
- xald-app : front-end react
- api-answers: back-end node-express-mongo
- my-prometheus: prometheus board for metrics
- grafana: grafana dashboard to display metrics

# All ready? - go to enjoy :vulcan_salute:
## enter the front-end :joystick:
open the browser and go to http://localhost:82/ :footprints:

## enter the back-end :star2:
open the browser and go to http://localhost:83/ :footprints:

## see the api swagger documentation :yarn:
open the browser and go to http://localhost:83/api/docs/swagger :footprints:

# test? yes sure! :hammer_and_wrench:
api tests :mage:
- enter the folder api-answers  (cd api-answers) :footprints:
- run: npm run test :crossed_fingers:

front tests :mage:
- enter the folder xald-app  (cd xald-app) :footprints:
- run: npm test :crossed_fingers:

#
## thanks for visiting this repository :clap: :clap:
do things with love and you will always get great satisfaction :heart: :heart:
:ok_hand: :love_you_gesture: :sunglasses:

