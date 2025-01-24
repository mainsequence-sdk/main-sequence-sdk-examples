# Main Sequence SDK Examples

Welcome to the **Main Sequence SDK Examples** repository! This repository contains a collection of practical examples that demonstrate how to effectively use the **Main Sequence Python SDK** to build and manage time-based data pipelines, interact with the TDAG and VAM backends, and implement complex workflows.

## About the SDK

The **Main Sequence Python SDK** provides client libraries for interacting with Main Sequence systems. It covers three primary components:

1. **TDAG (Time-Directed Acyclic Graph):** A system for managing complex, time-sensitive data pipelines.
2. **TDAG Client:** Provides methods to interact with the TDAG backend.
3. **VAM Client:** Offers methods to interact with the VAM backend for valuation and analytics data.

For more details about the SDK, visit the [Main Sequence SDK Documentation](www.docs.main-sequence-sdk.main-sequence.io).

## Repository Structure

This repository is organized to help you easily navigate through various examples:

```
├── examples/
│   ├── tdag/
│   │   ├── basic_pipeline.ipynb         # Simple TDAG pipeline example
│   │   ├── advanced_pipeline.ipynb      # Advanced TDAG pipeline with dependencies
│   │   └── financial_model.ipynb        # Financial modeling use case
│   ├── tdag_client/
│   │   ├── submit_workflow.ipynb        # Submitting workflows to TDAG backend
│   │   └── monitor_workflow.ipynb        # Monitoring workflow execution
│   ├── vam_client/
│   │   ├── retrieve_data.ipynb          # Fetching valuation data
│   │   └── process_analytics.ipynb       # Processing analytics data
├── README.md
└── Pipfile
```

## Getting Started

To run the examples in this repository, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/mainsequence/sdk-examples.git
cd sdk-examples
```

### 2. Install Dependencies

Ensure you have Python 3.8+ installed. Then, install the required dependencies using Pipenv:

```bash
pip install pipenv
pipenv install
```

### 3. Activate Virtual Environment

Activate the virtual environment with:

```bash
pipenv shell
```

### 4. Configure Environment

Set up your environment variables for API access:

```bash
export MAIN_SEQUENCE_API_KEY='your_api_key_here'
export MAIN_SEQUENCE_API_URL='https://api.main-sequence.io'
```

### 5. Run Examples

Navigate to an example directory and open the Jupyter Notebook. For example:

```bash
jupyter notebook examples/tdag/basic_pipeline.ipynb
```

## Example Highlights

### TDAG Examples
- **Basic Pipeline:** Learn how to create a simple time-directed acyclic graph for processing data sequentially.
- **Advanced Pipeline:** Explore more complex pipelines with dependencies and scheduling.
- **Financial Modeling:** Implement financial data pipelines for investment strategy predictions.

### TDAG Client Examples
- **Submitting Workflows:** Submit workflows programmatically to the TDAG backend.
- **Monitoring Workflows:** Track the execution and performance of submitted workflows.

### VAM Client Examples
- **Retrieving Data:** Fetch asset valuation and analytics data.
- **Processing Analytics:** Perform analysis on valuation data to derive insights.

## Contributions

We welcome contributions! Feel free to submit issues, feature requests, or pull requests to improve the example repository.

## Resources

- 📖 **[Main Sequence SDK Documentation](www.docs.main-sequence-sdk.main-sequence.io)** – Comprehensive guide to using the SDK.
- 📂 **[Main Sequence SDK GitHub](https://github.com/mainsequence-sdk/mainsequence-sdk)** – Official SDK repository.

## License

This repository is licensed under Custom Main Sequence License. See the [LICENSE](LICENSE) file for details.

---

Happy coding! 🚀

