---
title: Adobe Certification Restart Program
description: You have technical knowledge about audience segmentation, destination exports, and activation on real time basis for unified profiles that adhere to data and privacy regulations, customer data platforms (CDP) and knowledge of Adobe Experience Platform.
role: Developer
recommendations: disable, exclude
badge: label="Restart program" type="positive"
---
# Certification journey - Adobe Certification Restart program

## Restart your certification journey by going from expired to certified

![Certification Expert Badge](/help/certifications/assets/expert-badge-Xsmall.png) ![Certification Master Badge](/help/certifications/assets/master-badge-Xsmall.png)

**What is Adobe Restart program?**

The Adobe Restart Program is an initiative that allows individuals who previously held Adobe Digital Cloud Experience certifications that have since expired to earn a new certification for free. The program offers eligible participants the opportunity to update their skills and stay current in their field by completing designated learning activities or an unproctored job role exam, depending on the solution. This program is a valuable resource for individuals seeking to enhance their digital expertise and stay competitive in today's rapidly changing digital environment.

**How does it work?**

* Review the requirements to see if you are eligible
* Complete the requirements before the deadline
* Act now to take advantage of this opportunity to earn a new certification for free.

>[!NOTE]
>
>**This program is offered from April 4th, 2023 through October 1st, 2023.** 

<!DOCTYPE html>
<html><head>
<meta http-equiv="content-type" content="text/html; charset=windows-1252">
    <title>Exam Eligibility Check</title>
    <style>
        table, th, td {
            border: 1px solid black;
            border-collapse: collapse;
            padding: 5px;
        }
        th {
            background-color: #ccc;
        }
    </style>
</head>
<body>
    <h1>Certification Restart Eligibility Exam Checker</h1>
    <p>To check if an exam is eligible for the restart program, input the exam number (e.g., AD0-E100) and select "Check Eligibility.".</p>
    <form>
        <label for="exam-id"></label>
        <input type="text" id="exam-id" name="exam-id" required="">
        <input type="submit" value="Check Eligibility">
    </form>
    <br>
    <div id="result">We're sorry, but the exam number you have entered 
