# 📁 Serverless File Validation System using AWS SNS

## 📌 Project Overview
This project demonstrates a **serverless, event-driven architecture** using AWS services to automatically validate uploaded files.

Only **JPG and PNG image files** are allowed.  
Any other file type is **detected and automatically deleted**, and the action is logged for monitoring and debugging.

The system also sends **real-time notifications using Amazon SNS** to inform users about successful uploads or invalid file deletions.
