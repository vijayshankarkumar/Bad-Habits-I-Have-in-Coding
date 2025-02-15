# Bad Habits I Have in Coding

### Listing all the bad coding habits I have so that I can read them again and again to get rid of them.

#### 1. Whenever I come across a situation where I need a container of pairs and specially want them to be sorted, I usually define it as ```set<pair<int, int>>```. However, as soon as I need ```lower_bound``` on this set, I realize that using ```map<int, int>``` would make my life much easier.