could not be located or does not meet the eligibility criteria for the 
restart program. Try again with a different exam number or email <a href="mailto:certif@adobe.com?subject=Adobe Certification Restart Eligibility">certif@adobe.com</a> for further assistance.</div>
    <script>
        // Exam ID parameters
        var exams = [
            { certification: "Adobe Certified Expert - Adobe Experience Manager Sites Business Practitioner", name: "Adobe Experience Manager Sites Business Practitioner Expert", id: "AD0-E121", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },
            { certification: "Adobe Certified Expert - Adobe Experience Manager Sites Business Practitioner", name: "Adobe Experience Manager Sites Business Practitioner", id: "AD0-E102", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },
            { certification: "Adobe Certified Expert - Adobe Experience Manager Sites Developer", name: "Adobe Experience Manager Sites Developer", id: "AD0-E103", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },
            { certification: "Adobe Certified Expert - Adobe Experience Manager Sites Developer", name: "Adobe Experience Manager Sites Developer", id: "AD0-E116", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },
            { certification: "Adobe Certified Master - Adobe Experience Manager Sites Architect", name: "Adobe Experience Manager Sites Architect", id: "AD0-E117", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },            
            { certification: "Adobe Certified Master - Adobe Experience Manager Sites Architect", name: "Adobe Experience Manager Sites Architect", id: "AD0-E104", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },
            { certification: "Adobe Certified Expert - Adobe Analytics Business Practitioner", name: "Adobe Analytics Business Practitioner", id: "AD0-E202", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },
            { certification: "Adobe Certified Expert - Adobe Analytics Developer", name: "Adobe Analytics Developer", id: "AD0-E201", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },
            { certification: "Adobe Certified Master - Adobe Analytics Architect", name: "Adobe Analytics Architect", id: "AD0-E207", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },
            { certification: "Adobe Certified Master - Adobe Analytics Architect", name: "Adobe Analytics Architect", id: "AD0-E200", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },
            { certification: "Adobe Certified Master - Adobe Audience Manager Architectt", name: "Adobe Audience Manager Architect", id: "AD0-E454", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },
            { certification: "Adobe Certified Master - Adobe Audience Manager Architect", name: "Adobe Audience Manager Architect", id: "AD0-E452", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },
            { certification: "Adobe Certified Expert - Adobe Audience Manager Business Practitioner", name: "Adobe Audience Manager Business Practitioner", id: "AD0-E453", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },
            { certification: "Adobe Certified Expert - Adobe Campaign Classic Business Practitioner", name: "Adobe Campaign Classic Business Practitioner", id: "AD0-E300", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },
            { certification: "Adobe Certified Expert - Adobe Campaign Classic Business Practitioner", name: "Adobe Campaign Classic Business Practitioner", id: "AD0-E114", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },            
            { certification: "Adobe Certified Master - Adobe Campaign Classic Architect", name: "Adobe Campaign Classic Architect", id: "AD0-E118", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },
            { certification: "Adobe Certified Master - Adobe Campaign Classic Architect", name: "Adobe Campaign Classic Architect", id: "AD0-E303", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },
            { certification: "Adobe Certified Expert - Adobe Campaign Classic Developer", name: "Adobe Campaign Classic Developer", id: "AD0-E312", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },
            { certification: "Adobe Certified Expert - Adobe Campaign Classic Developer", name: "Adobe Campaign Classic Developer", id: "AD0-E308", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },
            { certification: "Adobe Certified Expert - Adobe Campaign Standard Business Practitioner", name: "Adobe Campaign Standard Business Practitioner", id: "AD0-E307", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },
            { certification: "Adobe Certified Expert - Adobe Campaign Standard Business Practitioner", name: "Adobe Campaign Standard Business Practitioner", id: "AD0-E302", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },            
            { certification: "Adobe Certified Expert - Adobe Campaign Standard Developer", name: "Adobe Campaign Standard Developer", id: "AD0-E306", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },
            { certification: "Adobe Certified Expert - Adobe Campaign Standard Developer", name: "Adobe Campaign Standard Developer", id: "AD0-E301", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },
            { certification: "Adobe Certified Expert - Adobe Marketo Engage Business Practitione", name: "Adobe Marketo Engage Business Practitioner", id: "AD0-E552", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },
            { certification: "Adobe Certified Expert - Adobe Marketo Engage Business Practitione", name: "Adobe Marketo Engage Business Practitioner", id: "AD0-E401", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },
            { certification: "Adobe Certified Master - Adobe Target Architect", name: "Adobe Target Architect", id: "AD0-E402", url: "https://experienceleague.corp.adobe.com/docs/certification/certification/restart-program.html?lang=en" },
        ];
​
        // Get form and result elements
        var form = document.querySelector("form");
        var result = document.getElementById("result");
​
        // Add event listener to form submit
        form.addEventListener("submit", function(event) {
            event.preventDefault();
            var input = document.getElementById("exam-id").value.trim().toUpperCase();
            var exam = exams.find(e => e.id === input);
            if (exam) {
                // Exam ID found
                result.innerHTML = `
                    <table>
                        <tr><th>Certification Name</th><th>Exam Name</th><th>Exam ID</th><th>Eligibility</th><th>More Information</th></tr>
                        <tr><td>${exam.certification}</td><td>${exam.id}</td><td>${exam.name}</td><td>Yes</td><td><a href="${exam.url}" target="_blank">View details</a></td></tr>
                    </table>
                `;
            } else {
                // Exam ID not found
                result.innerHTML = "We're sorry, but the exam number you have entered could not be located or does not meet the eligibility criteria for the restart program. Try again with a different exam number or email <a href='mailto:certif@adobe.com?subject=Adobe Certification Restart Eligibility'>certif@adobe.com</a> for further assistance.";
            }
            form.reset();
        });
    </script>
