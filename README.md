# Insure fund
## intro:
  invest fund and buy insurance webapp
![image](https://user-images.githubusercontent.com/116508084/213916141-5799d1d9-9407-4495-8cdc-d50f11439b70.png)
  the Center for those who want to invest in alternatives and those who want to buy insurance.
  it take money from investors for insurance funds and is paid back by the premium of buyer.
  
## Installation: 
frontend: https://github.com/maharnnop/front_tda4 
  - fork & clone
  - cd react-tda4 
  - npm i 
  - npm start
backend:https://github.com/maharnnop/insurance-fund
  - fork & clone
  - pip install, 
  - source .env/Scripts/activate
  - py manage.py runserver
database:https://bit.io/maharnnop/tda4-db 

## Deployment:
database:https://bit.io/maharnnop/tda4-db 

## Technology used:
frontend:   Reactjs, react-apexcharts
backend:    REST-Django
database:   postgresql

##  ER Diagram
![image](https://user-images.githubusercontent.com/116508084/213916948-6f4bd917-2063-4e0c-80a6-754a1cf4ad55.png)

## Main features:
- login/signup/logout
- package page shows the list of insurance that is available buy but the user needs to log in to see its detail.
- invest page shows the list of insurance that is available invest.
- profile page shows user data form and a list of insurance is bought.
- dashboard page shows a summary invest data chart and a list of insurance is invested.

## User Stories
- As a user, I should see the list of card insurance but I cant buy until login. if I cilck a card it will navigate to the login page.
- As a user after login in, I should be able to see the detail when I click the card. if I cilck buy-button it will navigate to the package page.
- As a user, I should see the list of card funds on invest page and be able to see detail after clicking the card.
- As a user, I click invest in investdetail page. If the funding is full Insurance will be sold on the pakage page.
- As a user, I can see sumary of investing port on dashboard page.

## What left?
1. UI&UX
2. i try to use Cordova to convert Reactjs to a mobile app but still struggle
