# Proposal-Helper

🔍 Problem Statement
In the world of proposal writing, finding relevant past data can be a tedious task. Our solution? An AI-assisted proposal retrieval chatbot that streamlines this process using AWS services. This blog walks through how we built this system using AWS Lex, Lambda, Kendra, Bedrock, and more.

Proposal writers often struggle with:
✅ Searching through past proposals 📂
✅ Ensuring consistency across documents 📝
✅ Reducing time spent on manual lookup ⏳

Our chatbot does not generate proposals but assists writers by retrieving relevant information using Retrieval-Augmented Generation (RAG).

🛠️ Tech Stack
Our system integrates multiple AWS services to ensure secure, efficient, and scalable retrieval of proposal data.

📌 Key AWS Services Used
AWS Lex 🤖 - Chatbot interface for user interactions
AWS Lambda 🔄 - Backend logic for processing queries
Amazon Kendra 📚 - Intelligent search across proposal documents
Amazon Bedrock 🤖 - LLM-powered retrieval and summarization
Amazon Cognito 🔐 - User authentication and security
Amazon API Gateway 🔗 - Secure API connections
Amazon S3 ☁️ - Storage for processed proposal data

🏗️ System Architecture
The architecture (shown below) integrates multiple AWS components to deliver a seamless experience for users.
system_arch

📌 How It Works:
1️⃣ User interacts with the chatbot via AWS Lex
2️⃣ Lex triggers AWS Lambda, which processes the request
3️⃣ Amazon Kendra searches SharePoint for relevant documents
4️⃣ Amazon Bedrock enhances retrieval with LLM-based summarization
5️⃣ API Gateway & Cognito ensure secure and authenticated access
6️⃣ Results are returned to the user, saving time and effort. 🎯

🎯 Impact of the Solution
✅ 60% reduction in manual search time ⏳
✅ More accurate proposal data retrieval 📑
✅ Enhanced security with AWS Cognito 🔐
✅ Scalable architecture with AWS Lambda & API Gateway 🚀

🚀 What’s Next?
We plan to enhance the system with:
✔️ Better NLP capabilities using fine-tuned LLM models
✔️ Integration with more data sources
✔️ Improved user experience with real-time insights

🎤 Final Thoughts
This project showcases the power of AWS AI services in streamlining proposal writing. By integrating Lex, Kendra, Bedrock, and Lambda, we’ve built an intelligent chatbot that saves time and enhances productivity.

🔗 Stay tuned for more updates and improvements! Would love to hear your thoughts in the comments! 🚀
