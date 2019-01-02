## happy path 1
* greet
 - utter_greet

## happy path 2
* thankyou
 - utter_thankyou

## Generated Story 1
* greet
    - utter_greet
* cancel_travel
    - utter_affirm_cancel
* affirm
    - action_cancel_travel
* thankyou
    - utter_thankyou

## Generated Story 2
* greet
    - utter_greet
* cancel_travel
    - utter_affirm_cancel
* affirm
    - action_cancel_travel
* thankyou
    - utter_thankyou

## Generated Story 3
* greet
    - utter_greet
* travel_status
    - action_check_status
* thankyou
    - utter_thankyou


## Generated Story 4
* greet
    - utter_greet
* cancel_travel
    - utter_affirm_cancel
* affirm
    - action_cancel_travel
* thankyou
    - utter_thankyou


## Generated Story 5
* greet
    - utter_greet
* cancel_travel
    - utter_affirm_cancel
* affirm
    - action_cancel_travel


## Generated Story 6
* greet
    - utter_greet
* travel_status
    - action_check_status
* thankyou
    - utter_thankyou


## Generated Story 7
* greet
    - utter_greet
* inform_travel{"city": "london", "bookDate": "20 sep", "meal": "vegetarian meal"}
    - slot{"bookDate": ["12 sep", "20 sep"]}
    - slot{"city": ["cairo", "london"]}
    - slot{"meal": ["vegetarian meal"]}
    - utter_affirm_request
* affirm
    - action_request_travel
* thankyou
    - utter_thankyou


## Generated Story 8
* inform_travel{"city": "budapest"}
    - slot{"city": ["cairo", "budapest"]}
    - utter_ask_time
* inform_travel{"bookDate": "25 nov"}
    - slot{"bookDate": ["20 nov", "25 nov"]}
    - slot{"meal": ["hot diabetic meal"]}
    - utter_affirm_request
* affirm
    - action_request_travel
* thankyou
    - utter_thankyou


## Generated Story 9
* greet
    - utter_greet
* inform_travel{"bookDate": "16 october"}
    - slot{"bookDate": ["12 october", "16 october"]}
    - utter_ask_city
* inform_travel{"city": "madrid"}
    - slot{"city": ["cairo", "madrid"]}
    - slot{"meal": ["seafood meal"]}
    - utter_affirm_request
* affirm
    - action_request_travel
* thankyou
    - utter_thankyou


## Generated Story 10
* greet
    - utter_greet
* inform_travel{"city": "madrid", "bookDate": "5 oct"}
    - slot{"bookDate": ["1 feb", "5 oct"]}
    - slot{"city": ["cairo", "madrid"]}
    - slot{"meal": ["seafood"]}
    - utter_affirm_request
* affirm
    - action_request_travel
* thankyou
    - utter_thankyou


## Generated Story 11
* greet
    - utter_greet
* inform_travel{"bookDate": "23 nov"}
    - slot{"bookDate": ["tomorrow", "23 nov"]}
    - utter_ask_city
* inform_travel{"city": "budapest"}
    - slot{"city": ["cairo", "budapest"]}
    - slot{"meal": ["reduced fat and salt meal"]}
    - utter_affirm_request
* affirm
    - action_request_travel
* affirm
    - utter_thankyou

## Generated Story 12
* greet
    - utter_greet
* inform_travel{"city": "budapest", "bookDate": "23 oct"}
    - slot{"bookDate": ["tomorrow", "23 oct"]}
    - slot{"city": ["cairo", "budapest"]}
    - slot{"meal": ["hot diabetic meal"]}
    - utter_affirm_request
* affirm
    - action_request_travel
* thankyou
    - utter_thankyou


## Generated Story 13
* greet
    - utter_greet
* inform_travel{"city": "budapest"}
    - slot{"city": ["cairo", "budapest"]}
    - utter_ask_time
* inform_travel{"bookDate": "25th october"}
    - slot{"bookDate": ["12th october", "25th october"]}
    - utter_ask_meal
* inform_travel{"meal": "vegetarian Meal"}
    - slot{"meal": ["vegetarian Meal"]}
    - utter_affirm_request
* affirm
    - action_request_travel
* thankyou
    - utter_thankyou




## Generated Story 14
* inform_travel
    - utter_ask_time
* inform_travel{"bookDate": "sunday"}
    - slot{"bookDate": ["sunday"]}
    - utter_ask_city
* inform_travel{"city": "budapest"}
    - slot{"city": ["madrid", "budapest"]}
    - utter_ask_meal
* inform_travel{"meal":"seafood meal"}
    - slot{"meal": ["seafood meal"]}
    - utter_affirm_request
* affirm
    - action_request_travel
* thankyou
    - utter_thankyou

## Generated Story 15
* greet
    - utter_greet
* inform_travel
    - utter_ask_city
* inform_travel{"city": "budapest"}
    - slot{"city": ["cairo", "budapest"]}
    - utter_ask_time
* inform_travel{"bookDate": "sunday"}
    - slot{"bookDate": ["tomorrow", "sunday"]}
    - utter_ask_meal
* inform_travel{"meal": "reduced fat and salt meal"}
    - slot{"meal": ["hot diabetic meal"]}
    - utter_affirm_request
* affirm
    - action_request_travel


## Generated Story 16
* inform_travel
    - utter_ask_city
* inform_travel{"city": "madrid"}
    - slot{"city": ["budapest", "madrid"]}
    - utter_ask_time
* inform_travel{"bookDate": "23/10"}
    - slot{"bookDate": ["tomorrow","23/10"]}
    - utter_ask_meal
* inform_travel{"meal":"meal"}
    - slot{"meal": ["meal for infants"]}
    - utter_affirm_request
* affirm
    - action_request_travel


## Generated Story 17
* inform_travel
    - utter_ask_city
* inform_travel{"city": "cairo"}
    - slot{"city": ["madrid", "cairo"]}
    - utter_ask_time
* inform_travel{"bookDate": "23/1"}
    - slot{"bookDate": ["tomorrow","23/1"]}
    - utter_ask_meal
* inform_travel{"meal": "show me the menu"}
    - slot{"meal": ["show me the menu"]}
    - utter_meal_options
    - utter_ask_meal
    - slot{"meal": "hot diabetic meal"}
    - utter_affirm_request
* affirm
    - action_request_travel


## Generated Story 18
* inform_travel
    - utter_ask_city
* inform_travel{"city": "paris"}
    - slot{"city": ["alex", "paris"]}
    - utter_ask_time
* inform_travel{"bookDate": "20/1"}
    - slot{"bookDate": ["tomorrow","12/1"]}
    - utter_ask_meal
