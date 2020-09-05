# Leads Conversion - Logistic Regression Model Case
___

In order to help eCommerce organizations respond and identify the most potential leads, known as the 'hot leads', which convert to profitable customers, this regression model analyzes customer actions and uses data to determine which class each unit will fall into - Converted or Not Converted. This data is based from X Education's marketing dataset, which stores information on over 9000 data points and track their actions throughout the sales cycle. The metrics tracked which determine lead potential include: Total Time Spent on Website, Total Visits, Source of Lead, Page Views, and Email & Call Preference. 

By utilizing this logictics regression model, the company and sales team will be able to focus more marketing spend on those 'hot leads' and increase their return on investment ratio.

For more information on the data sources used, see the [Leads Dataset](https://www.kaggle.com/ashydv/leads-dataset). More information on the data dictionary can be found in the data dictionary section below and under the Leads Data Dictionary folder.

## Company Background
This [Leads Dataset](https://www.kaggle.com/ashydv/leads-dataset) is taken from the marketing data of X Education - an online education company that sells courses to industry professionals. X Education provides marketing for their online courses across several websites and search engines. Users who land on the website can browse through the courses, watch videos, or fill out a form with their information, therefore becoming leads. Once a lead is identified, they are then contacted by the sales team via email or phone. However, the company has recognized that only 1/3 of leads are converted into customers, and marketing is distributed evenly across all leads. In order to make the process more efficient, X Education wants a way to identify leads which have the most potential, utilizing the given data. This will be done by creating a logistics regression model to analyze customer actions and determine if they will convert or not convert.

## Description
___
The Marketing Leads case data includes the following content.

| | Description |
| :---: | --- |
| **Sources** | The data source is taken from X Education leads with over 9000 data points. For a full description of the dataset sources see [Leads Dataset](https://www.kaggle.com/ashydv/leads-dataset). |
| **Measures** | Converted or Not Converted. |
| **Coverage and Granularity** | This dataset consists of various attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc. which may or may not be useful in ultimately deciding whether a lead will be converted or not. |
| **Released** | 2020-04-10 |

## Further Information
___
### Support
For additional support please send as a direct message.

### Feedback
Please send feedback as a direct message.

### Other Resources
For other resources within the dataset please see [Leads dataset](https://www.kaggle.com/ashydv/leads-dataset).

## Data Dictionary
___
| Variables                                        | Description                                                                                                                                                                       |
|--------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Prospect ID                                      | A unique ID with which the customer is identified.                                                                                                                                |
| Lead Number                                      | A lead number assigned to each lead procured.                                                                                                                                     |
| Lead Origin                                      | The origin identifier with which the customer was identified to be a lead. Includes API, Landing Page Submission, etc.                                                            |
| Lead Source                                      | The source of the lead. Includes Google, Organic Search, Olark Chat, etc.                                                                                                         |
| Do Not Email                                     | An indicator variable selected by the customer wherein they select whether of not they want to be emailed about the course or not.                                                |
| Do Not Call                                      | An indicator variable selected by the customer wherein they select whether of not they want to be called about the course or not.                                                 |
| Converted                                        | The target variable. Indicates whether a lead has been successfully converted or not.                                                                                             |
| TotalVisits                                      | The total number of visits made by the customer on the website.                                                                                                                   |
| Total Time Spent on Website                      | The total time spent by the customer on the website.                                                                                                                              |
| Page Views Per Visit                             | Average number of pages on the website viewed during the visits.                                                                                                                  |
| Last Activity                                    | Last activity performed by the customer. Includes Email Opened, Olark Chat Conversation, etc.                                                                                     |
| Country                                          | The country of the customer.                                                                                                                                                      |
| Specialization                                   | The industry domain in which the customer worked before. Includes the level 'Select Specialization' which means the customer had not selected this option while filling the form. |
| How did you hear about X Education               | The source from which the customer heard about X Education.                                                                                                                       |
| What is your current occupation                  | Indicates whether the customer is a student, umemployed or employed.                                                                                                              |
| What matters most to you in choosing this course | An option selected by the customer indicating what is their main motto behind doing this course.                                                                                  |
| Search                                           | Indicating whether the customer had seen the ad in any of the listed items.                                                                                                       |
| Magazine                                         | Indicating whether the customer had seen the ad in any of the listed items.                                                                                                                                                                                  |
| Newspaper Article                                | Indicating whether the customer had seen the ad in any of the listed items.                                                                                                                                                                                  |
| X Education Forums                               | Indicating whether the customer had seen the ad in any of the listed items.                                                                                                                                                                                  |
| Newspaper                                        | Indicating whether the customer had seen the ad in any of the listed items.                                                                                                                                                                                  |
| Digital Advertisement                            | Indicating whether the customer had seen the ad in any of the listed items.                                                                                                                                                                                  |
| Through Recommendations                          | Indicates whether the customer came in through recommendations.                                                                                                                   |
| Receive More Updates About Our Courses           | Indicates whether the customer chose to receive more updates about the courses.                                                                                                   |
| Tags                                             | Tags assigned to customers indicating the current status of the lead.                                                                                                             |
| Lead Quality                                     | Indicates the quality of lead based on the data and intuition the the employee who has been assigned to the lead.                                                                 |
| Update me on Supply Chain Content                | Indicates whether the customer wants updates on the Supply Chain Content.                                                                                                         |
| Get updates on DM Content                        | Indicates whether the customer wants updates on the DM Content.                                                                                                                   |
| Lead Profile                                     | A lead level assigned to each customer based on their profile.                                                                                                                    |
| City                                             | The city of the customer.                                                                                                                                                         |
| Asymmetrique Activity Index                      | An index and score assigned to each customer based on their activity and their profile.                                                                                            |
| Asymmetrique Profile Index                       | An index and score assigned to each customer based on their activity and their profile.                                                                                                                                                                                  |
| Asymmetrique Activity Score                      | An index and score assigned to each customer based on their activity and their profile.                                                                                                                                                                                  |
| Asymmetrique Profile Score                       | An index and score assigned to each customer based on their activity and their profile.                                                                                                                                                                                  |
| I agree to pay the amount through cheque         | Indicates whether the customer has agreed to pay the amount through cheque or not.                                                                                                |
| a free copy of Mastering The Interview           | Indicates whether the customer wants a free copy of 'Mastering the Interview' or not.                                                                                             |
| Last Notable Activity                            | The last notable acitivity performed by the student.                                                                                                                              |
