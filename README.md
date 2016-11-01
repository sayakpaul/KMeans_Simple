# KMeans_Simple
The difference between supervised and unsupervised machine learning is whether or not we, the scientist, are providing the machine with labeled data.

Unsupervised machine learning is where the scientist does not provide the machine with labeled data, and the machine is expected to derive structure from the data all on its own.

There are many forms of this, though the main form of unsupervised machine learning is clustering. Within clustering, you have "flat" clustering or "hierarchical" clustering.
Now, what can we use unsupervised machine learning for? In general, unsupervised machine learning can actually solve the exact same problems as supervised machine learning, though it may not be as efficient or accurate.

Unsupervised machine learning is most often applied to questions of underlying structure. Genomics, for example, is an area where we do not truly understand the underlying structure. Thus, we use unsupervised machine learning to help us figure out the structure.

Unsupervised learning can also aid in "feature reduction." A term we will cover eventually here is "Principal Component Analysis," or PCA, which is another form of feature reduction, used frequently with unsupervised machine learning. PCA attempts to locate linearly uncorrelated variables, calling these the Principal Components, since these are the more "unique" elements that differentiate or describe whatever the object of analysis is.

There is also a meshing of supervised and unsupervised machine learning, often called semi-supervised machine learning. You will often find things get more complicated with real world examples. You may find, for example, that first you want to use unsupervised machine learning for feature reduction, then you will shift to supervised machine learning once you have used, for example, Flat Clustering to group your data into two clusters, which are now going to be your two labels for supervised learning.

What might be an actual example of this? How about we're trying to differentiate between male and female faces. We aren't already sure what the defining differences between a male and female face are, so we take to unsupervised machine learning first. Our hopeful goal will be to create an algorithm that will naturally just group the faces into two groups. We're likely to go ahead and use Flat Clustering for this, and then we'll likely test the algorithm to see if it was indeed accurate, using labeled data only for testing, not for training. If we find the machine is successful, we now actually have our labels, and features that make up a male face and a female face. We can then use PCA, or maybe we already did. Either way, we can try to get feature count down. Once we've done this, we use these labels with their Principle Components as features, which we can then feed into a supervised machine learning algorithm for actual future identification.