* inform_travel{"meal": "what are the options"}
- slot{"meal": ["what are the options"]}
- utter_meal_options
- slot{"options" : "We have hot diabetic meals, hindu, kosher, seafood, reduced fat and salt meals, meals for infants, and vegetarian meals"}
- utter_ask_meal
- slot{"meal": "hot diabetic meal"}
    - utter_affirm_request
* affirm
    - action_request_travel


## Generated Story 19
* inform_travel
    - utter_ask_city
* inform_travel{"city": "roma"}
    - slot{"city": ["cairo", "roma"]}
    - utter_ask_time
* inform_travel{"bookDate": "2/10"}
    - slot{"bookDate": ["tomorrow","10/1"]}
    - utter_ask_meal
* inform_travel{"meal": "what are the options"}
- slot{"meal": ["what are the options"]}
- utter_meal_options
- slot{"options" : "We have hot diabetic meals, hindu, kosher, seafood, reduced fat and salt meals, meals for infants, and vegetarian meals"}
- utter_ask_meal
- slot{"meal": "hindu meal"}
    - utter_affirm_request
* affirm
    - action_request_travel



## Generated Story 20
* inform_travel
- utter_ask_meal
* inform_travel{"meal": "what are the options"}
    - slot{"meal": ["what are the options"]}
    - utter_meal_options
    - utter_ask_meal
- slot{"meal": "seafood"}
    - utter_ask_city
* inform_travel{"city": "alex"}
    - slot{"city": ["cairo", "alex"]}
    - utter_ask_time
* inform_travel{"bookDate": "20/6"}
    - slot{"bookDate": ["tomorrow","20/6"]}
    - utter_affirm_request
* affirm
    - action_request_travel



## Generated Story 21
* inform_travel
    - utter_ask_city
* inform_travel{"bookDate": "6/6"}
    - slot{"bookDate": ["tomorrow","1/6"]}
    - utter_ask_meal
* inform_travel{"meal": "what are the options"}
- slot{"meal": ["what are the options"]}
- utter_meal_options
- slot{"options" : "We have hot diabetic meals, hindu, kosher, seafood, reduced fat and salt meals, meals for infants, and vegetarian meals"}
- utter_ask_meal
- slot{"meal": "meal with reduced fat and salt"}
* inform_travel{"city": "cairo"}
    - slot{"city": ["landon", "cairo"]}
    - utter_ask_time
    - utter_affirm_request
* affirm
    - action_request_travel



## Generated Story 22
* inform_travel
    - utter_ask_meal
* inform_travel{"meal":"kosher"}
    - slot{"meal": ["hot diabetic meal"]}
    - utter_ask_city
* inform_travel{"city": "dubai"}
    - slot{"city": ["cairo", "dubai"]}
    - utter_ask_time
* inform_travel{"bookDate": "1/7"}
    - slot{"bookDate": ["tomorrow","29/6"]}
    - utter_affirm_request
* affirm
    - action_request_travel


## Generated Story 23
* inform_travel
    - utter_ask_time
* inform_travel{"bookDate": "1/7"}
    - slot{"bookDate": ["tomorrow","29/6"]}
    - utter_ask_meal
  * inform_travel{"meal": "hot diabetic meal"}
      - slot{"meal": ["chicken and soup, please"]}
      - utter_ask_city
* inform_travel{"city": "cairo"}
    - slot{"city": ["cairo", "doha"]}
    - utter_affirm_request
* affirm
    - action_request_travel



## Generated Story 24
  * inform_travel
    - utter_ask_time
  * inform_travel{"bookDate": "3/8"}
    - slot{"bookDate": ["20/10"]}
    - utter_ask_city
  * inform_travel{"city": "katar"}
    - slot{"city": ["doha", "katar"]}
    - utter_ask_meal
* inform_travel{"meal": "what are the options"}
    - slot{"meal": ["what are the options"]}
    - utter_meal_options
    - slot{"options" : "We have hot diabetic meals, hindu, kosher, seafood, reduced fat and salt meals, meals for infants, and vegetarian meals"}
    - utter_ask_meal
    - slot{"meal": "meal with reduced fat and salt"}
    - utter_affirm_request
  * affirm
    - action_request_travel


## Generated Story 25
  * inform_travel
    - utter_ask_time
  * inform_travel{"bookDate": "8/8"}
    - slot{"bookDate": ["20/1"]}
    - utter_ask_city
  * inform_travel{"city": "cairo"}
    - slot{"city": ["bubai", "cairo"]}
    - utter_ask_meal
  * inform_travel{"meal": "hot diabetic meal"}
      - slot{"meal": ["hot diabetic meal"]}
      - utter_affirm_request
  * affirm
    - action_request_travel



## Generated Story 26
  * inform_travel
    - utter_ask_time
  * inform_travel{"bookDate": "30/9/2019"}
    - slot{"bookDate": ["20/10/2019"]}
    - utter_ask_meal
  * inform_travel{"meal": "kosher meal"}
      - slot{"meal": ["kosher meal"]}
    - utter_ask_city
  * inform_travel{"city": "cairo"}
    - slot{"city": ["Algiers", "cairo"]}
    - utter_affirm_request
  * affirm
    - action_request_travel


## Generated Story 27
  * inform_travel
        - utter_ask_time
  * inform_travel{"bookDate": "28/9"}
        - slot{"bookDate": ["1/10"]}
        - utter_ask_meal
    * inform_travel{"meal": "what are the options"}
        - slot{"meal": ["what are the options"]}
        - utter_meal_options
        - slot{"options" : "We have hot diabetic meals, hindu, kosher, seafood, reduced fat and salt meals, meals for infants, and vegetarian meals"}
        - utter_ask_meal
        - slot{"meal": "vegetarian meal"}
        - utter_ask_city
  * inform_travel{"city": "Vienna"}
        - slot{"city": ["Baku", "Vienna"]}
        - utter_affirm_request
  * affirm
        - action_request_travel



## Generated Story 28
    * inform_travel
        - utter_ask_meal
    * inform_travel{"meal": "ii"}
        - slot{"meal": ["hot diabetic meal"]}
        - utter_ask_time
    * inform_travel{"bookDate": "24/6"}
        - slot{"bookDate": ["1/7"]}
        - utter_ask_city
    * inform_travel{"city": "Gaborone"}
        - slot{"city": ["Bujumbura", "Gaborone"]}
        - utter_affirm_request
    * affirm
        - action_request_travel



