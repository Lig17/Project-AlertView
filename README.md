# AlertView

AlertView is a real-time disaster image annotation, search, and response system that leverages AWS services and advanced machine learning models to provide actionable insights during disaster events.

## Features

- Real-time data ingestion using AWS Kinesis
- Automated image annotation with Amazon SageMaker
- Metadata extraction and storage in DynamoDB
- Real-time search and filtering using Pinecone
- Interactive Streamlit dashboard for user queries and visualizations
- Chatbot integration for alerting government officials and resource allocation

## Setup

1. Install the required Python packages:
    ```sh
    pip install -r requirements.txt
    ```

2. Deploy the infrastructure using AWS CloudFormation or Terraform.

3. Configure the AWS services and integrate them with your application.

4. Run the Streamlit dashboard:
    ```sh
    streamlit run frontend/streamlit_dashboard/dashboard.py
    ```


## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