​
​
​
​
​
​
</body></html>

## Exams eligible to re-certify 

>[!BEGINTABS]

>[!TAB Experience Manager]

<table>
 <tbody>
  <tr>
   <th>Certification</th>
   <th>Elegible exam</th>
  </tr>
  <tr>
   <td><p>Adobe Certified Expert - Adobe Experience Manager Business Practitioner</td>
   <td><p><ul><li>AD0-E121 Adobe Experience Manager Sites Business Practitioner Expert</li></ul><ul><li>AD0-E102 Adobe Experience Manager Sites Business Practitioner Expert (retired)</li></ul></p></td>
  </tr>
  <tr>
   <td><p>Adobe Certified Expert - Adobe Experience Manager Developer</td>
   <td><p><ul><li>AD0-E134 Adobe Experience Manager Sites Developer Expert</li></ul><ul><li>AD0-E103 Adobe Experience Manager Sites Developer Expert (retired)</li></ul><ul><li>AD0-E116 Adobe Experience Manager Sites Developer Expert</li></ul></p></td>
  </tr>
  <tr>
   <td><p>Adobe Certified Expert - Adobe Experience Manager Dev/Ops Engineer</td>
   <td><p><ul><li>AD0-E124 Adobe Experience Manager DevOps Engineer Expert</li></ul><ul><li>AD0-E106 Adobe Experience Manager Dev/Ops Engineer Expert (retired)</li></ul></p></td>
  </tr>
  <tr>
  <tr>
   <td><p>Adobe Certified Master - Adobe Experience Manager Sites Architect</td>
   <td><p><ul><li>AD0-E117 Adobe Experience Manager Sites Architect Mastert</li></ul><ul><li>AD0-E104 Adobe Experience Manager Sites Architect Master (retired)</li></ul> </p></td>
  </tr>
 </tbody>
</table>

>[!TAB Analytics]

<table>
 <tbody>
  <tr>
   <th>Certification</th>
   <th>Elegible exam</th>
  </tr>
  <tr>
   <td><p>Adobe Certified Expert - Adobe Analytics Business Practitioner</td>
   <td><p><ul><li>AD0-E208 Adobe Analytics Business Practitioner Expert</li></ul><ul><li>AD0-E202 Adobe Analytics Business Practitioner Expert (retired)</li></ul></p></td>
  </tr>
  <tr>
   <td><p>Adobe Certified Expert - Adobe Analytics Developer</td>
   <td><p><ul><li>AD0-E209 Adobe Analytics Developer Expert</li></ul><ul><li>AD0-E201 Adobe Analytics Developer Expert (retired)</li></ul></p></td>
  </tr>
  <tr>
   <td><p>Adobe Certified Master - Adobe Analytics Architect</td>
   <td><p><ul><li>AD0-E207 Adobe Analytics Architect Master</li></ul><ul><li>AD0-E200 Adobe Analytics Architect Master (retired)</li></ul></p></td>
  </tr>
  <tr>
</tbody>
</table>

>[!TAB Audience Manager]

<table>
 <tbody>
  <tr>
   <th>Certification</th>
   <th>Elegible exam</th>
  </tr>
  <tr>
   <td><p>Adobe Certified Expert - Adobe Audience Manager Business Practitioner</td>
   <td><p><ul><li>AD0-E457 Adobe Audience Manager Business Practitioner Expert</li></ul><ul><li>AD0-E453 Adobe Audience Manager Business Practitioner Expert - (retired)</li></ul></p></td>
  </tr>
  <tr>
   <td><p>Adobe Certified Master - Adobe Audience Manager Architect</td>
   <td><p><ul><li>AD0-E454 Adobe Audience Manager Architect Master</li></ul><ul><li>AD0-E452 Adobe Audience Manager Architect Master (retired)</li></ul></p></td>
  </tr>
  <tr>
   <td><p>Adobe Certified Master - Adobe Analytics Architect</td>
   <td><p><ul><li>AD0-E207 Adobe Analytics Architect Master</li></ul><ul><li>AD0-E200 Adobe Analytics Architect Master (retired)</li></ul></p></td>
  </tr>
  <tr>
  </tbody>