## Generated Story 29
    * inform_travel
        - utter_ask_time
    * inform_travel{"bookDate": "6/6"}
        - slot{"bookDate": ["1/8"]}
        - utter_ask_meal
    * inform_travel{"meal": "what are the options"}
        - slot{"meal": ["what are the options"]}
        - utter_meal_options
        - slot{"options" : "We have hot diabetic meals, hindu, kosher, seafood, reduced fat and salt meals, meals for infants, and vegetarian meals"}
        - utter_ask_meal
        - slot{"meal": "kosher meal"}
        - utter_ask_city
    * inform_travel{"city": "Havana"}
        - slot{"city": ["Roseau", "Havana"]}
        - utter_affirm_request
    * affirm
        - action_request_travel


## Generated Story 30
    * inform_travel
          - utter_ask_time
    * inform_travel{"bookDate": "3/10"}
          - slot{"bookDate": ["10/10"]}
          - utter_ask_meal
    * inform_travel{"meal": "seafood meal"}
          - slot{"meal": ["seafood meal"]}
          - utter_ask_city
    * inform_travel{"city": "Tokyo"}
          - slot{"city": ["cairo", "Tokyo"]}
          - utter_affirm_request
    * affirm
          - action_request_travel


## Generated Story 31
      * inform_travel
              - utter_ask_time
      * inform_travel{"bookDate": "3/3"}
              - slot{"bookDate": ["5/3"]}
              - utter_ask_meal
          * inform_travel{"meal": "what are the options"}
              - slot{"meal": ["what are the options"]}
              - utter_meal_options
              - slot{"options" : "We have hot diabetic meals, hindu, kosher, seafood, reduced fat and salt meals, meals for infants, and vegetarian meals"}
              - utter_ask_meal
              - slot{"meal": "hot diabetic meal"}
              - utter_ask_city
      * inform_travel{"city": "Tokyo"}
              - slot{"city": ["Monaco", "Tokyo"]}
              - utter_affirm_request
      * affirm
              - action_request_travel



## Generated Story 32
      * inform_travel
                - utter_ask_time
      * inform_travel{"bookDate": "29/3/2018"}
                - slot{"bookDate": ["5/5/2018"]}
                - utter_ask_city
      * inform_travel{"city": "Tunis"}
                - slot{"city": ["Bratislava", "Tunis"]}
                - utter_ask_meal
            * inform_travel{"meal": "what are the options"}
                - slot{"meal": ["what are the options"]}
                - utter_meal_options
                - slot{"options" : "We have hot diabetic meals, hindu, kosher, seafood, reduced fat and salt meals, meals for infants, and vegetarian meals"}
                - utter_ask_meal
                - slot{"meal": "hot diabetic meal"}
                - utter_affirm_request
      * affirm
                - action_request_travel



## Generated Story 33
        * inform_travel
                  - utter_ask_time
        * inform_travel{"bookDate": "8/3"}
                  - slot{"bookDate": ["18/5"]}
                  - utter_ask_meal
        * inform_travel{"meal": "kosher"}
                  - slot{"meal": ["kosher"]}
                  - utter_ask_city
        * inform_travel{"city": "Dakar"}
                - slot{"city": ["Riyadh", "Dakar"]}
                - utter_ask_time
        * affirm
                - action_request_travel


## Generated Story 34
      * greet
            - utter_greet
      * inform_travel
            - utter_ask_city
      * inform_travel{"city": "Oslo"}
            - slot{"city": ["cairo", "Oslo"]}
            - utter_ask_time
      * inform_travel{"bookDate": "monday"}
            - slot{"bookDate": ["today", "monday"]}
            - utter_ask_meal
        * inform_travel{"meal": "show me the options"}
            - slot{"meal": ["show me the options"]}
            - utter_meal_options
            - slot{"options" : "We have hot diabetic meals, hindu, kosher, seafood, reduced fat and salt meals, meals for infants, and vegetarian meals"}
            - utter_ask_meal
            - slot{"meal": "seafood meal"}
            - utter_affirm_request
      * affirm
            - action_request_travel




## Generated Story 35
    * greet
          - utter_greet
          - utter_meal_options
          - slot{"options" : "We have hot diabetic meals, hindu, kosher, seafood, reduced fat and salt meals, meals for infants, and vegetarian meals"}
          - utter_ask_meal
      * inform_travel{"meal": "what options do you have?"}
          - slot{"meal": ["what options do you have?"]}
          - utter_meal_options
          - slot{"options" : "We have hot diabetic meals, hindu, kosher, seafood, reduced fat and salt meals, meals for infants, and vegetarian meals"}
          - utter_ask_meal
          - slot{"meal": "hindu meal"}
          - utter_ask_city
    * inform_travel{"city": "Warsaw"}
          - slot{"city": ["cairo", "Warsaw"]}
          - utter_ask_time
    * inform_travel{"bookDate": "friday"}
          - slot{"bookDate": ["today", "friday"]}
          - utter_affirm_request
    * affirm
          - action_request_travel



## Generated Story 36
      * greet
          - utter_greet
      * inform_travel
          - utter_ask_city
      * inform_travel{"city": "Kigali"}
          - slot{"city": ["cairo", "Kigali"]}
          - utter_ask_time
      * inform_travel{"bookDate": "9/2"}
          - slot{"bookDate": ["18/3"]}
          - utter_ask_meal
      * inform_travel{"meal": "what are the options"}
          - slot{"meal": ["what are the options"]}
          - utter_meal_options
          - utter_ask_meal
          - slot{"meal": "vegetarian meal"}
          - utter_affirm_request
      * affirm
          - action_request_travel



## Generated Story 37
      * greet
          - utter_greet
    * inform_travel{"city": "Addis Ababa", "bookDate": "8 dec", "meal": "reduced fat and salt meal"}
          - slot{"bookDate": ["9 aug", "13 dec"]}
          - slot{"city": ["cairo", "Addis Ababa"]}
          - utter_ask_meal
      * inform_travel{"meal": "what options do you have?"}
          - slot{"meal": ["what options do you have?"]}
          - utter_meal_options
          - slot{"options" : "We have hot diabetic meals, hindu, kosher, seafood, reduced fat and salt meals, meals for infants, and vegetarian meals"}
          - utter_ask_meal
          - slot{"meal": "hindu meal"}
          - utter_affirm_request
    * affirm
          - action_request_travel


## Generated Story 38
      * greet
            - utter_greet
      * inform_travel{"city": "cairo", "bookDate": "8 November", "meal": "what is the menu"}
            - slot{"bookDate": ["1 January", "15 march"]}
            - slot{"city": ["San Jose", "cairo"]}
            - utter_ask_meal
        * inform_travel{"meal": "what are the options"}
            - slot{"meal": ["what are the options"]}
            - utter_meal_options
            - utter_ask_meal
            - slot{"meal": "reduced fat and salt meal"}
            - utter_affirm_request
      * affirm
            - action_request_travel



