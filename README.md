# Proxy-Check
Makes a list of proxies that are working and up at the time of check.                        
                         
                      
Pull proxies from website list                   
-Website list                         
--A list of websites that list proxies                    
--This list will only contain websites that update there proxies                    
                       
First check to see if there is already a good proxies document on the system                       
-If there is already a good proxies document then add all the proxies in that document to the check proxies list and delete the good proxies document                                           
                        
Second make a document that contains a list of proxies that were pulled from the websites                        
-Before adding a new proxy to the list check to make sure that it is not already in the list                        
-Have an option that allows the user to change the number of proxies to pull from the websites                        
                        
Next make a second list that contains a list of proxies that are up and running                            
-This list is made by looping through the proxies in the first list and checking each proxy                                 
-If the proxy passes the checks then it will be added to the good proxies list                           
                        
