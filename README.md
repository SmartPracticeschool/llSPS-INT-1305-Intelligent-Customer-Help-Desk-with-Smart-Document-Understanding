#llSPS-INT-1242-Intelligent-Customer-Help-Desk-with-Smart-Document-Understanding

Intelligent Customer Help Desk with Smart Document Understanding This is repositroy build with the help of Watson Asistance,Discovery,Clould Function and Node Red app of IBM Cloud. It is made with the regard of partial fullfillment of Smartinternz Internship Program.

#Project Description : The typical customer care chatbot can answer simple questions, such as store locations and hours, directions, and maybe even making appointments. When a question falls outside of the scope of the pre-determined question set, the option is typically to tell the customer the question isn’t valid or offer to speak to a real person.

In this project, there will be another option. If the customer question is about the operation of a device, the application shall pass the question onto Watson Discovery Service, which has been pre-loaded with the device’s owners manual. So now, instead of “Would you like to speak to a customer representative?” we can return relevant sections of the owners manual to help solve our customers’ problems. To take it a step further, the project shall use the Smart Document Understanding feature of Watson Discovery to train it on what text in the owners manual is important and what is not. This will improve the answers returned from the queries. Scope of Work Create a customer care dialog skill in Watson Assistant Use Smart Document Understanding to build an enhanced Watson Discovery collection Create an IBM Cloud Functions web action that allows Watson Assistant to post queries to Watson Discovery Build a web application with integration to all these services & deploy the same on IBM Cloud Platform

In Watson Discovery I have added ecobee3_userguide.

I have uploaded a demo video of this project in my youtube channel. https://youtu.be/Ub-0n3tcHHw

Node_Red Dasboard link after deploying : https://node-red-vqivh.eu-gb.mybluemix.net/ui

Preview link of Watson Assistant : https://eu-gb.assistant.watson.cloud.ibm.com/eu-gb/crn:v1:bluemix:public:conversation:eu-gb:a~2F0d1fb70035ce4af6bec992d78e38057e:4846548c-dbfd-4009-9201-dd16b71e6093::/skills/ac7dff0a-cdf3-4def-9c05-5f563fd96679/build/intents Have a casual talks about availability_of_flight, booking a flight, check_status_of_a_flight like What is status of AA 456,etc.
