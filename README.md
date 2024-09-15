# Phishing detection as a 2-step-approach with a combination of a Machine Learning Model and a LLM-Model

## Repositorie for a Scientific Paper
here you can find all the data used for our testing, the prompts, our email-Set as well as our Results

---

## Abstract
In 2023, Phishing was by far the most common reported cyberattack, though the reported incidents were in decline compared to previous years. But Studys showed that generating and multiplying phishing-mails has become faster and easier with state-of-the-art LLM-Models thus, more cost-efficient. With the increased efficiency of phishing attacks, it is likely to see a rise of phishing in the near future. Therefore, it is important to improve existing defence-technics against phishing.
Heiding et al. used commonly available LLMs to generate phishing mails and let them evaluate the mails in a second step. The results varied greatly in the quality of detection. In difference to them, we generated phishing mails to test out different programs for machine generated text (MGT) detection to evaluate if a text is machine generated or not. Only after labeling said mails the LLMs were tasked to determine, if the presented mail is phishing or not. We made two separate runs and compared the results to see, if the additional information provided by these detection programs helps the LLMs to detect phishing mails.
We've run this two-step-approach for prediction on ChatGPT-4, Gemini and Claude as LLMs, and three different detection programs. Though there was some inconsistecy in our testing results, we were able to prove that there is a difference in evaluation. Especially tagging a mail as HGT lowers the LLMs evaluation for phishing probability significantly.
