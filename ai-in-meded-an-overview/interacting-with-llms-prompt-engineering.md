# Interacting with LLMs: Prompt Engineering

* **Prompting:** LLMs like ChatGPT interact through prompts, which are instructions or questions you provide to guide the AI's response.
* **Prompt engineering:** Crafting effective prompts is crucial for getting optimal results from LLMs. Consider these principles:
  1. **Context:** Clearly specify the role you want the AI to assume and the context of your request. For example, "Act like an expert in medical education" or "You are a tutor for medical students."
  2. **Specific Instructions:** Provide detailed instructions to guide the AI towards the desired output. Be explicit about the type of response you need (paragraph, list, table, etc.), the tone (academic, conversational), and any specific requirements.
  3. **Examples:** Include examples to illustrate the desired output format or style. This helps the AI understand your expectations better.
* **Iterative Refinement:** The output of LLMs can vary. Experiment with different prompts, provide feedback, and iteratively refine your instructions until you achieve satisfactory results.

### Tutorial

Let's go through the basics of prompt engineering. We'll use ChatGPT as our example, but you can repeat the same process with other models. We will assume that you have registered for a paid account so that we can explore more features.

We are going to go through how to construct a prompt step-by-step. Understand that prompting is a skill that gets better with experience and there isn't a magic prompt that will just work. The more you use AI, the more you will understand what works and what doesn't. You can even ask the AI to help you write a prompt.

1. Navigate to [https://chatgpt.com/](https://chatgpt.com/) and login.
2. Enter in the prompt "Write me a paragraph about the importance of simulation." and press enter.

<figure><img src="../.gitbook/assets/Screenshot 2024-08-20 at 2.06.20 PM.png" alt="" width="563"><figcaption></figcaption></figure>

You see we get a pretty generic paragraph about simulation.&#x20;

3. So we add in the additional context "act like an expert medical educator."

<figure><img src="../.gitbook/assets/Screenshot 2024-08-20 at 2.07.13 PM.png" alt="" width="563"><figcaption></figcaption></figure>

And we get a better response, which discusses clinical reasoning, teamwork, and things relevant to health professionals.

4. We can add some further instructions about style and tone, so we can ask for an academic piece of journal-style writing.

<figure><img src="../.gitbook/assets/Screenshot 2024-08-20 at 2.09.15 PM.png" alt="" width="563"><figcaption></figcaption></figure>

5. Then, since this version of ChatGPT is linked to the internet, I can ask it to search for academic articles to support its claims and add references.

<figure><img src="../.gitbook/assets/Screenshot 2024-08-20 at 2.10.47 PM.png" alt="" width="563"><figcaption></figcaption></figure>

Are these articles, the best? Probably not, and I wouldn't 100% trust the sources, but you can click on the links and read the articles and use them potentially as a starting point for your own literature search.

6. The last point, and probably the most important, is that you can add your expertise and your input and help guide the AI. Because up until now there has been no human input involved in the creation of this material, which often doesn't make for great writing.

<figure><img src="../.gitbook/assets/Screenshot 2024-08-20 at 2.13.24 PM.png" alt="" width="563"><figcaption></figcaption></figure>

7. Finally, we can use an additional technique known as "chain of thought," where we ask the AI to think step-by-step through the process. We can ask the AI to first create an outline, then write a rough draft, and then revise it and improve it into a final draft.

<figure><img src="../.gitbook/assets/Screenshot 2024-08-20 at 2.15.48 PM.png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/Screenshot 2024-08-20 at 2.16.00 PM (1).png" alt="" width="563"><figcaption></figcaption></figure>

We’ve talked about creating and refining a prompt, but the way I prefer to work with the AI is through iterative refinements. So I will say, could you expand on the second point, or add some of my own thoughts. Working as part guide, part editor, part writer to get an optimal output.

### Randomness

One important thing to note is that there is randomness built into all these AI systems. So when you give the AI one prompt, you may get different outputs during multiple iterations.

<figure><img src="../.gitbook/assets/Screenshot 2024-08-20 at 2.19.26 PM.png" alt="" width="563"><figcaption></figcaption></figure>

You can actually use this to your advantage, like asking for several examples of a title or a paragraph and picking the one you like. You can then refine that one and put it back into the system as a new chat with a prompt to refine it or expand on a point and just keep working that way until you get something you like.
