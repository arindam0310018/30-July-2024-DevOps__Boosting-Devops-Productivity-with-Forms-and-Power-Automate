# Boosting Devops Productivity with Forms and Power Automate:-
 
Greetings to my fellow Technology Advocates and Specialists.

In this Session, I will demonstrate __How to create Azure Devops Work-Items using Microsoft Forms and Power Automate.__

| __AUTOMATION OBJECTIVES:-__ |
| --------- |

| __#__ | __TOPICS__ |
| --------- | --------- |
| 1. | Create Microsoft Forms and Publish. |
| 2. | Create Power Automate Flow - __Automated Cloud Flow__. |
| 3. | Integrate Microsoft Forms and Azure Devops with Power Automate. |
| 4. | There are 3 Actions created in the __Automated Cloud Flow__. |
| 4(a). | Action#1: __When a New Response is Submitted__. |
| 4(b). | Action#2: __Get Response Details__. |
| 4(c). | Action#3: __Create a Work-item in Azure Devops__. |
| 5. | Create Azure Devops Work-items by submitting Microsoft Forms. |

| __REQUIREMENTS:-__ |
| --------- |

1. Access to Microsoft Forms.
2. Access to Microsoft Power Automate.
3. Azure DevOps Organisation and Project.

Below follows the step by step Process:-

| __1. Create Microsoft Forms and Publish__. |
| --------- |
| a. Login to Microsoft Forms and Click on __"New Form"__. |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/wstj66oxhijjuiuwd6i5.jpg) |
| b. Create the __Required Microsoft Form__. |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/jzyofzcmo9tfnidw7zul.jpg) |
| c. Once Microsoft Form is created, Click on __"Preview"__. |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/nuhcr140xd45fmcibxbz.jpg) |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ex693mwdkg1s5uyadhdt.jpg) |
| d. Then click on __"Present"__. |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/nuhcr140xd45fmcibxbz.jpg) |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/7x1yzmlhg3cypsnop6z1.jpg) |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/cc5mgs1ehstn4wkphslk.jpg) |
| From above, copy the link under the QR Code and open in another browser tab. |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ottav8pe7zc84s3r6khe.png) |

| __2. Create Power Automate Flow__. |
| --------- |
| a. Login to __Microsoft Power Automate__ > __Create__ > __Automated cloud flow__. |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/s0fdjwww6x5ndtsq9qkr.jpg) |
| b. Provide the __Flow Name__, __Choose the below Trigger__ and Click on __"Create"__. |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/yut2iqsxfebca4cvyrz7.jpg) |

| __3. Integrate Microsoft Forms with Power Automate.__ |  
| --------- |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/apezmcindwaxp8q3zxvb.jpg) |

| __4. There are 3 Actions created in the Automated Cloud Flow.__ |
| --------- |
| 4(a) Action#1: When a New Response is Submitted. |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ga1fyhyavph6o4mk4sg0.jpg) |
| Add an Action - Microsoft Forms |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/lhv28c1xjh58oi26ni91.jpg) |
| 4(b) Action#2: Get Response Details.
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/2dxcap33e9x410c70ail.jpg) |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/njkelnx9yp8qp0yq211s.jpg) |
| When a new response is submitted using Microsoft Forms, Response ID is captured by selecting __"Dynamic Content"__. |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/5elshzdxh55b4hi2dzeu.jpg) |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/y74ecic0roqjzr334hyq.jpg) |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/lmpdkbyi0g1p7v7rfc0l.jpg) |
| 4(c) Action#3: Create a Work-item in Azure Devops. |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/rupgkqft2em4rtc6ytv5.jpg) |
| Ensure the __"Work Item Type"__ is selected as __"Issue"__. |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/umqxikkwjbzlh64fpcod.jpg) |
| The __"Title"__ option in __"Create a Work Item"__ Action in Microsoft Power Automate is mapped to Microsoft Forms __"Get Response Details"__ __"Task Name"__ under __"Dynamic Content"__. |
|![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/rs1q4x44ku1n9zgar9vj.jpg) |
|![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/jtqctif8b55zssto3tk4.jpg) |
| The __"Description"__ option in __"Create a Work Item"__ Action in Microsoft Power Automate is mapped to Microsoft Forms __"Get Response Details"__ __"Description"__ under __"Dynamic Content"__. |
|![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/m7pr1jucc6rayjay75md.jpg) |

| __5. Create Azure Devops Work-items by submitting Microsoft Forms.__ |
| --------- |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/0gf6a44360parw9do4bn.jpg) |
| Response was submitted. |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/y3u5lbozgso56q8o77bl.jpg) |
| Azure Devops Work item was successfully created. |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/z3gx6n2d0v1erz7to4ql.jpg) |
| The Success Status can also be viewed from Microsoft Power Automate. |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/xc0p5luo0zhe0rwbnq8c.jpg) |

__Hope You Enjoyed the Session!!!__

__Stay Safe | Keep Learning | Spread Knowledge__