## Generated Story 39
      * greet
              - utter_greet
      * inform_travel{"city": "Dili", "bookDate": "30 aug", "meal": "show me the menu to choose from"}
              - slot{"bookDate": ["1 Jan", "15 mar"]}
              - slot{"city": ["Paris", "Dili"]}
              - slot{"meal": "show me the menu to choose from"}
              - utter_meal_options
              - utter_ask_meal
              - slot{"meal": "hot diabetic one"}
              - utter_affirm_request
      * affirm
            - action_request_travel


## Generated Story 40
      * greet
            - utter_greet
      * inform_travel{"city": "cairo", "bookDate": "7-1", "meal": "vegetarian meal"}
            - slot{"bookDate": ["9-1", "15-2"]}
            - slot{"city": ["Roseau", "cairo"]}
            - utter_ask_meal
        * inform_travel{"meal": "what are the options"}
            - slot{"meal": ["what are the options"]}
            - utter_meal_options
            - utter_ask_meal
            - slot{"meal": "vegetarian meal"}
            - utter_affirm_request
      * affirm
            - action_request_travel


## Generated Story 41
      * greet
              - utter_greet
      * inform_travel{"city": "cairo", "bookDate": "1-1", "meal": "hindu meal"}
              - slot{"city": ["cairo", "Berlin"]}
              - slot{"bookDate": ["14-4", "29-5"]}
              - slot{"meal": ["hindu meal"]}
              - utter_affirm_request
      * affirm
              - action_request_travel
      * thankyou
              - utter_thankyou


## Generated Story 42
      * greet
            - utter_greet
      * inform_travel{"bookDate": "5th aug", "city": "Amman", "meal": "kosher meal"}
            - slot{"city": ["Amman", "cairo"]}
            - slot{"bookDate": ["1st jan", "20th jan"]}
            - slot{"meal": ["kosher meal"]}
            - utter_affirm_request
      * affirm
            - action_request_travel
      * thankyou
            - utter_thankyou



## Generated Story 43
            * greet
                - utter_greet
            * inform_travel{"city": "cairo", "bookDate": "2nd jan", "meal": "what is in the menu"}
                - slot{"bookDate": ["14th jan", "2nd feb"]}
                - slot{"city": ["cairo", "paris"]}
                - slot{"meal": ["what is in the menu"]}
                - utter_meal_options
                - utter_ask_meal
                - slot{"meal": "kosher meal"}
                - utter_affirm_request
            * affirm
                - action_request_travel
            * thankyou
                - utter_thankyou



## Generated Story 44
              * greet
                    - utter_greet
              * inform_travel{"city": "Tokyo", "bookDate": "3/3", "meal": "reduced fat and salt meal"}
                    - slot{"bookDate": ["14/9", "2/11"]}
                    - slot{"city": ["Tokyo", "cairo"]}
                    - slot {"meal": ["reduced fat and salt meal"]}
                    - utter_affirm_request
              * affirm
                    - action_request_travel
              * thankyou
                    - utter_thankyou

## Generated Story 45
      * greet
              - utter_greet
      * inform_travel{"city": "Nairobi", "bookDate": "1/9", "meal": "vegetarian meal"}
              - slot{"city": ["Nairobi", "tokyo"]}
              - slot{"bookDate": ["2/9", "21/9"]}
              - slot{"meal": ["vegetarian meal"]}
              - utter_affirm_request
      * affirm
              - action_request_travel
      * thankyou
              - utter_thankyou


## Generated Story 46
      * inform_travel
              - utter_ask_time
      * inform_travel{"bookDate": "9/5/2018"}
              - slot{"bookDate": ["8/8/2018"]}
              - utter_ask_city
      * inform_travel{"city": "cairo"}
              - slot{"city": ["Kuwait", "cairo"]}
              - utter_ask_meal
              - utter_ask_meal
          * inform_travel{"meal": "what are the options"}
              - slot{"meal": ["what are the options"]}
              - utter_meal_options
              - utter_ask_meal
              - slot{"meal": "hot diabetic meal"}
              - utter_affirm_request
      * affirm
              - action_request_travel



## Generated Story 47
      * inform_travel
              - utter_ask_city
      * inform_travel{"city": "Tehran"}
              - slot{"city": ["Tehran", "cairo"]}
              - utter_ask_meal
          * inform_travel{"meal": "what are the options"}
              - slot{"meal": ["what are the options"]}
              - utter_meal_options
              - utter_ask_meal
              - slot{"meal": "vegetarian meal"}
              - utter_ask_time
      * inform_travel{"bookDate": "6-1-2018"}
              - slot{"bookDate": ["8-5-2018"]}
              - utter_affirm_request
      * affirm
              - action_request_travel



## Generated Story 48
      * inform_travel
              - utter_ask_city
      * inform_travel{"city": "alex"}
              - slot{"city": ["Tehran", "alex"]}
              - utter_ask_time
      * inform_travel{"bookDate": "4-1-18"}
              - slot{"bookDate": ["8-8-18"]}
              - utter_ask_meal
      * inform_travel{"meal": "meal for infants, please"}
              - slot{"meal": ["meal for infants, please"]}
              - utter_affirm_request
      * affirm
              - action_request_travel


## Generated Story 49
      * inform_travel
          - utter_ask_city
      * inform_travel{"city": "Pristina"}
          - slot{"city": ["Riga", "Pristina"]}
          - utter_ask_meal
      * inform_travel{"meal": "kosher meal"}
          - slot{"meal": ["kosher meal"]}
          - utter_ask_time
      * inform_travel{"bookDate": "3rd april"}
          - slot{"bookDate": ["1-8-18"]}
          - utter_affirm_request
      * affirm
            - action_request_travel


## Generated Story 50
    * greet
        - utter_greet
    * inform_travel
        - utter_ask_city
    * inform_travel{"city": "male"}
        - slot{"city": ["alex", "male"]}
        - utter_ask_time
    * inform_travel{"bookDate": "thur"}
        - slot{"bookDate": ["sunday"]}
        - utter_ask_meal
    * inform_travel{"meal": "I need a Vegetarian Meal please"}
        - slot{"meal": ["I need a Vegetarian Meal please"]}
        - utter_affirm_request
    * affirm
        - action_request_travel


## Generated Story 51
    * greet
          - utter_greet
    * inform_travel
          - utter_ask_city
    * inform_travel{"city": "Wellington"}
          - slot{"city": ["cairo", "Wellington"]}
          - utter_ask_time
    * inform_travel{"bookDate": "2/3"}
          - slot{"bookDate": ["2/3"]}
          - utter_ask_meal
    * inform_travel{"meal": "hot diabetic meal"}
          - slot{"meal": ["hot diabetic meal"]}
          - utter_affirm_request
    * affirm
          - action_request_travel



