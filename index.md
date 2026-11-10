# Shant Guedekelian

**Email:** sguedekelian@ucsd.edu

**Domain:** D42 (SD City & County)
**Mentor:** Bijan Arbab

---

**1. Most interesting topic in your domain this quarter:**

The most interesting thing was seeing how much of permit delay sits with the applicant and not the City. Going in, I assumed reviewers were the bottleneck. But when we split each project's time into City days and applicant days, a big share of the wait came from applicants making fixes and resubmitting. It changed our question from "how do we speed up reviewers?" to "how do we help applicants get it right the first time?"

**2. Potential Quarter 2 investigation:**

I'd like to use the review comment data to find the comments reviewers give most often, and break those down by permit type, location, and other factors. The goal is to turn those patterns into a practical prep guide for applicants, like "for this kind of permit in this area, here are the top issues reviewers flag." That tells applicants what to fix before they submit, so there are fewer resubmittals, and it gives DSD a view of which problems keep coming up.

**3. A change to the Quarter 1 approach:**

Our Q1 plan leaned toward a prediction model for which permits would need multiple resubmittals. In practice, that was much harder than expected. Submissions vary a lot, from hand-drawn plans to different formats and levels of detail, and a model can't capture most of that. If I were redoing Q1, I'd scope around the comments data from the start, since it shows what reviewers actually asked for. It's also more directly useful: applicants get specific guidance, not just a risk score. I'd also get the data sources confirmed with DSD earlier, so we don't lose time to access delays.

**4. Other techniques I'd like to use:**

* **Text analysis (NLP):** cleaning and grouping the comments to find common themes, since the same issue is often worded many different ways.
* **Topic modeling or clustering:** to automatically group similar comments and find the main categories of issues.
* **Frequency and association analysis:** to see which comments tend to appear together and for which permit types or locations.
* **Mapping and spatial analysis:** to check whether certain issues cluster in certain neighborhoods.
* **Survival analysis:** to see how much time different comment types add to a permit's review, so we can prioritize the ones that cause the most delay.
