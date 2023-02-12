<pre>
The Arabic-TOD dataset is based on the BiToD dataset.
Of the 3,689 BiToD-English dialogues, 1,500 dialogues (30,000 utterances) were translated into Arabic.
We translated the task-related keywords such as cuisine, dietary restrictions, and price-level for the
restaurant domain, price-level for the hotel domain, type, and price-level for the attraction domain, day,
weather, and city for the weather domain. We keep the rest of values without translation, like hotels’ and
restaurants’ names, locations, and addresses. These values are real  entities in Hong Kong city (literals),
and most of them contain Chinese words written in English, therefore they have not been translated. According to
the slot-values in the Arabic-TOD dataset, we used the slots names as they are in English and translated their
corresponding values, except the entities in Hong Kong city since the Arabic-TOD dataset supports codeswitching. 

We did not translate the 'UserTask' for all dialogues, since it is not important in developing the system.
It is just as a summarization of the dialogue contents.
</pre>