## Generated Story 52
      * greet
            - utter_greet
      * inform_travel
            - utter_ask_city
     * inform_travel{"bookDate": "20-3"}
            - slot{"bookDate": ["2-4"]}
            - utter_ask_city
      * inform_travel{"city": "Kingstown"}
            - slot{"city": ["Kingstown", "cairo"]}
            - utter_ask_meal
        * inform_travel{"meal": "what are the options"}
            - slot{"meal": ["what are the options"]}
            - utter_meal_options
            - utter_ask_meal
            - slot{"meal": "hindu"}
            - utter_affirm_request
      * affirm
            - action_request_travel



## Generated Story 53
    * inform_travel{"city": "cairo"}
        - slot{"city": ["Tokyo", "Ankara", "cairo"]}
        - utter_ask_time
    * inform_travel{"bookDate": "20/3"}
        - slot{"bookDate": ["18/2", "25/5"]}
        - utter_ask_meal
  * inform_travel{"meal": "hindu meal"}
        - slot{"meal": ["hindu meal"]}
        - utter_affirm_request
    * affirm
        - action_request_travel
    * thankyou
          - utter_thankyou



## Generated Story 54
              * inform_travel{"city": "Stockholm"}
                  - slot{"city": ["Tokyo", "Stockholm"]}
                  - utter_ask_time
              * inform_travel{"bookDate": "2-10"}
                  - slot{"bookDate": ["3-10", "25-10"]}
                  - utter_ask_meal
            * inform_travel{"meal": "seafood meal please"}
                  - slot{"meal": ["seafood meal please"]}
                  - utter_affirm_request
              * affirm
                  - action_request_travel
              * thankyou
                    - utter_thankyou


## Generated Story 55
          * inform_travel{"city": "Lome"}
                - slot{"city": ["Lome", "Stockholm"]}
                - utter_ask_time
          * inform_travel{"bookDate": "2 September"}
                - slot{"bookDate": ["3 august", "25 august"]}
                - utter_ask_meal
          * inform_travel{"meal": "bring me, a vegetarian meal please"}
                - slot{"meal": ["bring me, a vegetarian meal please"]}
                - utter_affirm_request
          * affirm
                - action_request_travel
          * thankyou
                - utter_thankyou


## Generated Story 56
      * inform_travel{"city": "cairo"}
            - slot{"city": ["alex", "Lisbon"]}
            - utter_ask_time
      * inform_travel{"bookDate": "2 august, 2018"}
            - slot{"bookDate": ["3 august, 2018", "20 august, 2018"]}
            - utter_ask_meal
        * inform_travel{"meal": "what are the options"}
            - slot{"meal": ["what are the options"]}
            - utter_meal_options
            - utter_ask_meal
            - slot{"meal": "reduced fat and salt meal"}
            - utter_affirm_request
      * affirm
            - action_request_travel
      * thankyou
            - utter_thankyou


## Generated Story 57
      * inform_travel{"city": "Doha"}
            - slot{"city": ["Lisbon", "cairo"]}
            - utter_ask_meal
      * inform_travel{"meal": "hindu"}
            - slot{"meal": ["hindu"]}
            - utter_ask_time
      * inform_travel{"bookDate": "2 aug, 2018"}
            - slot{"bookDate": ["3 march, 2018", "20 april, 2018"]}
            - utter_affirm_request
      * affirm
            - action_request_travel
      * thankyou
            - utter_thankyou


## Generated Story 58
    * inform_travel
          - utter_ask_city
    * inform_travel{"city": "Victoria"}
          - slot{"city": ["cairo", "Victoria"]}
          - utter_affirm_request
    * inform_travel{"bookDate": "tues"}
          - slot{"bookDate": ["thur"]}
          - utter_ask_time
          - utter_ask_meal
    * inform_travel{"meal": "show me the menu"}
          - slot{"meal": ["Show me the menu"]}
          - utter_meal_options
          - utter_ask_meal
          - slot{"meal": "one reduced fat and salt meal"}
    * affirm
          - action_request_travel
    * thankyou
          - utter_thankyou



## Generated Story 59
      * inform_travel{"city": "Moscow"}
            - slot{"city": ["Tokyo", "Moscow"]}
            - utter_ask_time
      * inform_travel{"bookDate": "20-2"}
              - slot{"bookDate": ["12-5", "27-5"]}
              - utter_ask_meal
     * inform_travel{"meal": "vegetarian meal"}
              - slot{"meal": ["vegetarian meal"]}
              - utter_affirm_request
      * affirm
              - action_request_travel
      * thankyou
              - utter_thankyou



## Generated Story 60
      * greet
            - utter_greet
      * inform_travel
            - utter_ask_time
      * inform_travel{"bookDate": "20 march"}
            - slot{"bookDate": ["2 april"]}
            - utter_ask_city
      * inform_travel{"city": "cairo"}
            - slot{"city": ["cairo", "Riyadh", "Singapore"]}
            - utter_ask_meal
      * inform_travel{"meal": "Show me the menu"}
            - slot{"meal": ["Show me the menu"]}
            - utter_meal_options
            - utter_ask_meal
            - slot{"meal": "vegetarian meal"}
            - utter_affirm_request
      * affirm
            - action_request_travel


## Generated Story 61
    * greet
          - utter_greet
    * inform_travel{"city": "cairo", "bookDate": "2/10"}
          - slot{"city": ["alex", "Honiara"]}
          - slot{"bookDate": ["12/8/2018", "2/2/2019"]}
          - utter_ask_meal
    * inform_travel{"meal": "kosher"}
          - slot{"meal": ["kosher"]}
          - utter_affirm_request
    * affirm
          - action_request_travel
    * thankyou
          - utter_thankyou


## Generated Story 62
          * greet
              - utter_greet
          * inform_travel{"city": "Singapore", "bookDate": "2/sep/2018"}
              - slot{"bookDate": ["5/sep/2018", "20/october/2018"]}
              - slot{"city": ["Moscow", "Singapore"]}
              - utter_ask_meal
        * inform_travel{"meal": "what is the menu"}
              - utter_meal_options
              - utter_ask_meal
              - slot{"meal": ["reduced fat and salt meal"]}
              - utter_affirm_request
          * affirm
              - action_request_travel
          * thankyou
              - utter_thankyou



