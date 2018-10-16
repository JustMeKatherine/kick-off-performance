# Test environment

Url: http://18.184.154.65:8080

Login: aadays
Password: password


# Goal

What is median response time for 10 concurrent different users using 10 different boards

# Steps

1. Open `start.jmx` file from this directory in JMeter:
    
    ![](/exercises/4/images/step_1.png)
    
1.   Add > Config Element > CSV Data Set Config twice:
        
     ![](/exercises/4/images/step_2.png)   

1. Browse for users.csv file under this exercise directory. Add `username` variable. Set `Ignore first line` to true:

     ![](/exercises/4/images/step_3.png) 
     
1. Similar with boards.csv:

     ![](/exercises/4/images/step_4.png) 
     
1. Start using the variables in HTTP Requests. Examples:

    ![](/exercises/4/images/step_5a.png) 
    
    ![](/exercises/4/images/step_5b.png) 
    
1. Run > Clear All. Run > Start.

1. Check inside `Aggregate Report` if there are no errors

1. Check out value of median in `Aggregate Report`
