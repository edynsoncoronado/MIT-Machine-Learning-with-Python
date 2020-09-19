# MIT-Machine-Learning-with-Python
https://www.edx.org/es/course/machine-learning-with-python-from-linear-models-to

Where do you go to learn these skills? What courses are the best?  
There’s no best answer. Everyone’s path will be different. Some people learn better with books, others learn better through videos.  
What’s more important than how you start is why you start.  
Start with why.  
- Why do you want to learn these skills?
- Do you want to make money?
- Do you want to build things?
- Do you want to make a difference?

There’s no right reason. All are valid in their own way.

Start with why because having a why is more important than how. Having a why means when it gets hard and it will get hard, you’ve got something to turn to. Something to remind you why you started.

## What does a machine learning engineer actually do?
What a machine engineer does in practice might not be what you think.  
Despite the cover photos of many online articles, it doesn’t always involve working with robots that have red eyes.  
Here are a few questions a machine learning engineer has to ask themselves daily.  
- Context — How can ML be used to help learn more about your problem?
- Data — Do you need more data? What form does it need to be in? What do you do when data is missing?
- Modeling — Which model should you use? Does it work too well on the data (overfitting)? Or why doesn’t it work very well (underfitting)?
- Production — How can you take your model to production? Should it be an online model or should it be updated at time intervals?
- Ongoing — What happens if your model breaks? How do you improve it with more data? Is there a better way of doing things?

There’s so much happening in the field it can be daunting to get started. Too many options lead to no options. Ignore this.

Start wherever interests you most and follow it. If it leads to a dead end, great, you’ve figured out what you’re not interested in. Retrace your steps and take the other fork in the road instead.

Computers are smart but they still can’t learn on their own. They need your help.

### Step1
docker run --name MIT-ML-Python -v $(pwd):/opt/notebooks -i -t -p 8883:8888 continuumio/anaconda3 /bin/bash -c "/opt/conda/bin/conda install jupyter -y --quiet && /opt/conda/bin/jupyter notebook --notebook-dir=/opt/notebooks --ip='0.0.0.0' --port=8888 --no-browser --allow-root"

Links:
- https://towardsdatascience.com/i-want-to-learn-artificial-intelligence-and-machine-learning-where-can-i-start-7a392a3086ec
- http://www.fast.ai/2018/07/12/auto-ml-1/
- https://en.wikibooks.org/wiki/LaTeX/Mathematics
- https://nbviewer.jupyter.org/github/twistedhardware/mltutorial/blob/master/notebooks/jupyter/2.%20Markdown%20%26%20LaTeX.ipynb