## Generated Story 63
    * greet
          - utter_greet
    * travel_status
          - action_check_status
   * inform_travel{"city": "Taipei", "bookDate": "2/may"}
        - slot{"bookDate": ["5/may/2018", "16/june"]}
        - slot{"city": ["Taipei", "Singapore"]}
        - utter_ask_meal
  * inform_travel{"meal": "Show me samples"}
        - utter_meal_options
        - utter_ask_meal
        - slot{"meal": "seafood meal"}
        - utter_affirm_request
  * affirm
        - action_request_travel
    * thankyou
          - utter_thankyou


## Generated Story 64
    * greet
        - utter_greet
    * inform_travel{"city": "Tunis", "bookDate": "20th September, 2018"}
        - slot{"bookDate": ["12th april, 2019", "1st may, 2019"]}
        - slot{"city": ["cairo", "Tunis"]}
        - utter_ask_meal
    * inform_travel{"meal": "show me the menu!"}
        - slot{"meal": ["show me the menu!"]}
        - utter_meal_options
        - utter_ask_meal
        - slot{"meal": "vegetarian meal"}
        - utter_affirm_request
    * affirm
        - action_request_travel
    * thankyou
        - utter_thankyou


## Generated Story 65
      * greet
          - utter_greet
      * inform_travel{"city": "cairo", "bookDate": "10/9"}
          - slot{"bookDate": ["11/9", "13/10"]}
          - slot{"city": ["Mbabane", "Tunis"]}
          - utter_ask_meal
    * inform_travel{"meal": "what is the menu?"}
          - utter_meal_options
          - utter_ask_meal
          - slot{"meal": ["meal for infants"]}
      * cancel_travel
          - utter_affirm_cancel
      * affirm
          - action_cancel_travel
      * thankyou
          - utter_thankyou



## Generated Story 66
      * greet
              - utter_greet
      * inform_travel{"city": "Bangkok", "bookDate": "2/sep"}
              - slot{"bookDate": ["5/Sep", "20/oct"]}
              - slot{"city": ["Moscow", "Bangkok"]}
              - utter_ask_meal
          * inform_travel{"meal": "show me the menu"}
              - slot{"meal": ["show me the menu"]}
              - utter_meal_options
              - utter_ask_meal
              - slot{"meal": "vegetarian meal, please"}
              - utter_affirm_request
      * affirm
              - action_request_travel
      * thankyou
              - utter_thankyou


## Generated Story 67
    * inform_travel{"city": "Dushanbe"}
                  - slot{"city": ["budapest", "Dushanbe"]}
                  - utter_ask_time
    * inform_travel{"bookDate": "2019-06-15"}
                  - slot{"bookDate": ["2019-06-15", "2019-08-15"]}
                  - utter_ask_meal
    * inform_travel{"meal": "what is the menu?"}
                  - utter_meal_options
                  - utter_ask_meal
                  - slot{"meal": ["reduced fat and salt meal"]}
                  - utter_affirm_request
    * affirm
                  - action_request_travel
    * thankyou
                  - utter_thankyou



## Generated Story 68
      * inform_travel{"city": "Harare"}
          - slot{"city": ["cairo", "Harare"]}
          - utter_ask_meal
      * inform_travel{"meal": "show me the menu"}
          - slot{"meal": ["show me the menu"]}
          - utter_meal_options
          - utter_ask_meal
          - slot{"meal": "meal for infants"}
          - utter_ask_time
      * inform_travel{"bookDate": "June 15"}
          - slot{"bookDate": ["June 15", "july 18"]}
          - utter_affirm_request
      * affirm
          - action_request_travel
      * thankyou
          - utter_thankyou



## Generated Story 69
      * greet
            - utter_greet
      * inform_travel{"city": "cairo", "bookDate": "Monday, June 15, 2018", "meal": "one meal for infants"}
            - slot{"bookDate": ["tuesday, July 10, 2019", "thursday, July 16, 2019"]}
            - slot{"meal": ["one meal for infants"]}
            - slot{"city": ["Bangkok", "cairo"]}
            - utter_affirm_request
      * affirm
            - action_request_travel
      * thankyou
            - utter_thankyou


## Generated Story 70
      * inform_travel{"city": "Harare"}
            - slot{"city": ["cairo", "Harare"]}
            - utter_ask_meal
* inform_travel{"meal": "what is the menu?"}
            - utter_meal_options
            - utter_ask_meal
            - slot{"meal": ["hindu meal"]}
            - utter_ask_time
      * inform_travel{"bookDate": "June 15"}
            - slot{"bookDate": ["thur, July 12, 18", "sat, jan 11, 19"]}
            - utter_affirm_request
      * affirm
            - action_request_travel
      * thankyou
            - utter_thankyou



## Generated Story 71
      * inform_travel{"bookDate": "sat, Jul 12, 2018"}
            - slot{"bookDate": ["thur, Jul 13, 2018", "sun, dec 10, 2018"]}
            - utter_ask_meal
      * inform_travel{"meal": "what is the menu?"}
            - utter_meal_options
            - utter_ask_meal
            - slot{"meal": ["single reduced fat and salt meal"]}
            - utter_ask_city
      * inform_travel{"city": "Madrid"}
            - slot{"city": ["Madrid", "Mbabane"]}
            - utter_affirm_request
      * affirm
            - action_request_travel
      * thankyou
            - utter_thankyou


## Generated Story 72
      * greet
            - utter_greet
      * inform_travel{"bookDate": "18th June"}
            - slot{"bookDate": ["august 15", "august 28"]}    
            - utter_ask_meal
      * inform_travel{"meal":"reduced fat and salt meal"}
            - slot{"meal": ["reduced fat and salt meal"]}  
            - utter_ask_city
            - slot{"city": ["cairo", "Madrid"]}
            - utter_affirm_request
      * affirm
              - action_request_travel
      * thankyou
              - utter_thankyou


## Generated Story 73
      * inform_travel{"city": "Juba"}
            - slot{"city": ["cairo", "Riyadh", "Juba"]}
            - utter_ask_time
      * inform_travel{"bookDate": "tomorrow, 22 march"}
            - slot{"bookDate": ["tomorrow, 22 march"]}
            - utter_ask_meal
* inform_travel{"meal": "what is the menu?"}
            - utter_meal_options
            - utter_ask_meal
            - slot{"meal": ["hindu meal please"]}
            - utter_affirm_request
      * affirm
            - action_request_travel





## Generated Story 74
      * inform_travel{"city": "Bern"}
            - slot{"city": ["Bern", "Riyadh"]}
            - utter_ask_time
      * inform_travel{"bookDate": "today, 25th march"}
            - slot{"bookDate": ["29th april"]}
            - utter_ask_meal
        * inform_travel{"meal": "show me the menu"}
            - slot{"meal": ["show me the menu"]}
            - utter_meal_options
            - utter_ask_meal
            - slot{"meal": "vegetarian meal"}
            - utter_affirm_request
      * affirm
            - action_request_travel