</table>

>[!TAB Campaign]

<table>
 <tbody>
  <tr>
   <th>Certification</th>
   <th>Elegible exam</th>
  </tr>
  <tr>
   <td><p>Adobe Certified Expert - Adobe Campaign Classic Business Practitioner</td>
   <td><p><ul><li>AD0-E327 Adobe Campaign Classic Business Practitioner Expert</li></ul><ul><li>AD0-E300 Adobe Campaign Classic Business Practitioner Expert (retired)</li></ul><ul><li>AD0-E314 Adobe Campaign Classic Business Practitioner Expert (retired)</li></ul></p></td>
  </tr>
  <tr>
   <td><p>Adobe Certified Master - Adobe Campaign Classic Architect</td>
   <td><p><ul><li>AD0-E328 Adobe Campaign Classic Architect Master</li></ul><ul><li>AD0-E318 Adobe Campaign Classic Architect Master (retired)</li></ul><ul><li>AD0-E303 Adobe Campaign Classic Architect Master (retired)</li></ul></p></td>
  </tr>
  <tr>
   <td><p>Adobe Certified Expert - Adobe Campaign Classic Developer</td>
   <td><p><ul><li>AD0-E330 Adobe Campaign Classic Developer Expert</li></ul><ul><li>AD0-E312 Adobe Campaign Classic Developer Expert (retired)</li></ul><ul><li>AD0-E308 Adobe Campaign Classic Developer Expert (retired)</li></ul></p></td>
  </tr>
  <tr>
  <td><p>Adobe Certified Expert - Adobe Campaign Standard Business Practitioner</td>
   <td><p><ul><li>AD0-E307 Adobe Campaign Standard Business Practitioner Expert</li></ul><ul><li>AD0-E302 Adobe Campaign Standard Business Practitioner Expert (retired)</li></ul></p></td>
  </tr>
  <tr>
  </tr>
  <tr>
  <td><p>Adobe Certified Expert - Adobe Campaign Standard Developer</td>
   <td><p><ul><li>AD0-E306 Adobe Campaign Standard Developer Expert</li></ul><ul><li>AD0-E301 Adobe Campaign Standard Developer Expert (retired)</li></ul></p></td>
  </tr>
  <tr>
  </tbody>
</table>

>[!TAB Commerce]

<table>
 <tbody>
  <tr>
   <th>Certification</th>
   <th>Elegible exam</th>
  </tr>
  <tr>
   <td><p>Adobe Certified Expert - Adobe Commerce Business Practitioner</td>
   <td><p><ul><li>AD0-E708 Adobe Commerce Business Practitioner Expert</li></ul><ul><li>AD0-E700 Adobe Commerce Business Practitioner Expert</li></ul></p></td>
  </tr>
  <tr>
   <td><p>Adobe Certified Expert - Adobe Commerce Developer</td>
   <td><p><ul><li>AD0-E716 Adobe Commerce Developer Expert</li></ul><ul><li>AD0-E709 Adobe Commerce Developer Expert (retired)</li></ul></p></td>
  </tr>
  <tr>
   <td><p>Adobe Certified Expert - Adobe Commerce Front End Developer</td>
   <td><p><ul><li>AD0-E710 Adobe Commerce Front End Developer Expert</li></ul><ul><li>AD0-E701 Adobe Commerce Front End Developer Expert (retired)</li></ul></p></td>
  </tr>
  <tr>
  <td><p>Adobe Certified Master - Adobe Commerce Architect</td>
   <td><p><ul><li>AD0-E718 Adobe Commerce Architect Master</li></ul><ul><li>AD0-E704 Adobe Commerce Architect Master (retired)</li></ul></p></td>
  </tr>
  <tr>
  </tbody>
