# MLP-82
Constructing machine learning architecture with AWS SageMaker, AWS  Lambda  and  AWS API Gateway



![Project structure](https://github.com/thedatanerdz/MLP-82/blob/main/structure.JPG)

### When you work for a client in a different geographic region, it's generally a good practice to set your AWS region code to the region that is geographically closer to your client or to the region where your client's AWS resources are located.
#### Considerations:
- Latency: AWS services in the same region tend to have lower latency when communicating with each other. If your client's AWS resources are primarily hosted in the Asia Pacific (Mumbai) region and you are in South Africa, setting your region to Asia Pacific (Mumbai) might provide better performance and lower latency for interactions with your client's resources.
- Data Residency: Some clients may have data residency requirements that dictate where their data should be stored. In such cases, it's important to ensure that you comply with their data residency policies by setting your AWS region accordingly.
- Compliance: Depending on the industry your client operates in, there may be regulatory compliance requirements that specify where certain data or services must be hosted. Adhering to these compliance regulations may require you to set your region to align with your client's compliance needs.
- Collaboration: Setting your region to match your client's region can also simplify collaboration and resource sharing. It ensures that you are working within the same AWS infrastructure, making it easier to manage permissions, share resources, and collaborate effectively.
-Cost Considerations: AWS pricing can vary slightly between regions. It's a good practice to understand the cost implications of choosing a specific region and consider any cost-sharing arrangements with your client.