## Generated Story 75
    * inform_travel{"city": "cairo"}
          - slot{"city": ["Taipei", "cairo"]}
          - utter_ask_time
    * inform_travel{"bookDate": "2nd july"}
          - slot{"bookDate": ["august 10", "october 18"]}
          - utter_ask_meal
* inform_travel{"meal": "what is the menu?"}
          - utter_meal_options
          - utter_ask_meal
          - slot{"meal": ["seafood meal"]}
          - utter_affirm_request
    * affirm
          - action_request_travel


## Generated Story 76
    * inform_travel{"city": "Juba "}
          - slot{"city": ["Juba ", "Tashkent"]}
          - utter_ask_time
    * inform_travel{"bookDate": "3rd july"}
          - slot{"bookDate": ["3rd july", "10th September"]}
          - utter_ask_meal
    * inform_travel{"meal": "seafood meal"}
          - slot{"meal": ["seafood meal"]}
          - utter_affirm_request
    * affirm
          - action_request_travel


## Generated Story 77
      * inform_travel{"city": "cairo"}
              - slot{"city": ["Tunis", "cairo"]}
              - utter_ask_meal
          * inform_travel{"meal": "show me the menu"}
              - slot{"meal": ["show me the menu"]}
              - utter_meal_options
              - utter_ask_meal
              - slot{"meal": "kosher meal, please"}
              - utter_ask_time
        * inform_travel{"bookDate": "july 18th"}
              - slot{"bookDate": ["july 18th", "august 20th"]}
              - utter_affirm_request
        * affirm
              - action_request_travel
        * thankyou
              - utter_thankyou



## Generated Story 78
      * greet
            - utter_greet
      * inform_travel{"city": "Kampala", "bookDate": "20th sep"}
            - slot{"bookDate": ["21th sep", "17th may"]}
            - slot{"city": ["cairo", "Kampala"]}
            - utter_ask_meal
      * inform_travel{"meal": "seafood meal"}
            - slot{"meal": ["seafood meal"]}
            - utter_affirm_request
      * affirm
            - action_request_travel
      * thankyou
            - utter_thankyou


## Generated Story 79
    * greet
          - utter_greet
    * inform_travel{"city": "male", "bookDate": "10, august", "meal": "meals for infants, please"}
          - slot{"bookDate": ["10, august", "13, october"]}
          - slot{"city": ["Singapore", "male"]}
          - slot{"meal": ["meal for infants, please"]}
    * cancel_travel
          - utter_affirm_cancel
    * affirm
          - action_cancel_travel
    * thankyou
          - utter_thankyou



## Generated Story 80
    * greet
          - utter_greet
    * inform_travel{"city": "Lisbon", "bookDate": "10th, august", "meal": "vegetarian Meal"}
          - slot{"bookDate": ["10th, Lisbon", "13th, cairo"]}
          - slot{"city": ["Lisbon", "cairo"]}
          - slot{"meal": ["vegetarian Meal"]}
    * cancel_travel
          - utter_affirm_cancel
    * affirm
          - action_cancel_travel
    * thankyou
          - utter_thankyou


## Generated Story 81
    * greet
          - utter_greet
    * inform_travel{"city": "Apia", "bookDate": "10th, august"}
          - slot{"bookDate": ["10th, Lisbon", "13th, Apia"]}
          - slot{"city": ["Lisbon", "cairo"]}
          - utter_ask_meal
* inform_travel{"meal": "what is the menu?"}
          - utter_meal_options
          - utter_ask_meal
          - slot{"meal": ["hot diabetic meal"]}
    * cancel_travel
          - utter_affirm_cancel
    * affirm
        - action_cancel_travel
    * thankyou
          - utter_thankyou



## Generated Story 82
    * greet
          - utter_greet
    * inform_travel{"city": "Madrid", "bookDate": "1st, may", "meal": "vegetarian meal"}
          - slot{"bookDate": ["1st, Lisbon", "1st, Apia"]}
          - slot{"city": ["Madrid", "Apia"]}
          - slot{"meal": ["vegetarian meal"]}
    * cancel_travel
          - utter_affirm_cancel
    * affirm
          - action_cancel_travel
    * thankyou
          - utter_thankyou


## Generated Story 83
      * greet
            - utter_greet
      * inform_travel{"bookDate": "11th June"}
            - slot{"bookDate": ["august 9", "august 18"]}      
            - utter_ask_city
            - slot{"city": ["Bern", "Madrid"]}
            - utter_ask_meal
      * inform_travel{"meal": "a hot diabetic meal"}
            - slot{"meal": ["a hot diabetic meal"]}
            - utter_affirm_request
      * affirm
            - action_request_travel


## Generated Story 84
    * inform_travel
          - utter_ask_time
    * inform_travel{"bookDate": "20/10"}
          - slot{"bookDate": ["today","20/10"]}
          - utter_ask_city
    * inform_travel{"city": "Warsaw"}
          - slot{"city": ["Warsaw", "cairo"]}
          - utter_ask_meal
    * inform_travel{"meal": "seafood"}
          - slot{"meal": ["seafood"]}
          - utter_affirm_request
    * affirm
          - action_request_travel


## Generated Story 85
    * greet
          - utter_greet
    * inform_travel
          - utter_ask_city
    * inform_travel{"city": "cairo"}
          - slot{"city": ["Doha", "Lisbon"]}
          - utter_ask_time
    * inform_travel{"bookDate": "saturday"}
          - slot{"bookDate": ["29/10/2018"]}
          - utter_ask_meal
    * inform_travel{"meal":"seafood"}
          - slot{"meal": ["seafood"]}
          - utter_affirm_request
    * affirm
         - action_request_travel



## Generated Story 86
    * greet
        - utter_greet
    * inform_travel{"city": "Manila", "bookDate": "11/6", "meal": "soup"}
        - slot{"bookDate": ["12/8"]}
        - slot{"city": ["Manila", "Lisbon"]}
        - slot{"meal": ["kosher"]}
        - utter_affirm_request
    * affirm
        - action_request_travel
    * thankyou
        - utter_thankyou


## Generated Story 87
    * greet
          - utter_greet
    * inform_travel{"city": "Doha", "bookDate": "1/1", "meat": "carret soup"}
          - slot{"bookDate": ["1/1", "1/1"]}
          - slot{"city": ["Doha", "cairo"]}
          - slot{"meal": ["seafood"]}
    * cancel_travel
          - utter_affirm_cancel
    * affirm
          - action_cancel_travel
    * thankyou
          - utter_thankyou


