| [Home Page](https://natashapawar.github.io/dataviz-portfolio/) | [Visualizing Government Debt](https://natashapawar.github.io/dataviz-portfolio/visualizing-government-debt) | [Critique by Design](https://natashapawar.github.io/dataviz-portfolio/critique-by-design) | [Final Project I](https://natashapawar.github.io/dataviz-portfolio/final-project-part-one) | [Final Project II](https://natashapawar.github.io/dataviz-portfolio/final-project-part-two) | [Final Project III](https://natashapawar.github.io/dataviz-portfolio/final-project-part-three) |

# Makeover Monday: Critique by Design

## Part 1: Choosing a Visualization

The data visualization I chose is titled, [“Which is the Best Performing Marvel Movie?”](https://informationisbeautiful.net/visualizations/which-is-the-best-performing-marvel-movie/) by Information is Beautiful. It presents a comparative analysis of Marvel films based on multiple performance metrics. The visualization ranks Marvel Cinematic Universe (MCU) films using a combination of critical reception (Rotten Tomatoes scores), audience ratings (IMDb scores), box office revenue (adjusted for inflation), and profitability. 

I chose this visualization as it aligns well with my academic area of focus. I have also been a fan of the MCU (although more so the earlier years), and I'm always interested in looking into how these movies fair in general audience ratings.

## Part 2: The Critique 

I critiqued this visualization using Stephen Few's Data Visualization Effectiveness Profile.

| Criteria        | Rating |
|----------------|--------|
| Usefulness     | 8      |
| Completeness   | 10      |
| Perceptibility | 6      |
| Truthfulness   | 9      |
| Intuitiveness  | 9      |
| Aesthetics     | 6      |
| Engagement     | 10      |

*Observations:* The visualization effectively shows Marvel movies and their performance relative to their budgets over time. The color-coding by franchise and the ability to filter by franchise is very effective for identifying trends within each Marvel sub-franchise. For example, it's easy to see how Avengers movies consistently outperform in profitability. The inclusion of movie names next to each data point is very helpful for quickly identifying specific films without additional interaction. The ability to update and change the axes to further interact with the data also adds a lot of value to the interpretations possible. It is immediately clear that Avengers: Endgame and Spider-Man: No Way Home are clear leaders in profitability, while Incredible Hulk and Black Widow are among the lower performers. 

*What Worked Well:* The dotted line indicating breakeven (100% budget recovery) helps viewers easily distinguish profitable movies from those that underperformed. The legend makes it easy to filter and group movies by franchise, adding even more clarity. The graph effectively communicates which Marvel movies were the most profitable relative to their budget, not showing causation but rather relating the data. The information is extremely valuable to any stakeholders or fans who may be interested in it and want to know more - they also have the ability to switch axes to draw more correlations.

*What Didn’t Work Well:* Movies with similar release years or similar performance (ex: 400% budget recovered) have overlapping labels and points, making some parts of the visualization cluttered and harder to read. The information feels very congested, and while you can filter or change things to understand it better, upon first glance it is extremely overwhelming to understand.

*Suggested Changes:* Instead of having "size = no metric," we could use bubble size to indicate total gross revenue, enabling the viewer to compare absolute performance alongside relative profitability. It could be useful to spread apart the data more, leaving more space on the x and y axis and adding a scroll feature to give each movie enough space, even when the numbers are slightly overlapping. Including the major Marvel phases (Phase 1, Phase 2, etc) as annotations or markers could also add context to the timeline, as Marvel is known for these distinctive phases and movies that correlate with these phases. A simplified approach could also be using stacked bars to maintain the focus on a few specific metrics and comparing them with one another, with the option to select multiple metrics to create each bar.

*Primary Audience:* The primary audience for this visualization are 1. Marvel Fans and Movie Enthusiasts, 2. Industry Professionals and 3. Academics/Students. The first category of people could be fans who are interested in understanding the financial success of their favorite Marvel movies and how each one performed relative to the other, as well as seeing which movies were the most profitable and how their favorite franchises stack up over time. The second could be professionals in the entertainment industry, such as movie producers, marketers, and financial analysts, who need insights into profitability trends, ROI, and how different Marvel sub-franchises perform. The visualization could help stakeholders understand the financial dynamics of blockbuster movies and guide investment decisions in future projects. The third could be those studying business, media economics/management, etc.

The graph is visually engaging, with color-coded franchises making it easy for viewers to identify their favorite movies. The use of ROI and budget data provides industry professionals with insights into financial efficiency and the visualization helps identify temporal trends. The breakeven line is also a helpful visual anchor that distinguishes movies. The labeling of movie titles next to data points also reduce the need to guess which data belongs to which movie, making it effective overall. Some challenges could be the overlapping data points (especially around the breakeven line or movies released in the same year) may make it harder to extract insights quickly as well as the oversaturation of information.
Overall, the visualization is partially effective for reaching its intended audiences. It is engaging and easy to follow but could be enhanced by reducing clutter.

*Final Thoughts:* Stephen Few's method focuses on universal principles but doesn't always account for the intended audience’s unique needs or expertise. For instance, fans might prioritize visual storytelling and entertainment, while industry professionals might prioritize financial details and interactivity. It also does not evaluate the interactivity of a visualization, which is especially relevant in modern, dynamic tools. One recommendation could be to improve the layout to reduce clutter and overlapping labels. The overlapping data points and labels make it hard to read the visualization, particularly for movies released in the same year or with similar profitability. A change for this could be using a stacked bar chart and colors for each segment to visually distribute and compare the data between movies in a better way. This change, along with having the interactivity feature of changing how many dimensions the viewer is seeing at a specific time would also enhance the overall visual.

Another recommendation could be using a diverging color scale to represent the profitability or budget of the film to make it more visually intuitive. This would make it easier for viewers to compare movies’ financial performance at a glance, regardless of the franchise, and reduce reliance on the legend for interpretation.

## Part 3: Sketching Solutions

In developing a solution to this dataviz, I brainstormed a few different solutions, keeping in mind my current skillset and applications available. 


## Part 4: Testing the Solution

| Question | Interview 1: Female, Mid 20's | Interview 2: Female, Mid 20's |
|----------|-------------|-------------|
| Can you tell me what you think this is?|             |             |
| Can you describe to me what this is telling you?|             |             |
| Is there anything you find surprising or confusing?|             |             |
| Who do you think is the intended audience for this?|             |             |
| Is there anything you would change or do differently?|             |             |

*Synthesis:*

_What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign._

## Part 5: Building the Final Solution


_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._

