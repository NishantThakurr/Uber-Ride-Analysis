
# Business Case Study on Cancellation and no cars availabilty in Uber

Business Problem Statement-
Uber is a transportation company with an app that allows passengers to hail a ride and drivers to charge fares and get paid. More specifically, Uber is a ridesharing company that hires independent contractors as drivers.
During recent times,the users of these app were giving a constant negative feedback that there rides were getting cancelled and in many cases they also faced cars not available issue.
So in this case, we are trying to find if this is really happening.
If yes, we will try to find the exact reason behind these and also try to find some measures that can be taken to tackle this Problem.






## 🚀 About Me
Hey,I am Nishant Thakur.I am a data analyst and solving business problems through data is what I love to do.


## Project Process Flow.

#### 1)Understanding the actual problem that the business is facing.

Uber is a transportation company with an app that allows passengers to hail a ride and drivers to charge fares and get paid. More specifically, Uber is a ridesharing company that hires independent contractors as drivers.
During recent times,the users of these app were giving a constant negative feedback that there rides were getting cancelled and in many cases they also faced cars not available issue.

#### 2) Getting the data.
The data was downloaded from kaggle in the form of a csv.You can download it from 
https://www.kaggle.com/datasets/abhi231092/uber-rides-data-bw-city-and-airport

![image](https://user-images.githubusercontent.com/102639991/218497944-4754de75-c634-43a8-8aa7-cd3653c52b44.png)

#### 3)Basic data exploration,data cleaning and Feature Engineering.
![image](https://user-images.githubusercontent.com/102639991/218498385-c79aefe1-efb2-460a-acc6-28e3aaa0b97e.png)
![image](https://user-images.githubusercontent.com/102639991/218498541-03fd57a7-2612-4423-98c7-d4b45d236527.png)
![image](https://user-images.githubusercontent.com/102639991/218499771-8b250cfa-9943-4d7e-9964-fc5309704516.png)

#### 4) Understanding if this problem is really happening and the amplitude of it.

![image](https://user-images.githubusercontent.com/102639991/218497580-a42eadbc-4826-4ce9-b9d4-9f9d82329c65.png)

Yes,As we can see from the data this was really a serious problem with Uber rides.

### 5) Univariate analysis and finding insights from them

![image](https://user-images.githubusercontent.com/102639991/218499405-98cbc511-2359-4e75-99f7-37494d0dc90f.png)

![image](https://user-images.githubusercontent.com/102639991/218500126-8fda493f-3ef0-4512-8b94-1d680aa2a48a.png)


### 6) Bivariate analysis and finding insights from them.
![image](https://user-images.githubusercontent.com/102639991/218500478-08ef0e55-62e8-4fb1-93d2-c1d14320cb67.png)

### 7) Finding out the actual reasons for the problem and explaining that through some graphs.

![image](https://user-images.githubusercontent.com/102639991/218500971-9a40e91b-cc8f-467e-a4aa-d57d9b4dd03d.png)
![image](https://user-images.githubusercontent.com/102639991/218501069-f6c42615-080d-4681-b61a-3653a4bc2187.png)

#### 8) Finding out the steps that can be taken to solve the particular business problem.
## Tech Used
Python,Pandas,Matplotlib,Seaborn

## Insights.

#### 1)Only 42.0% trips are completed which in itself is a poor number.39.3% cases had 'no cars available'.18.7% Requests were cancelled

#### 2)No driver is cancelling his requests in a huge number.The median cancellation rate is 0.3 that is most drivers tend to cancel 3 rides out of 10 that were requested.Drivers with more Requests tend to have more cancellation rate.This must be because overload of requests

#### 3)There is a huge amount of Request cases in Wednesday.The amount of no cars available is even more than Trip completed during Thursday and Friday which are more close to the weekends.July has an incredible rush of ride requests!

#### 4)In case of City,Completed trip percentage is highest during evening and lowest at Early morning.Also,during Early mornings a significant amount of these requests are not completed due to cancellations by the driver. In case of airport,this is quite the opposite.Completed trip percentage is highest during early mornings(even higher than City during evenings) but this number is very poor at evening time(even lower than City during mornings).Also,during early mornings a significant amount of these requests are not completed due to non-availabilty due to cars. Now this is a pure supply and demand issue as demand is highest during Early morning in case of City.That's why many requests are left incompleted. Visa versa,Demand is highest during evening time in case of Airports.That's why there is a huge non-availabilty issue during these time.Let's try to understand it better with help of some graphs.


## Final Verdict and recommendation
#### What the business is facing is a clear 'Demand and Supply issue'
#### In case of Pickup point City,Completed trip percentage is highest during evening(5pm-9pm) and lowest at Early morning(5am-9am).Also,during Early mornings a significant amount of these requests are not completed due to cancellations by the driver.Now Since the trips that were completed were similar in evening and early morning and Total requests are way more during early morning, it means that the supply of cars/drivers is very low as compared to it's demand during early mornings.Uber should hire more drivers for this particular time in City during early morning time.
#### Visa versa,Demand is highest during evening time in case of Airports.That's why there is a huge non-availabilty issue during these time.

![image](https://user-images.githubusercontent.com/102639991/218505858-49927d77-d215-4c7c-8878-a9a872e4dea2.png)
![image](https://user-images.githubusercontent.com/102639991/218505975-8da28742-1e25-4120-a345-ae8d35d7adab.png)



