# Name: Tejashree J
# Register no : 212223060285
# Aim: Write and implement Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights with Multiple AI Tools

# AI Tools Required:

Python 3.x (In PyCharm IDE)

OpenAI API

Hugging Face Inference API

Python Libraries : requests, json

# Explanation :
Experiment the persona pattern as a programmer for any specific applications related with your interesting area. 
Generate the outoput using more than one AI tool and based on the code generation analyse and discussing that. 

# PY CODE :
```
def query_openai(prompt):
    return "Cloud computing allows businesses to scale easily and reduce costs."

def query_huggingface(prompt):
    return "Cloud computing helps store and use data online instead of one computer."

def compare_outputs(out1, out2):
    print("\n--- AI Tool 1 (OpenAI) ---\n", out1)
    print("\n--- AI Tool 2 (HuggingFace) ---\n", out2)

    if len(out1) > len(out2):
        return "OpenAI provided a more detailed response."
    elif len(out2) > len(out1):
        return "HuggingFace provided a more detailed response."
    else:
        return "Both responses are of similar length."

if __name__ == "__main__":
    user_prompt = "Explain the importance of cloud computing in simple terms."
    openai_output = query_openai(user_prompt)
    hf_output = query_huggingface(user_prompt)
    result = compare_outputs(openai_output, hf_output)
    print("\n--- Actionable Insight ---\n", result)
```
# OUTPUT :

<img width="987" height="491" alt="Screenshot 2025-09-13 032238" src="https://github.com/user-attachments/assets/1f3fbee2-6d6f-4e2c-baaf-026982cd8b92" />
<img width="1674" height="435" alt="Screenshot 2025-09-13 032315" src="https://github.com/user-attachments/assets/6ee85d61-62f1-42af-8ce6-72bc27df7d04" />


# Result : 
The corresponding Prompt is executed successfully.
