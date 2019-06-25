# AIKT-MAIN
This version of AI Knowledge Tree is a brief index of various branches. In order to explore details, you can click the related links. 

In order to have a look at quick start, you can refer to [guide part](#Methods-to-Contribute-to-SFFAI-AIKT).



# Artificial Intelligence Knowledge Tree

- [机器学习（Machin Learning）](https://github.com/SFFAI-AIKT/AIKT-Machine_Learning)
- [计算机视觉（Computer Vision）](https://github.com/SFFAI-AIKT/AIKT-Computer_Vision)
- [自然语言处理（Natural Language Processing）](https://github.com/SFFAI-AIKT/AIKT-Natural_Language_Processing)
- [语音处理（Speech Processing）](https://github.com/SFFAI-AIKT/AIKT-Speech_Processing)
- [计算机图形学（Computer Graphics）](https://github.com/SFFAI-AIKT/AIKT-Computer_Graphics)
- [类脑智能（Brain-inspired Artificial Intelligence）](https://github.com/SFFAI-AIKT/AIKT-Brain-inspired_Artificial_Intelligence)
- [数据挖掘（Data Mining）](https://github.com/SFFAI-AIKT/AIKT-Data_Mining)
- [机器人学（Robotics）](https://github.com/SFFAI-AIKT/AIKT-Robotics)



# [AI Conference Deadlines](https://aideadlin.es/?sub=ML,CV,NLP,RO,SP,DM)

# Related Works

1. [Paper with code](https://paperswithcode.com/)
2. [NLP Progress](https://github.com/sebastianruder/NLP-progress)
3. [State of the art Collection](https://www.stateoftheart.ai/)

---

# [Methods-to-Contribute-to-SFFAI-AIKT](https://github.com/EriCongMa/Publications-of-EriC.MA/blob/master/Blog_Articles/Methods_to_Contribute_SFFAI_AIKT.pdf)

Welcome to contribute the project called Artificial Intelligence Knowledge Tree, Student Forums on Frontiers of Artificial Intelligence (SFFAI AIKT). In order to add content in AIKT project, we strong suggest you to read the instructions as follows. We are trying our best to make it easy for everyong to contribute themselves in this projece. Of course we know there are many talented contributors having their outstanding method to construct a open-resource project. Due to the limited capacity of the originator, ways to contribute to AIKT may not be the optimum solution. As a result, if you have any better plan for contributing to AIKT, please feel free to contact [EriC. MA](mailto:cong.ma@nlpr.ia.ac.cn) by email.

## 1. Initialization

To start contributing, make sure that you have a [GitHub](https://github.com/) account. As we all know, GitHub is a quite popular online platform to collect open-resource codes and projects especially in Computer Science Area. We assure you that contributing yourself in GitHub is a great way to communicate with various outstanding people in CS. Area.

It is pretty easy to sign up an account in GitHub. A valid email is necessary to sign up a GitHub account and the password in GitHub can be different from that in your email.

Imagine that you have already had a GitHub account and we can contiue to do the next step.



## 2. Clone the lastest version of AIKT

Suppose that you are a researcher or a student focusing on Natural Language Processing and you want to contribute to SFFAI_AIKT-NLP, you can clone the repository to your local computer with the following steps.

1. First open the [repository](<https://github.com/SFFAI-AIKT/AIKT-Natural_Language_Processing>) in your browser.
2. Fork the repository.
3. Clone your forked repository

```shell
# Replace <your-github-name> to your GitHub Account name.
# e.g., if your GitHub Account name is EriCongMa, you should type:
# git clone https://github.com/EriCongMa/AIKT-Natural_Language_Processing
git clone https://github.com/<your-github-name>/AIKT-Natural_Language_Processing
```

Aftering cloning the repository in your own computer, you can edit the file in your local computer anytime and anywhere even without a Internet connection. It's quite convenient, right?



## 3. Making Changes

Since you have already copied the repository in your own PC, you can open it in your terminal.

```shell
cd AIKT-Natural_Language_Processing
```

Check the branch that you are in.

```shell
git brach
```

You are in the **<u>master</u>** branch If the output is about '* master'. You can edit the files now. However, you can't to push the changes to GitHub because you don't have permission to change in **<u>master</u>** branch unless you are one of the contributors in this repository. In order to change the file on Github, you need to transfer youself from **<u>master</u>** brach to a sub-brach.

Create a new sub-brach named 'work'.

```shell
# git checkout -b <sub-brach-name> master
git checkout -b work master
```

After doing that, you can check which branch you are in and the ouput should be the sub-brach you have created.

```shell
git branch
```

Then, you can change any file as you want. You can also add new files, new folders. 



## 4. Push changes to GitHub

Suppose that you have already finished changes. It's time to push your contributions to GitHub Web.

To make things easy to say, we imagine that you add a line '*Hello world*' in 'README.md' file.

You can see what you have changed.

```shell
git status
```

The output will show you what you have changed. To add your changes to queue that is wating to be upload to GitHub, you can use the command.

```shell
# add the changes to add queue.
git add .
# raise a commit to clarify what you are going to change.
git commit -m 'Hello_world-change by <your name>'
# Last step in terminal, push your commit to GitHub Web.
git push --set-upstream origin work
```



## 5. Pull Request in your GitHub Website

After doing things as afore mentioned, it's time to open your browser and log in GitHub.

Go and find pull request to pull a request from your branch to **<u>master</u>** branch.



## 6. Waiting to be Merged

The contributors of this project can see your 'pull request' and check whether it has conflicts with the current version and merge it to **<u>master</u>** branch.



### Any question, welcome to contact with sffai_aikt@mustedu.cn