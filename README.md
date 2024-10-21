# Open-LLM-Problems

Welcome to **Open-LLM-Problems**, a community-driven project designed to crowd-source real-world challenges and limitations encountered when interacting with large language models (LLMs) like GPT-4. Our goal is to create a comprehensive list of examples where LLMs fall short in specific capabilities, so that researchers, developers, and users can focus on addressing these gaps.

## 🚀 Why This Repository?

Despite the rapid advancement of LLMs, there are still many practical issues and limitations in real-world use cases. This repository exists to:

- **Catalog specific problems** users face when interacting with LLMs.
- **Document missing capabilities** or areas where LLMs fail.
- **Collaboratively identify** and track potential solutions or research directions.

## ✨ How You Can Contribute

We’ve made contributing as simple as possible. If you’ve encountered a limitation or problem with an LLM, you can contribute to the growing list by submitting a pull request (PR) to this repository. Here’s how:

1. **Fork the Repository**: Create a personal copy of this repository by clicking "Fork" in the top-right corner.
2. **Edit the Table**: Add your example to the existing table in the `README.md` file. Please follow the format outlined below.
3. **Submit a Pull Request**: Once you’ve added your example, submit a pull request to this repository. We’ll review it, and once approved, it will be added to the main list.

## 🔎 Explore Open Problems

Below is the list of current open problems submitted by the community.

| Prompt                                            | Model Name | Model Reply                                                                                                                                             | Expected Answer/Capability                                                                 | Solutions/Papers (if solved)                                                    | Date Solved | Collected Date | Contributor |
|---------------------------------------------------|------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------|--------------|----------------|-------------|
| "What's the weather in San Francisco right now?"  | GPT-4      | Responded with a general statement, but couldn’t provide real-time weather information.                                                                  | Should provide real-time information or acknowledge inability to fetch live data.               | Not yet solved                                                                  | N/A          | 2024-10-21     | @memray |
| "Explain the impact of this event on the future." | GPT-4      | Discussed the event but failed to correctly establish the cause-effect relationship, oversimplifying the impact timeline.                                | Should demonstrate a clear understanding of causal relationships and future implications.       | Not yet solved                                                                  | N/A          | 2024-10-21     | @memray |
| "Summarize the content of this 100-page document."| GPT-4      | Provided a basic summary but forgot key points from earlier sections and lacked coherence in the final output.                                           | Should retain information throughout the entire document, even in long-context scenarios.      | Not yet solved                                                                  | N/A          | 2024-10-21     | @memray |
| "Summarize an hour-long video lecture on astrophysics." | GPT-4      | Summarized the main points but missed key details and nuances, especially in complex topics like black holes and dark matter.                              | Should accurately summarize long lectures, including all key details and complex concepts.        | Not yet solved                                                                  | N/A          | 2024-10-21     | @memray |

## License
This repository is licensed under the MIT License. See LICENSE for details.
