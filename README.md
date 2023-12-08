# MIA Wiki

[中文](./README-zh_CN.md)  [English](./README.md)
Welcome to **MIA Wiki**.

**MIA** (Medical Image Analysis) represents the intersection of artificial intelligence and medical imaging, a rapidly evolving field. As AI technology advances, medical image analysis plays an increasingly vital role in enhancing diagnostic accuracy and accelerating disease detection.

The realm of **MIA** is broad and the pace of technological advancement is swift. Beginners often face the challenge of systematically learning about this field. Existing resources are frequently scattered and complex, requiring significant time and effort to comprehend and integrate.

To aid enthusiasts in getting started with **MIA**, the **MIA Wiki** made its first commit on GitHub in 2023. As the content has been enriched over time, **MIA Wiki** has garnered increasing attention from enthusiasts in the medical and AI communities, attracting more like-minded individuals to join.

As a free knowledge platform, **MIA Wiki** focuses on the application of AI in medical image analysis. It provides detailed introductions to relevant knowledge and technologies, assisting beginners in understanding and learning about this field.

Currently, **MIA Wiki** primarily includes basic knowledge about medical image analysis and is actively working to enhance the following areas:

- Advanced knowledge in medical image analysis
- Classic case studies in the field of medical image analysis

For more details on the ongoing and planned content, please visit **MIA Wiki's** [Projects](https://github.com/MIA-wiki/MIA-wiki/projects).

Moreover, while rooted in medical image analysis, **MIA Wiki** is not limited to this area. In the future, **MIA Wiki** will also:

- Introduce tools related to medical image analysis
- Integrate more with practical medical scenarios

Considering the following principles:

- Knowledge should be shared in an open manner.
- Medical and AI technologies are constantly evolving, and older techniques may not suffice against new challenges.

In conclusion, **MIA Wiki**, born from the community as an **independent organization**, advocates for **freedom of knowledge**. It will remain non-commercial and maintain its **independent and free** nature in the future.


## How to build？

MIA Wiki uses [mkdocs](https://github.com/mkdocs/mkdocs) to show its contents. And it is deployed at [https://MIA-wiki.org](https://MIA-wiki.org).

It can also be deployed locally, with the following steps:

```shell
# 1. clone
git clone https://github.com/MIA-wiki/MIA-wiki.git
# 2. requirements
pip install -r requirements.txt
# generate static file in site/
python3 scripts/docs.py build-all
# deploy at http://127.0.0.1:8008
python3 scripts/docs.py serve
```

**A local instance of mkdocs is dynamically updated, for instance when a markdown file is modified, the corresponding page will be modified too.**

If you just want to view it statically, try Docker!

```
docker run -d --name=MIA-wiki -p 4100:80 MIAwiki/MIA-wiki
```
And then access [http://localhost:4100/](http://localhost:4100/) .

## How to practice？

Firstly, learn some basic security knowledge through online reading.

Secondly, MIA Wiki has two sister projects.

- All of the challenges that are mentioned are in the [MIA-challenges](https://github.com/MIA-wiki/MIA-challenges) repository, you can locate them with their corresponding category.
- The tools mentioned in the MIA Wiki are constantly added to the [MIA-tools](https://github.com/MIA-wiki/MIA-tools) repository.

## How to make MIA Wiki Better？

We welcome to write content for the wiki and share what you have learned. 

**Before you decide to contribute content, please read [CONTRIBUTING](https://MIA-wiki.org/en/contribute/before-contributing/)**.

Thank you to all the people who have already contributed to MIA Wiki.

<a href="https://github.com/MIA-wiki/MIA-wiki/graphs/contributors"><img src="https://opencollective.com/MIA-wiki/contributors.svg?width=890&button=false" /></a>

## What can you get?

- Ability to learn new things quickly
- Different ways of thinking
- A love for solving problems
- Interesting security techniques
- Memorable and enriching experience

Before reading the Wiki, we hope to give you some advice:

- Learn to ask [smart-questions](http://www.catb.org/~esr/faqs/smart-questions.html) .
- Learn to use Google Search for self-improvement.
- Be good at least one programming language, such as Python.
- Practice is the most important learning tool.
- Maintain the passions and desire to learn about new techniques.

The security circle is small and the areas of exploration is vast. Let's get started with **MIA Wiki**!
