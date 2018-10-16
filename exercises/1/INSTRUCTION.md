# Test environment

Url: [http://18.184.154.65:8080](http://18.184.154.65:8080)

Login: aadays

Password: password

# Goal

Find out how many concurrent requests for `Kanban Board` can Jira handle so that median response time is  still below < 1s

# Steps


1. Add > Threads (Users) > Thread Group:

    ![](/exercises/1/images/step_1.png)
    
1. Under the Thread Group Add > Sampler > HTTP Request:

    ![](/exercises/1/images/step_2.png)
    
1. Add > Listener > View Results Tree:

    ![](/exercises/1/images/step_3.png)
    
1. Add > Listener > Aggregate Report:

    ![](/exercises/1/images/step_4.png)
    
1. Configure HTTP Request:

    ![](/exercises/1/images/step_5.png)
    
1. Save your Test Plan (File > Save)

1. Run Test Plan (Run > Start)

1. See if response is OK in View Results Tree

1. Check out how much is median in Aggregate Report

1. If median is below 1s increase threads (users) in Thread Group:

    ![](/exercises/1/images/step_6.png)
    
1. Clear previous results (Run > Clear All)

1. Run > Start. Get back to Step 8 and repeat until you get median above 1s




