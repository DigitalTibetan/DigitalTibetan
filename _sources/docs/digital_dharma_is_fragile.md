# Digital dharma is extremely fragile

Now that we've looked into all the [exciting opportunities](computational_dharma.ipynb) digital technologies provide, here a few words about the dangers:

```{image} https://upload.wikimedia.org/wikipedia/commons/7/72/Braque_Family_Triptych_closed_WGA.jpg
:align: right
:width: 320
```
* If you are working on dharma material, and whatever you are doing is just on your computer, shared with a number friends or some small organization of a few 10000 people, then most of this material we be lost with a probability > 99.999% in a few decades. It will be copied, fragmented and corrupted over time. As a result at some point: **The entire work will be gone.**
* If you rely on proprietary software to store your material (office, databases, cloud-subscriptions, etc.), everything will be gone in less than half a century (at least if you don't have more resources than US government and NASA: Many of the recordings of the space explorations of the 60ties are now inaccessible: neither the machines nor the knowledge is available today to access it). So: **your entire work will be gone.**
* If you believe in secrecy and restrictions of aspects of your dharma material, rest assured that your work will be secret forever: there can't be enough thieves to prevent each person involved to lose the material over time. So either be confident to set up your own aural lineage thus propagating from human to human (in this case this is the wrong site for you), or: **your entire work will be gone.**

## That sounds gloomy! So what can be done?

```{image} https://upload.wikimedia.org/wikipedia/commons/b/bc/Early_writing_tablet_recording_the_allocation_of_beer.jpg
:align: right
:width: 200
```

We still have accounts of the culture of Sumer, because those responsible for digital preservation at 3000BCE used clay tablets. Even the Tibetan woodblocks were far more resilient than almost anything our current technology has to offer in terms of longevity. So what are possible best practices?

### Simplicity & open formats

Dharma content is precious. In order to make it possible to maintain it, **separate between _presentation_ and _information_**. If you say: I need to work with this and that tool, because otherwise it looks bad, then you focus on presentation, and this will make preservation much more difficult long term.

Choose the most simple text format possible for long-term relevant information: an ideal format is human-readable without any additional decoding-tools.

* For text, an ideal choice for many applications is **markdown**
* For structured information use comma-separated text **CSV** based tables
* XML, JSON and similar formats are suitable too, but at a cost of lower direct human accessibility.

Then, if a more embellished output is required, use tools to convert simple text formats into more complex formats. As a last step human editing can be added, but it should be seen like a sand mandala: this will not last.

If the resultant object can be considered as an artistic representation of it's own right, use **PDF-A** (Archive PDF) to store the result.

```{note}
The source-of-truth for any long-term dharma material needs to be as simple as possible: a text-format like markdown or CSV.
```

### Resilience and long-term backups

Individual humans and small or medium sized organizations **do not have the means to guarantee long term backups**.

Once you've made sure that dharma material that needs to be preserved is stored in a format as simple as possible, backups become essential.

- **Sharing** is a way to use everybody else's computer as backup-device. It's probably the _only_ longterm strategy to make sure information survives.
- **Powerful partners** are required to increase chances: by working together with as many organizations as possible and sharing freely between them, the resilience for the material to be protected increases.
- **Longterm backups** are only within in reach of very few organizations. Luckily, if you material is in simple text form, free and open, you have access to the most powerful backup facilities currently available: the [github artic code vault](https://archiveprogram.github.com/): store your information as text in github and (if public and open consisting of reasonably small text files), the repository will be put in cold storage within an Arctic code vault.

```{note}
Carefully evaluate the best possible backup- and distribution strategy for everything that has been established as source-of-truth above.
```
---------------
#### Image references

* Image "The outer panels of Rogier van der Weyden's Braque Triptych (c. 1452) show the skull of the patron displayed on the inner panels. The bones rest on a brick, a symbol of his former industry and achievement" (Public domain, [wikipedia](https://en.wikipedia.org/wiki/Memento_mori#/media/File:Braque_Family_Triptych_closed_WGA.jpg)
* Image "Early writing tablet recording the allocation of beer"; 3100-3000 BC (Late Prehistoric period); height: 9.4 cm, width: 6.87 cm; probably from southern Iraq; British Museum (ME 140855). [wikipedia](https://commons.wikimedia.org/wiki/File:Early_writing_tablet_recording_the_allocation_of_beer.jpg), Creative commons.