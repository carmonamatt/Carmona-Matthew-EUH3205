---
layout: default
title: Introduction
number: 1
---
# Introduction


This is where you introduce your project to your audience. You should summarize briefly the topic you are working on. (250-350 words)
This is Matthew trying out the website configuration 
The following is sample text to show the capabilities of presenting text with various formatting (such as bold), different languages, adding footnotes, and images.[^1] [^2] 

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'General Napoleon in the Council of the Five Hundred'" %}
{% include media.html pages=media %}


After the coup of 18 Brumaire, Napoleon took control of the Directory of France, and soon after started styling himself as consul-for-life. Born from minor nobility on Corsica, Napoleon would be sent to military school in Paris as the French Revolution began. The revolution itself would have a profound effect on Napoleon, shaping his views on liberty, republicanism, legal codes, and the military. Seeing the potential of a new society based on rational thought and merits, Napoleon would be one the revolution’s foremost champions with him even joining the Corsican Jacobins. In his justification on the coup of 18 Brumaire, he claims that he had acted only to preserve liberty and the republic from internal enemies. It is from the understanding of his desire to carry on the will of the revolution and to defend France from all enemies foreign and domestic that we can truly begin to see what Napoleon’s effects on Europe were. For him to truly bring peace and stability to France, and to spread the ideas of the revolution abroad, he argued that the only way to accomplish it was to bring other nations to heel. From here, the reason why Napoleon was able to have such an impact on Europe, as compared to say the French Revolution, was because he was able to conquer and oversee the administrations of other nations. So even long after his defeat, the radical new changes he instilled on other nations persisted even against the wishes of the ruling elite. The three most striking and important effects were his social and political changes, his influence on the military, and his influence on nationalism. All these changes could be seen as tools used by Napoleon to impose his ideals, and make sure the countries followed them. 


[^1]: First example footnote. View other pages to see sample methods of working with Markdown.
[^2]: I copied this text from this [website](https://www.lipsum.com/feed/html) 
