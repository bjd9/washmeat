# Why people wash meat (or don't)


## Dataset

YouTuber (and former public radio reporter) Adam Ragusea asked his viewers in September 2020 to answer a detailed survey about whether (and why and how) they wash meat before cooking it. He received more than 13,000 responses. The data explored and analyzed here is the anomymized data collected.

Data was downloaded and retrieved from [link](https://drive.google.com/file/d/1eygYpBJQGFd4wHH8iYsLoy3PR8PmHN0O/view) on February 26, 2021. The file is a CSV file of responses from a Google Form.

## Summary of Findings

Findings from exploration were organized into 3 categories:
1. About the Respondents
2. Kitchen Practices
3. Safety Practices

*About the Respondents*
  - Demographic/ Background Info on the respondents, including:
    * Gender
    * Country of Origin
    * Country of Residency
    * U.S. State of Residency (if USA)
    * Race
    * Age

*Kitchen Practices*
  - Handling practices of plates, thermometer, cutting board, and  utensils after or while handling raw meat.
  - Washing practices (or not) depending on type of meat

*Safety Practices*
  - Responses in rating home kitchen safety and commercial kitchen safety.


## Key Insights for Presentation

Presentation will focus on kitchen practices and safety practices analysis outlined in the exploratory analysis for the slide deck.

Some of the key insights covered in the slide deck include the following:
  - Background on the demographics of the respondents to the survey. From the data it appears that top demographics include: white, male, in 20s, and from the USA.
  - For kitchen practices, there were two strong observations within the data:
    * Respondents ALWAYS use different plates for handling raw meat and cooked meat
    * Respondents NEVER use the same cutting board without cleaning it with hot soapy water between using it for raw meat or chicken and using it for ready-to-eat food
  - Overall, respondents overwhelmingly said they do NOT wash their meat -- no matter the type. The largest difference between wash and not wash was for ground meat. Fish was the closest with -- but still a significant difference.
  - For a commercial eatery, there was a noticeable pattern of safety being extremely important with '5' being the top choice then a decline to '1'. Meanwhile, when eating at someone's house the top answer was a '4' with '5' and '3' being almost tied for the second most popular answer.

In order to run the slide deck the following should be executed in the terminal:

 jupyter nbconvert --to slides --TemplateExporter.exclude_input=True washmeatexplanatoryslidedeck.ipynb