## Generated Story 88
    * inform_travel{"bookDate": "tomorrow"}
          - slot{"bookDate": ["tomorrow", "12th jan"]}
            - utter_ask_time
    * inform_travel{"city": "Monaco "}
          - slot{"city": ["Monaco ", "Tashkent"]}
          - utter_ask_meal
    * inform_travel{"meal": "hindu"}
          - slot{"meal": ["hindu"]}
          - utter_affirm_request
    * affirm
          - action_request_travel



## Generated Story 89
    * greet
        - utter_greet
    * inform_travel
        - utter_ask_meal
    * inform_travel{"meal": "kosher"}
        - slot{"meal": ["kosher"]}
        - utter_ask_city
    * inform_travel{"city": "Maputo"}
        - slot{"city": ["Maputo", "madrid"]}
        - utter_ask_time
    * inform_travel{"bookDate": "2nd march, 2018"}
        - slot{"bookDate": ["tomorrow","3/3"]}
        - utter_affirm_request
    * affirm
        - action_request_travel


## Generated Story 90
      * greet
          - utter_greet
      * inform_travel{"bookDate": "28-july"}
          - slot{"bookDate": ["3-august", "18-September"]}      
          - utter_ask_city
          - slot{"city": ["Madrid", "Riga"]}
          - utter_ask_meal
          - slot{"meal": ["reduced fat and salt meal"]}
          - utter_affirm_request
      * affirm
          - action_request_travel



## Generated Story 91
   * inform_travel
        - utter_ask_city
   * inform_travel{"city": "Kuwait City"}
        - slot{"city": ["cairo", "Kuwait City"]}
        - utter_ask_time
  * inform_travel{"bookDate": "12-1"}
        - slot{"bookDate": ["10-3"]}
        - utter_ask_meal
  * inform_travel{"meal": "a meal for Infants!"}
        - slot{"meal": ["a meal for Infants!"]}
        - utter_affirm_request
  * affirm
        - action_request_travel


## Generated Story 92
    * greet
        - utter_greet
    * inform_travel
        - utter_ask_city
    * inform_travel{"city": "Kuwait"}
        - slot{"city": ["Kuwait", "New Delhi"]}
        - utter_ask_time
    * inform_travel{"bookDate": "12th march"}
        - slot{"bookDate": ["1st april"]}
        - utter_ask_meal
   * inform_travel{"meal": "Vegetarian Meal please!"}
        - slot{"meal": ["Vegetarian Meal please!"]}
        - utter_affirm_request
    * affirm
        - action_request_travel


## Generated Story 93
    * greet
      - utter_greet
    * inform_travel{"city": "Tehran", "bookDate": "3/7/2018", "meal": "vegetarian meal"}
      - slot{"bookDate": ["today", "3/7/2018", "1/9/2018"]}
      - slot{"meal": ["vegetarian meal"]}
      - slot{"city": ["Tehran", "Dublin"]}
      - utter_affirm_request
    * affirm
      - action_request_travel
    * thankyou
        - utter_thankyou



## Generated Story 94
    * inform_travel{"city": "Berlin"}
        - slot{"city": ["Berlin", "cairo"]}
        - utter_ask_time
    * inform_travel{"bookDate": "17th January"}
        - slot{"bookDate": ["19th January", "25th January"]}
        - slot{"meal": ["kosher"]}
        - utter_affirm_request
    * affirm
        - action_request_travel
    * thankyou
        - utter_thankyou



## Generated Story 95
    * greet
      - utter_greet
    * inform_travel{"city": "Tokyo"}
      - slot{"city": ["Tokyo", "Berlin"]}
      - utter_ask_time
    * inform_travel{"bookDate": "3rd Oct"}
      - slot{"bookDate": ["4th Oct", "25th nov"]}
      - utter_ask_meal
    * inform_travel{"meal": "a meal for Infants!"}
      - slot{"meal": ["a meal for Infants!"]}
      - utter_affirm_request
    * affirm
      - action_request_travel
    * thankyou
      - utter_thankyou




## Generated Story 96
    * greet
        - utter_greet
    * inform_travel{"city": "Tunis"}
        - slot{"city": ["Tunis", "Ankara"]}
        - utter_ask_time
    * inform_travel{"bookDate": "18/1"}
        - slot{"bookDate": ["18/1", "25/2"]}
        - utter_ask_meal
      * inform_travel{"meal":"a meal for Infants!"}
        - slot{"meal": ["a meal for Infants!"]}
        - utter_affirm_request
    * affirm
        - action_request_travel


## Generated Story 97
    * inform_travel
        - utter_ask_city
    * inform_travel{"city": "Kampala"}
        - slot{"city": ["Doha", "Kampala"]}
        - utter_ask_meal
      * inform_travel{"meal" :"seafood"}
        - slot{"meal": ["seafood"]}
        - utter_ask_time
    * inform_travel{"bookDate": "tomorrow"}
        - slot{"bookDate": ["25th april"]}
        - utter_affirm_request
    * affirm
        - action_request_travel



## Generated Story 98
    * inform_travel
        - utter_ask_time
    * inform_travel{"bookDate": "21th mar"}
        - slot{"bookDate": ["19th apr"]}
        - utter_ask_city
    * inform_travel{"city": "Gaborone"}
        - slot{"city": ["Bujumbura", "Gaborone"]}
        - utter_ask_meal
    * inform_travel{"meal" : "hindu"}
        - slot{"meal": ["hindu"]}
        - utter_affirm_request
    * affirm
        - action_request_travel



## Generated Story 99
    * inform_travel
        - utter_ask_time
    * inform_travel{"bookDate": "11-1"}
        - slot{"bookDate": ["19-1"]}
        - utter_ask_city
    * inform_travel{"city": "Gaborone"}
        - slot{"city": ["Bujumbura", "Gaborone"]}
        - utter_ask_meal
    * inform_travel{"meal" : "Seafood please"}
        - slot{"meal": ["Seafood please"]}
        - utter_affirm_request
    * affirm
        - action_request_travel
    * thankyou
        - utter_thankyou



## Generated Story 100
    * greet
          - utter_greet
    * inform_travel
          - utter_ask_city
    * inform_travel{"city": "Singapore"}
          - slot{"city": ["Singapore", "oslo"]}
          - utter_ask_time
    * inform_travel{"bookDate": "11/11/2018"}
          - slot{"bookDate": ["13/11/2018", "1/1/2019"]}
          - utter_ask_meal
    * inform_travel{"meal": "Vegetarian meal"}
          - slot{"meal": ["Vegetarian meal"]}
          - utter_affirm_request
    * affirm
          - action_request_travel
    * thankyou
        - utter_thankyou
