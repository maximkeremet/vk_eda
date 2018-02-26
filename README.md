# vk_eda
This is a try out investigation of how frequent people post in VK and is there any difference between those who post a lot and post less.


First, we identify the scope of the investigation as my friends ids and then collecting their fiends ids, getting the friends with depth of 2, as an initial scope for collecting data.
One can find here helpful functions to download data for analyis id-wise.

Then, we retrieve open acess information that we can grap, uisng [VK API](https://vk.com/dev/openapi) methods and process them into a proper format for futher analysis.

Further on we dive into an EDA of available data, trying to identify if there any difference between those who post frequently and post rare. In the end of this section we also compile manually male/female portraits of requent and low-posters.

Lastly, we attempt to make a classifier to predict if the person shall be a frequent-poster either a low-poster.

Check out the EDA [here](http://nbviewer.jupyter.org/github/maximkeremet/vk_eda/blob/master/vk_task_v3.ipynb).

All data is retrieved via [VK API](https://vk.com/dev/openapi) and is open-access, so no sensitive information was fetched.
