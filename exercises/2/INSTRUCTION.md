# Test environment

Url: http://18.184.154.65:8080

Login: aadays
Password: password


# Goal

Measure median response time for 10 concurrent users

# Steps

1. Start with JMeter script from previous exercise


1. Add > Listener > jp@gc - Active Threads Over Time:

    ![](/exercises/2/images/step_1.png)
    
1. Add > Threads (Users) > jp@gc - Ultimate Thread Group:

    ![](/exercises/2/images/step_2.png)
    
1. Duplicate `HTTP Request`:

    ![](/exercises/2/images/step_3.png)
    
1. Drag & drop `HTTP Request` to `Ultimate Thread Group`:

    ![](/exercises/2/images/step_4.png)
    
1. Disable `Thread Group` that was used previously:

    ![](/exercises/2/images/step_5.png)
    
1. Open `Ultimate Thread Group` and add row with load setup:

    ![](/exercises/2/images/step_6.png)

1. Change `Start Threads Count` to 10:

    ![](/exercises/2/images/step_7.png)

1. Run > Clear All. Run > Start.

1. Check out how much is median in Aggregate Report



