# Full Name
***Pavel Karpeko***

# Сontacts
   ### ***Mail:*** ###
* **syffiks2325@gmail.com**    
* **syffiks1998@gmail.com**    
* **Phone:** *+375293906429*   
* **Skype:** *+375293906429*
* 
# Summary
My goal is to learn js, become a highly skilled developer and find a job in IT.

# Skills: 
* *HTML*  
* *CSS*   
* *C#*    
* *jQuerry*   
* *SQL*   
* *BEM*   
* *Agile*     
* 
# Code example:

        function fu(str){
            let result={};
            let newStr =str.split('').sort();
            for(let item of newStr){
                if(!result[item]){
                    result[item]=1;
                }
                else{
                    result[item]++;
                }
            }
            var lastStr='';
            for (let key in result){
                lastStr = lastStr + (key + result[key]);
            }
            return lastStr;
        }
