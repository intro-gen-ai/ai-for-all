# ai-for-all
Changing the notion of who AI is for

[Try the app here](https://huggingface.co/spaces/shalinialisha/shalinialisha-ai-for-all)

## Project Creator
Shalini Thinakaran, shalini.a.thinakaran@vanderbilt.edu, thinaksa

## Project Proposal 

### Description of Problem/Opportunity
As of right now, there are no machine learning models whose trainings are focused on readings that include how power dynamics effect our society. There is nothing out there where I can recieve responses that are obviously "understanding" of social dynamics that marginalized communitites are subjected to without being prompted to recognize those dynamics. 


### Proposed Solution/Approach
I will be fine tuning a machine learning model using documents written by people like James Baldwin and Angela Davis that use literature as a conduit for social justice to create responses that make the user feel it is somewhat "aware" of the social implications of class, race, gender, ect. Additionally, using a mixture of personal narratives and historical context will hopefully allow for the model to present responses that are inclined to better suit the some needs BIPOC people might have. 

Because the training of a machine learning model means having the model "guess" the end of a sentence or the next chunck of a paragraph (context learning), I'll be using dissertations or papers that reflect on the themes that appear within the personal narratives. This will cut out the "thinking" that the model is unable to do, especially with just the personal narratives. 


### Project Outline and Timeline
* Decide which model to fine-tune
  * Llama V2
  * GPT 2
  * BERT

* Choose the materials 
  * Must be a mixture of literature, historical context, and personal narrative
  * Clean the materials (delete blank pages, publishing info, ect.)
  * Upload these materials to [HuggingFace as a dataset](https://huggingface.co/shalinialisha/ai-for-all)
* Fine-tune the model

## Goals of project 

### Goal 1
Having a variety of resources for the model to train on so that it can be a resource to BIPOC folks. 

### Goal 2
Centering marginalized voices in the field of AI fine-tuning.

## Project Metrics 

### Metric 1
GPT-2:
<img width="450" alt="hi" src="https://github.com/intro-gen-ai/ai-for-all/assets/123770923/9aed770d-e4c8-4b19-a00c-a72ccbe01625">

AI-for-all:
<img width="450" alt="hi_ai" src="https://github.com/intro-gen-ai/ai-for-all/assets/123770923/7b55f700-75dd-4ec6-9438-8c49422c20c4">


### Metric 2
GPT-2:
<img width="450" alt="college" src="https://github.com/intro-gen-ai/ai-for-all/assets/123770923/70266b9c-408f-47cb-a7ea-a97f4bb29eeb">

AI-for-all:
<img width="450" alt="college_ai" src="https://github.com/intro-gen-ai/ai-for-all/assets/123770923/e60eae22-8873-420b-aa6d-037582a5609f">


### Metric 3
GPT-2:<br>
<img width="450" alt="last2" src="https://github.com/intro-gen-ai/ai-for-all/assets/123770923/53ee8a30-054f-4c24-a807-cea6d691ef8a">


AI-for-all:
<img width="450" alt="last1" src="https://github.com/intro-gen-ai/ai-for-all/assets/123770923/20aa599d-04c8-43a9-99fb-a95d01419358">


### Metric 4
GPT-2:
<img width="450" alt="yes1" src="https://github.com/intro-gen-ai/ai-for-all/assets/123770923/d4485fd6-44f5-4b4d-99f0-767503c059db">

AI-for-all:
<img width="450" alt="yes_ai" src="https://github.com/intro-gen-ai/ai-for-all/assets/123770923/03ff3653-7400-4326-8470-8f2d48940808">

## Self-Evaluation
**Due December 8, 11:59pm**

300-1000 words

Address each of the goals, and assess each of the metrics. Include a statement on each on what you achieved or did not achieve, give support for your assessments.

I believe I acheived both of my goals, seeing as though GPT-2 wasn't even trained on any documents on social power dynamics. Here is more detail on the individual metrics:

* Metric 1: I was simply seeing how the original GPT-2 responds to 'hi'. Obviously, as an older model it had difficulty being coherent. 
* Metric two: Here, prompting the model seemed to show a starker difference in comprehension. 
* Metric three: We see the poetic nature of the authors I included through the rhetorical questioning.
* Metric four: We see an obviously dangerous response from GPT-2 and a potentially sophisticated response from AI For All.
  
AI for All demonstrates improved coherence, relevance, and style when generating text related to inclusion and marginalization. My fine-tuning approach resulted in clear enhancements over the original GPT-2 model across defined metrics, achieving my intended goals.


## Reflection on Learning
**Due December 8, 11:59pm**

500-1000 words

What do you take away from the project? Has this changed how you understand AI? Does and how does this affect future plans for learning, work, or otherwise?

This project gave me hands-on experience with fine-tuning natural language models like GPT-2 for a specific purpose. I gained valuable skills in data curation, hyperparameter tuning, monitoring training, and deploying the finished model. My coding abilities definitely improved as well.

On a deeper level, working so closely with AI exposed its incredible promise but also its limitations. State-of-the-art models can generate human-like text, yet they lack true language understanding without the right training data. I also witnessed how biases can sneak into AI systems if minorities are excluded from the process.

These takeaways have made me even more passionate about continuing my AI education. With access to more computing resources and cleaner training data, I believe we can create inclusive AI assistants, creative tools, and content moderators. My goal is to pursue graduate-level studies in AI while partnering with marginalized communities to co-create empowering, ethical applications.

Projects like AI for All are just a start, but they teach core skills I will need to drive change. My dream is for AI to amplify all voices equally while resolving hierarchies of human values. We have significant breakthroughs still to make, which is why I am committed to learning all I can in this emerging field. By considering inclusivity from day one, I believe we can get there.

## What's Next?
**Due December 8, 11:59pm**

100-500 words

Do you plan on continuing the project? What will you do with what you've learning?

Yes, I definitely plan to continue developing AI for All over time. This was an initial proof of concept, but I learned so much that I want to build on.

My next steps are to expand the training dataset to include more perspectives and types of marginalization. I will also experiment with fine-tuning more advanced models like GPT-3 and Codex to generate longer-form text focused on education and empowerment.

Ultimately, I envision AI for All evolving into an inclusive language model that can power educational applications, creative tools for marginalized groups, policy analysis on equity issues, and more. The core skills I built in data curation, compute optimization, and model deployment will serve me well as I scale impact.

With each iteration, I want to move closer to AI that uplifts all of humanity. This starter project sparked my passion for leading inclusion in AI development. By open sourcing my work and findings, I hope to move the broader field in a similar direction.
