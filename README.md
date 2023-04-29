# AB-Testing-Experiment

A/B testing, also known as split testing, is a marketing experiment wherein you split your audience to test a number of variations of a campaign and determine which performs better. In other words, you can show version A of a piece of marketing content to one half of your audience, and version B to another.

![image](https://user-images.githubusercontent.com/64821137/235305996-c3fa20b0-2ce1-4e28-8e4a-170f16d7e705.png)

### How does A/B testing Work?

To run an A/B test, you need to create two different versions of one piece of content, with changes to a single variable. Then, you'll show these two versions to two similarly sized audiences and analyze which one performed better over a specific period of time (long enough to make accurate conclusions about your results).

Explanation of what a/b testing is

<p align="center">
  <img src="https://user-images.githubusercontent.com/64821137/235306046-5c3b2c0f-208a-408f-a350-634fa566818a.png" />
</p>

### Experiment Definition

We developed a new webpage and want to test it's effects on purchase conversion. As such we split our users evenly into 2 groups:
1. **Control**: They get the old webpage
2. **Treatment**: They get the new webpage

Metric we want to track: 

$$
\text{purchase conversion} = \frac{\text{Converted Users}}{\text{Exposed Users}}
$$

We have 3 weeks of logged exposure/conversion data. Let's define these terms:
1. **Exposure**: A user is bucketed as control or treatment and sees their corresponding page for the first time in the experiment duration
2. **Conversion**: An exposed user makes a purchase within 7 days of being first exposed

Questions you should ask when setting up a test:
- How do you think the experiment will fair?
- Do we have actionable next steps laid out?

