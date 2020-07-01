# AI Design Papers

## 📃Paper

| Name | Title | Description | Publication | Links |  
| --- | --- | --- | --- | --- |  
| LayoutGAN | LayoutGAN: Generating Graphic Layouts with Wireframe Discriminators | 提出了一个可以生成Layout的GAN模型。 | ICLR 2019 |  [[paper](https://arxiv.org/pdf/1901.06767.pdf)] [project] [[note](...)] |  
| ManiGAN | ManiGAN: Text-Guided Image | 用文字来指引图像的修改。 | CVPR 2020 |  [[paper](https://arxiv.org/abs/1912.06203)] [[project](https://github.com/mrlibw/ManiGAN)] [[note](...)] |  

## 🎯Dataset

| Name | Title | Description | Scale | Annotation | Links |  
| --- | --- | --- | --- | --- | --- |  
| AVA | AVA: A large-scale database for aesthetic visual analysis | 一个大规模图像美学数据集。 | 250,000+ | aesthetic scores for each image, semantic labels for over 60 categories as well as labels related to photographic style |  [[paper](http://refbase.cvc.uab.es/files/MMP2012a.pdf)] [project] [[note](...)] |  


## Contribute to AI Design Papers  

1. Click the `Fork` button on the top of this repo  

2. Clone your repo to local  

```shell
git clone https://github.com/yourusername/ai-design-paper.git
```

3. Add your notes  

>Add your findings in the corresponding folders using `markdown`. You need to make sure following things:
>
>1. Use template in each folder. E.g., you add a new dataset, use `dataset\template.md`.
>2. The `name` of the md file is the nickname of the paper.
>3. Your md file must include `Brief Information` part as shown in the templates in each folders.

4. Commit your update and push to your repo  

5. Pull Request

### ⚠Notice

>### make sure you are up to date
>
>You don't need to do this every time, but you need when original repo updates.
>
>#### Configure `upstream`
>
>**Notice**: You don't need to configure again if you have done it.
>
>1. List the current configured remote repository for your fork. You should only see `origin`.
>```shell
>git remote -v
>```
>
>2. Specify a new remote `upstream` repository that will be synced with the fork.
>```shell
>git remote add upstream https://github.com/tezignlab/ai-design-papers.git
>```
>
>3. Verify the new upstream repository you've specified for your fork. You should see both `origin` and `upstream`.
>```shell
>git remote -v
>```
>
>#### Sync your fork
>
>1. Fetch the branches and their respective commits from upstream repo.
>```shell
>git fetch upstream
>```
>
>2. Check out your fork's local master branch.
>```shell
>git checkout master
>```
>
>3. Merge the changes from upstream/master into your local master branch.
>```shell
>git merge upstream/master
>```
>