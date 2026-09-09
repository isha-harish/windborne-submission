### 1. Which of our open ML Research Engineer roles are you interested in, in order?

Applied Research, General, Model Evaluation. I’m most interested in Applied Research because I enjoy problems where I have to figure out what to model, test different assumptions, and understand why a model behaves the way it does. My research at IISc and ML projects have made me especially interested in that process.

### 2. Describe an ML idea you were initially excited about but later decided was wrong or unimportant. What changed your mind?

I was initially very excited about adding more complexity to models because I assumed a stronger model would naturally mean better results. Working on smaller models and knowledge distillation changed that. I started paying more attention to whether the extra complexity actually improved the outcome enough to justify the cost. Often, it didn’t.

### 3. Describe a time when you embarked on a sidequest / took initiative outside your core job responsibilities. What value did you add to your organization? What drove you to action?

At Check Point, I started digging beyond my immediate task when I noticed that debugging our AI services often meant tracing problems across models, tools, streaming, and APIs. I built and tested pieces of the surrounding infrastructure myself rather than treating each issue as someone else’s problem. I did it because I wanted to understand where things were actually breaking, and it made debugging much faster.

### 4. How could better accuracy fail to translate into more useful forecasts for a weather model?

A model can have better average accuracy while still being less useful for the forecasts people actually care about. It might improve common weather patterns but get rare or extreme events wrong, or be slightly better overall while being worse at the specific location or time someone needs. The metric can improve without improving the decision the forecast is meant to support.

### 5. Describe a time you changed how you use LLMs in your work. What did you observe that prompted the change?

At Check Point, I initially treated model choice as mostly a question of which model gave the best answer. After working with different providers and tasks, I noticed that the “best” model depended heavily on the job. I started routing requests based on the task instead of sending everything to one model. That reduced unnecessary cost and made some workflows more reliable.

