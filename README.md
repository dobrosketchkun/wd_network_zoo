# Wisketchy Dobrov's collection of pretrained StyleGAN2-ada-pytorch compatible networks

Here you can see some of my network, based on ffhq one. Use them as you please.
Links are in the [json file](https://raw.githubusercontent.com/dobrosketchkun/wd_network_zoo/main/wd_networks.json).

# NeuralKuvshinov2 

In order to make a dataset, I downloaded the whole instagram of [Ilia Kuvshinov](https://www.instagram.com/kuvshinov_ilya/) with [instaloader](https://instaloader.github.io/) and, using some automation pull out all the faces.

![NeuralKuvshinov2 ](https://raw.githubusercontent.com/dobrosketchkun/wd_network_zoo/main/files/nkv2_v3.jpg)

# Idols

For some project, I needed an average Japanese idol likeness, so I fetched some sites with said people, aligned and cropped the faces (basically everywhere you see a face, I used this step unless explicitly stated I'm not, so I will omit to mention it) 

![Idols](https://raw.githubusercontent.com/dobrosketchkun/wd_network_zoo/main/files/idols_v5.jpg)

# Asian heritage

Honestly, I just wanted to see if it can be done, but this and two following networks can be used for lowering an unrepresentative bias in human face datasets.
Basically, I used [FairFace](https://github.com/dchen236/FairFace) to filter what I wanted.

![Asian heritage](https://raw.githubusercontent.com/dobrosketchkun/wd_network_zoo/main/files/asian_v1.jpg)

# African heritage

The same as previous

![African heritage](https://raw.githubusercontent.com/dobrosketchkun/wd_network_zoo/main/files/black_v1.jpg)

# Indian heritage

The same as previous

![Indian heritage](https://raw.githubusercontent.com/dobrosketchkun/wd_network_zoo/main/files/indian_v1.jpg)

# 10-19 yo
Like the asian heritage one this can be used to lower age bias in dataset.

![10-19 yo](https://raw.githubusercontent.com/dobrosketchkun/wd_network_zoo/main/files/10-19.jpg)


# NeuralKuvshinov1

This is the first attempt to make a network to generate Ilia Kuvshinov's art. In this particular instance, I manually filter what I think is suitable for this network to learn on.

![NeuralKuvshinov1](https://raw.githubusercontent.com/dobrosketchkun/wd_network_zoo/main/files/nkv1_v27.jpg)

# Ava's Demon

Some fun little project about a particular [webcomic](https://www.avasdemon.com/).

![Ava's Demon](https://raw.githubusercontent.com/dobrosketchkun/wd_network_zoo/main/files/avasdemon_v1.jpg)

# Archillect

Wanting something surrealistic I used the [Archillect](https://www.instagram.com/archillect/?hl=en) instagram as a source for the dataset. I downloaded it whole and padded all images to a square.

![Archillect](https://raw.githubusercontent.com/dobrosketchkun/wd_network_zoo/main/files/archillect_v22.jpg)

# Liminal

A subset of the archillect network. I trained the previous network on a dump of the [/r/LiminalSpace](https://www.reddit.com/r/LiminalSpace) subreddit.

![Liminal](https://raw.githubusercontent.com/dobrosketchkun/wd_network_zoo/main/files/liminal_v1.jpg)


# K-pop

Nightmarish failed experiment, for some reason, I tried to use a raw dataset of random frames from [k-pop videos](https://www.youtube.com/channel/UCaO6TYtlC8U5ttz62hTrZgg/videos). Don't ask why.

![K-pop](https://raw.githubusercontent.com/dobrosketchkun/wd_network_zoo/main/files/kpop_v1.jpg)