</table>

>[!TAB Marketo Engage]

<table>
 <tbody>
  <tr>
   <th>Certification</th>
   <th>Elegible exam</th>
  </tr>
  <tr>
   <td><p>Adobe Certified Expert – Adobe Marketo Engage Business Practitioner</td>
   <td><p><ul><li>AD0-E559 Adobe Marketo Engage Business Practitioner Expert</li></ul><ul><li>AD0-E552 Adobe Marketo Engage Business Practitioner (previously MCE)</li></ul><ul><li>AD0-E554 Adobe Marketo Engage Business Practitioner (new version)</li></ul><ul><li>AD0-E558 Adobe Marketo Engage Business Practitioner Expert (retired)</li></ul></p></td>
  </tr>
  <tr>
  </tbody>
</table>

>[!TAB Target]

<table>
 <tbody>
  <tr>
   <th>Certification</th>
   <th>Elegible exam</th>
  </tr>
  <tr>
   <td><p>Adobe Certified Expert - Adobe Target Business Practitioner</td>
   <td><p><ul><li>AD0-E406 Adobe Target Business Practitioner Expert</li></ul><ul><li>AD0-E401 Adobe Target Business Practitioner Expert (retired)</li></ul></p></td>
  </tr>
  <tr>
   <td><p>Adobe Certified Master - Adobe Target Architect</td>
   <td><p><ul><li>AD0-E407 Adobe Target Architect Master</li></ul><ul><li>AD0-E402 Adobe Target Architect Master (retired)</li></ul></p></td>
  </tr>
  <tr>
  </tbody>
</table>

>[!ENDTABS]

## Get ready

To restart your expired certification, we offer either continuous learning activities or an on-demand online exam based on solution/application area, both modalities are offered free of cost and non-proctored.

**Steps for continuous learning activities** 

* A set of short assessments based on the Adobe Experience League content 
* Submit a customer reference to validate active engagement 
* Complete minimum required activities for reattaining certification

**Steps for on-demand exam** 
 
* The exam is available free of cost online with no proctor 

>[!NOTE]
>
>A single Campaign Classic on-demand exam reinstates certifications for all job-roles (for those who have more than 1 certification across multiple job-roles) 


>[!NOTE]
>
>Audience Manager and Campaign Standard will have on-demand exams based on job-roles

**Solution and restart requirement:**

| Certification by Solution | Requirement |
| ------- | ------- |
| Adobe Experience Manager | Continuous learning (for all job roles) |
| Analytics | Continuous learning (for all job roles) |
| Target | Continuous learning (for all job roles)|
| Campaign Classic | On-demand exam |
|Campaign Standard | On-demand exam |
| Audience Manager | On-demand exam |
| Marketo Engage | On-demand exam |

## Get prepped

Here are some suggested resources to help you prepare:

>[!BEGINTABS]

>[!TAB Experience Manager]

Add content from exam guides

>[!TAB Analytics]

Add content from exam guides

>[!TAB Target]

Add content from exam guides

>[!TAB Campaign Classic]

Add content from exam guides

>[!TAB Standard]

Add content from exam guides

>[!TAB Audience Manager]

Add content from exam guides

>[!TAB Marketo Engage]

Add content from exam guides

>[!ENDTABS]

## Restart your certification

To renew your exam click on the "Restart your certification" link below. This will redirect you to the Adobe Credential Management system where you will click "renew your certification" tab on the right side of the screen > then search for RESTART PROGRAM to see the options from above.

* [Restart your certification](https://learning.adobe.com/api.certify.json){target="_blank"}

## Questions

Have a question about Adobe Certification? Please email `certif@adobe.com`.

View the certification [FAQs](https://solutionpartners.adobe.com/solution-partners/training_and_certification/certification/certification_faq.html#){target="_blank"}.
