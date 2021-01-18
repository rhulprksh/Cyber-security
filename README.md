# Cyber-security
A cyber security product protects web and mobile applications from runtime attacks. The way hackers attack keeps on changing constantly and thats where Machine Learning comes into the picture. A machine learning model is developed which can identify if the request is safe or not.

Here is the sample data: https://jsonblob.com/f0b70eef-566b-11eb-9d92-415b3ac53928

(But I just copied the data from this link and saved it as data.json)

This data contains the request payload and a field "isSafe" which basically tells if the request is safe or not for the app. Using some prelim method fields each request have been  as not safe if any of the fields contain malicious input from the user in to perform owasp top 10 attacks. Therefore, If value of isSafe is False, it means the request should be blocked. 

Based on the problem statement a machine learning model is developed to categorize the application requests as safe or not.
