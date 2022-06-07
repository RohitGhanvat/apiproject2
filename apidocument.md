//page 1
>list of city
>>(Get) http://localhost:8100/location
>>>Live url=https://mainapiedu.herokuapp.com/location

>list of shop
>>(Get) http://localhost:8100/shop
>>>Live url=https://mainapiedu.herokuapp.com/shop

>shop on the  basis of  city
>>(Get) http://localhost:8100/shop?stateId=1
>>>Live url= https://mainapiedu.herokuapp.com/shop?stateId=1

list of special
>>(Get) http://localhost:8100/special
>>>Live url=https://mainapiedu.herokuapp.com/special


//page 2
>list of shop on basis of meal
>>(Get) http://localhost:8100/shop?mealId=1
>>>Live url=https://mainapiedu.herokuapp.com/shop?mealId=1

>filter on basis of cuisine
>>(Get) http://localhost:8100/filter/1?cuisineId=2
>>>Live url=https://mainapiedu.herokuapp.com/filter/1?cuisineId=2

>filter on basis of cost 
>>(Get) http://localhost:8100/filter/1?lcost=450&hcost=1200
>>>Live url=https://mainapiedu.herokuapp.com/filter/1?lcost=450&hcost=1200

> sort on basis of cost
>>(Get) http://localhost:8100/filter/1?lcost=150&hcost=1200&sort=1
>>>Live url=https://mainapiedu.herokuapp.com/filter/1?lcost=150&hcost=1200&sort=1


//page 3
>details of the shop
>>(Get) http://localhost:8100/details/14
>>>Live url=https://mainapiedu.herokuapp.com/details/14

>Menu of the shop
>>(Get) http://localhost:8100/menu/9
>>>Live url=https://mainapiedu.herokuapp.com/menu/9


//page 4
>Menu details (selected item )
>>(Post)  http://localhost:8100/menuItem
[1,3,6]
>>>Live url= https://mainapiedu.herokuapp.com/menuItem

>place order 
>>(Post) http://localhost:8100/placeOrder
>>>Live url= https://mainapiedu.herokuapp.com/placeOrder

{
    "name":"rohit",
    "email":"rohit@gmail.com",
    "address":"home34",
    "phone":6789987989,
    "cost":450,
    "menuItem":[3,7,1]
}


//page 5
>list of order placed
>>(Get) http://localhost:8100/order
>>>Live url=https://mainapiedu.herokuapp.com/order

>list of order placed of particular user
>>(Get) http://localhost:8100/order?email=
>>>Live url=https://mainapiedu.herokuapp.com/order?email=rohit@gmail.com

>update order status
>>(Put) localhost:8100/updateOrder/1
>>>Live url=https://mainapiedu.herokuapp.com/updateOrder/1


//extra
>delete order
>>(Delete) localhost:8100/deleteOrder
>>>Live url=https://mainapiedu.herokuapp.com/deleteOrder