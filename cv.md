# **Isabek Uezbaev**
***
## **My contacts**
---
* **My phone:** +996 552 852 852
* **My e-mail:** uezbaev852@gmail.com
* **My GitHub:** [uezbaev852](https://github.com/uezbaev852)
* **My Discord:** kobayashi#0676
## **About me**
---
I am a 22 year old student of the 3rd year of the KRSU. Doing my best to find my place in this horrible world
## **My skills**
---
* HTML/CSS (beginner)
* C/C++ (basic skills)
* C# (could be better)
* Java (basic skills)
* T-SQL (basic querry writting skills)
## **My code example**
---
```
static List<FitnessRecord> GenerateFitnessRecords()
        {
            Random random = new Random();

            var records = new List<FitnessRecord>();

            for (int year = 2020; year <= 2022; year++)
            {
                for (int month = 1; month <= 12; month++)
                {
                    for (int clientCode = 1; clientCode <= 6; clientCode++)
                    {
                        int duration = random.Next(3,17); 
                        records.Add(new FitnessRecord { Duration = duration, ClientCode = clientCode, Month = month, Year = year });
                    }
                }
            }

            return records;
        }
```
## **Education**
---
* Kyrgyz-Russian Slavic University
* C# + T-SQL Courses
## **English**
---
B1 - Intermediate 
