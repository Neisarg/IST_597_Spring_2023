# Project Ideas

Remember when picking a project make sure there is enough data; usually a sample count of >100k is good enough for deep learning projects. 

- Projects by students who took the DL course in Stanford - [https://cs230.stanford.edu/past-projects/](https://cs230.stanford.edu/past-projects/) - this is a great source for projects ideas and datasets. We are sharing these for inspiration. These are projects by other students which might motivate you and help you explore.
    - DO NOT COPY PROJECT REPORTS FROM HERE. We run plagiarizers and you do not want to get caught.
- **ASL dataset -** [https://www.kaggle.com/datasets/grassknoted/asl-alphabet](https://www.kaggle.com/datasets/grassknoted/asl-alphabet) ;  Train ViT  on this and report results - [https://www.kaggle.com/datasets/datamunge/sign-language-mnist](https://www.kaggle.com/datasets/datamunge/sign-language-mnist) more
- Classification on the **YELP dataset** - [https://www.kaggle.com/datasets/yelp-dataset/yelp-dataset](https://www.kaggle.com/datasets/yelp-dataset/yelp-dataset)
- **Fake news detection** - [https://paperswithcode.com/datasets?task=fake-news-detection](https://paperswithcode.com/datasets?task=fake-news-detection)
- **Summarization** - [https://github.com/allenai/scitldr](https://github.com/allenai/scitldr) ; [https://paperswithcode.com/datasets?q=summarization&v=lst&o=match](https://paperswithcode.com/datasets?q=summarization&v=lst&o=match) ; [https://huggingface.co/datasets?task_categories=task_categories:summarization&sort=downloads](https://huggingface.co/datasets?task_categories=task_categories:summarization&sort=downloads)
- Find more datasets here - [https://huggingface.co/datasets](https://huggingface.co/datasets)

Some suggestions for the students - 

1. For the course please start with an existing dataset. DO NOT TRY TO BUILD A DATASET. We respect your passion but one semester is not enough for building a good dataset and experimenting comprehensively on it. We would like you to focus on methods and implementation in this course.
2. **GPU Resources;** Most probably you will need a GPU for your project. Remember deep learning is an empirical study so iterating again and again is a part of the “science”. This means you will have to run multiple experiments with different parameters and keep a track of them (see - [https://wandb.ai/site/pricing](https://wandb.ai/site/pricing)). Try running your model on Google Collab with less parameters. 
    1. Google cloud platform will give students $300 in credits, which is more than enough for the course if used wisely. 
    2. AWS credits for research [https://aws.amazon.com/government-education/research-and-technical-computing/cloud-credit-for-research/](https://aws.amazon.com/government-education/research-and-technical-computing/cloud-credit-for-research/)
    3. Consider Google Colab - $10 per month
    4. Consider [https://www.paperspace.com/gradient](https://www.paperspace.com/gradient) - $8 per month - better than Google IMO
    5. Kaggle 
    6. Hugginface spaces - [https://huggingface.co/pricing](https://huggingface.co/pricing) 
3. **Training models**: 90% of the time you wont have to train a model from scratch. Using existing weights and models should be your first move. Always establish a strong baseline before jumping to the best model in existence. 
4. For the **proposals** please answer these questions in detail - [https://www.darpa.mil/work-with-us/heilmeier-catechism](https://www.darpa.mil/work-with-us/heilmeier-catechism) ; This will give both you and us a good idea of what you are trying to do and how. 
5. GPT3 - OpenAI gives $18 free credits for GPT3. If you want to build an application instead of training your models this is a great way of just linking API calls together and have access to the most powerful generative LLM out there. You can even fine-tune GPT3 on your dataset and get state-of-art in a day. 
6. For application based projects - consider few-shot and zero-shot classifiers if you do not have a labelled dataset.