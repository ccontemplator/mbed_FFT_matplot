#self note 

read the button if b1 is on then multiply cs by 2, 
read the button if b2 is on then divide cs by 2
    
when pressing b3 then stop selecting cs and start to generate wave，slope area is 80ms*cs ,flat area is 240-80ms*cs*2(using a for loop to generate) 

sampling at specific rates using sleep_for,printf to ttyACM0 interface and use python to fetch data from ttyACM0 interface ,then we can plot the graph 
