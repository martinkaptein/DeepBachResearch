# DeepBachResearch

A fork of the [original DeepBach](https://github.com/Ghadjeres/DeepBach) (which can be found [here](https://github.com/Ghadjeres/DeepBach)) **with exactly the version and adjustements I have used for my bachelor research at the ArtEz conservatory in Zwolle, The Netherlands**.

The research paper can be found on my website. [Here](https://www.martinkaptein.com/files/research_bach_mk_2019.pdf) is the direct link to it.

# Instructions

Python 3 with Pip3 is required. The exact version can be found in requirements.txt file.

```
git clone https://github.com/martinkaptein/DeepBachResearch.git
cd DeepBach
sudo pip3 install -r requirements.txt
```
# Adjustements

The adjustments, I am talking about in my research paper can be invoked in the following way:

## Version 1

`deepBach.py -b 64 -s 250 --validation_steps 10 -d 100 -i 10000 -t 10 -l 100 -o research-output/version1.mid`

## Version 2

`deepBach.py -b 128 -s 500 --validation_steps 20 -d 200 -i 20000 -t 15 -l 100 -o research-output/version2.mid`

## Version 3

`deepBach.py -b 128 -s 500 --validation_steps 30 -u 500 500 -d 300 -i 40000 -t 15 -l 100 -o research-output/version3.mid`
