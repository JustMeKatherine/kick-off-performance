# Test environment

Url: http://18.184.154.65:8080

Login: aadays
Password: password


# Goal

Measure median response time for 10 concurrent users

# Steps

1. Make sure you have `Blazemeter Plugin` installed in your browser

1. Open `Kanban board`

1. Open `Blazemeter Plugin`. Make sure you are logged in. Sign up if you don't have account yet.

    ![](/exercises/3/images/step_1.png)
    
1. Start recording:

    ![](/exercises/3/images/step_2.png)
    
1. Refresh page with `Kanban board`
    
1. Stop recording:

    ![](/exercises/3/images/step_3.png)
    
1. Download recording:

    ![](/exercises/3/images/step_3.png)
    
1. Choose `JMeter (JMX)` and our test Jira domain:
    
    ![](/exercises/3/images/step_4.png)  

    
1. Open saved file in JMeter:
    
    ![](/exercises/3/images/step_5.png)
    
    
1. Move `Test` to `Ultimate Thread Group`

1. Disable `Thread Group` 

1. Open `Ultimate Thread Group` and add row with load setup

1. Change `Start Threads Count` to 10

1. Run > Clear All. Run > Start.

1. Check out how much is median in Aggregate Report

1. Check how many of request ended up with errors in `Aggregate Report` in column `Error %`. Do you know what pitfall you've just felt into? See details of responses in `View Results Tree`



