# TP-IOT

# Configuration 

I created a node application with **Typescript** and **Javascript** framework **Express.JS**. 

This app collects humidity and temperature data generated by sensors, thanks to node app in folder **tp-iot-main**.

 1) Open a terminal and install dependencies into the **root folder** and **tp-iot-main** folder :

```
npm i

```

2) Then, create a new **.env** file based on **.env.sample.txt** and modify what you need 

3) My node app runs with a Typescript compiler who transform Typescript in Javascript(ts-node), so you have to start a terminal and write :

```
ts-node index.ts

```
# Final Results 

You have in **graphs pictures** some screens in **Grafana**, and **InfluxDB Data Explorer**.

In **Grafana** I add some threshold, it's a value that you specify for a visually crossing in your dashboard. 

For **Temperature**, threshold orange color is for 28°C and red for 30°C.
![temperature](https://user-images.githubusercontent.com/74965427/211004702-419dfb2c-84ef-4f6a-978a-49102341565c.png)

For **Humidity**, threshold orange is for 80% and red for 90%.
![humidity](https://user-images.githubusercontent.com/74965427/211004703-1e0502a8-88fa-46d7-9e31-e81eb865a44b.png)
