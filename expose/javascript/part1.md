Part 1: 
1. 20
2. 20
3. 20
4. Error, result is not defined since it is out of scope
5. Error, variable with constant can't be reassigned
6. Error, result is not defined since it is out of scope

Part 2:
1. 3, Since 'i' is a var variable, it can be accessed anywhere inside the function it is defined in. The final value for 'i' is 3 because prices array has a length of 3. 
2. 150, Since 'discountedPrice' is a var variable, it can be accessed anywhere inside the function it is defined in. The final value for 'discountedPrice' is 150 because in the last round of the for loop, discountedPrice has been assigned to 300 * (1 - 0.5) which is equal to 150
3. 150, Since 'finalPrice' is a var variable, it can be accessed anywhere inside the function it is defined in. The final value for 'finalPrice' is 150 because in the last round of the for loop, finalPrice has been assigned to Math.round(150 * 100) / 100 which is equal to 150. 
4. [50, 100, 150], Since 'discounted' is a var variable, it can be accessed anywhere inside the function it is defined in. The original prices before discount are [100, 200, 300], and after going through the function and applying the 50% of discount, we will get the result [50, 100, 150]. 
5. Error, 'i' is not defined since it is out of scope. 'i' is a let variable and has been defined in the for loop so it cant be accessed outside of that
6. Error, 'discountedPrice' is not defined since it is out of scope. 'discountedPrice' is a let variable and has been defined in the for loop so it cant be accessed outside of that
7. 150, 'finalPrice' is been defined inside the discountPrices function, so it can be accessed within the scope. 'finalPrice' is equal to 150 because the last value been assigned to it is Math.round(150 * 100) / 100 which is 150. 
8. [50, 100, 150], Since 'discounted' is been defined inside the discountPrices function, so it can be accessed within the scope. The original prices before discount are [100, 200, 300], and after going through the function and applying the 50% of discount, we will get the result [50, 100, 150]. 
9. Error, 'i' is not defined since it is out of scope. 'i' is a let variable and has been defined in the for loop so it cant be accessed outside of that
10. 3, 'length' is a const variable been assigned inside the function, it can be accessed anywhere inside the function. In addition, the value hasn't be reassigned so it wont cause any error. 
11. [50, 100, 150], Since 'discounted' is been defined inside the discountPrices function, so it can be accessed within the scope. The original prices before discount are [100, 200, 300], and after going through the function and applying the 50% of discount, we will get the result [50, 100, 150]. 