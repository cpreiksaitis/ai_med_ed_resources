# Ethical/Safety Considerations

### What happens to information I enter into an AI model?

There are many (reasonable) privacy concerns related to inputing data into a LLM. It is worth reading the terms of service for models that you use to understand how and what data is used by the company.

When you input information into a model, the prompt is run through the LLM and generates an output. Your data is not "added" to the AI model and will not be available to the model unless it is provided to it in a prompt. When you continue a conversation in a thread, the application sends the previous content of your conversation to the model so that it is aware of what has come before the most recent entry in a conversation. The most recent iteration of ChatGPT has a "memory" feature that will gradually store information about you as a user in order to improve the responses you get from the model. This functions just as we discussed in the prompt engineering section about providing context. The application does this on the back end to allow the model to have access to context to improve its responses. This may be why different users get different responses with the same prompt. There is the ability to opt-out of this feature or temporarily deactivate it.

Your conversation history is stored by most of these companies in order to allow you to return to a previous conversation. You can delete a conversation and it will be removed from the company's server eventually.

Several of these companies _may_ use your data to train or improve their models. This doesn't happen in real time, as training these models takes weeks and a large amount of computing power. They may use your prompts and model responses as well as your feedback or corrections to the model to improve model output in the long run. These companies say that they will take efforts to minimize the use of personal information in this process. All companies allow you the ability to opt out of this process.

There are different ways to interact with these models such as through an API or with a professional account that at baseline do not store or record information put into the model. There are also instances that individual institutions have that are HIPAA-compliant.

### What does this mean for my data?

Although you can opt-out of many of these functions, data is still stored in many cases (at least for some period of time). Therefore, I would use judgement regarding what potentially identifiable or sensitive content is put into an AI model. It is worth considering each use case seperately and making special considerations if you are working in a use case with sensitive data.

### What is plagairism with AI?

Many people are concerned about the potential for passing off AI-generated content as their own and the potential for academic dishonesty. Here are a few points to consider:

* Institutions and organizational bodies are not fast-moving. It took probably a year for most journals to develop policies on AI writing and many institutions still do not have concrete recommendations. It is worth checking whether your instutiton has such a policy.
* Unless someone is truly careless in using AI to generate content, there is currently no reliable way to differentiate between AI and human-generated content. Misacusations of individuals using AI for their writing are potentially harmful, which is why I don't advocate for restricting the use of AI tools.
* I recommend we encourage the use of AI and ask people to reasonably disclose that use. If AI use was part of the methodology for your study, its use should be documented in the methods section. If it was used for editing or feedback on content, you may wish to include a note at the end of a manuscript to that effect. Ultimately, I feel that the responsibility will fall to the users to disclose when we are using AI. Part of that disclosure process is taking responsibility for the final generated content and reflecting on the source of original ideas: "Is this _my_ work or the work of an AI model?"
* That being said, we also must be practical with this disclosure. We don't require disclosure of every piece of technology that went into generating a final product, nor do we ask to see a list of everyone who offered feedback on a paper. Making this process too onerous or stigmatizing against the use of AI has problems as well. An amazing value of this tool is its democratic access. Using it to aid with writing may help those who don't have a large number of mentors available to provide feedback, those for whom English is not their first language, or those who simply struggle to express themselves clearly.
