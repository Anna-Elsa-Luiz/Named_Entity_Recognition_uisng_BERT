<h1><b>Named Entity Recognition (NER)</b></h1>

<p>Named Entity Recognition (NER) is a task of Natural Language Processing (NLP) that involves identifying and classifying named entities in a text into predefined categories such as person names, organizations, locations, and others. The goal of NER is to extract structured information from unstructured text data and represent it in a machine-readable format. Approaches typically use BIO notation, which differentiates the beginning (B) and the inside (I) of entities. O is used for non-entity tokens.</p>

<p>NER extracts the meaningfull information from the unstructured data, basically detecting the entities and using the similary measurement we can take decisions</p>


<p>In this project, I've utilized <a href="https://huggingface.co/bert-base-cased" target="_blank"><b>Hugging Face’s bert-base-cased model</b></a> for named entity recognition (NER). The bert-base-cased model, part of the Hugging Face transformers library, is a pre-trained language model known for its state-of-the-art performance in various NLP tasks. By fine-tuning this model, we can accurately identify and classify entities in the text, such as names of people, organizations, locations, and more.</p>

Refer Jay Alammar blogs : <a href="https://jalammar.github.io/a-visual-guide-to-using-bert-for-the-first-time/">visual guide to using bert for the first time</a>  , <a href="https://jalammar.github.io/illustrated-bert/">illustrated bert</a> 

Vist  <a href="https://paperswithcode.com/task/named-entity-recognition-ner">Named Entity Recognition Papers with code at paperswithcode</a>

For Data annotation and labelling : <a href="https://prodi.gy/">Prodigy </a> , <a href="https://tecoholic.github.io/ner-annotator/">Ner Annotator</a>


<h2><b>Why BERT for NER?</b></h2>
<ul>
  <li><strong>Efficiency and Effectiveness:</strong> BERT models have significantly improved the efficiency and effectiveness of NLP tasks by enhancing the processing and inference of information in a scalable and consistent manner.</li>
  <li><strong>Contextual Understanding:</strong> Unlike previous models that focused on word-level meanings, BERT models understand context by considering the relationships between words in a sentence, leading to more accurate and context-aware results.</li>
  <li><strong>Pre-Trained and Open Source:</strong> BERT models are pre-trained on large corpora of unannotated text and are publicly available, allowing for easy access and utilization by developers for various NLP tasks without the need to train models from scratch.</li>
  <li><strong>Versatility and Adaptability:</strong> BERT's unified architecture enables it to adapt to various downstream tasks with minimal modifications, making it a versatile and highly effective tool for natural language understanding and processing.</li>
  <li><strong>State-of-the-Art Performance:</strong> BERT-based models have achieved state-of-the-art results across 11 NLP tasks, showcasing their superior performance and capabilities in handling a wide range of NLP applications.</li>
  <li><strong>Multilingual Support:</strong> BERT models are multilingual and can be fine-tuned for any language, making them suitable for diverse linguistic tasks and applications.</li>
</ul>


<h2><b>Implementation</b></h2>

<ul>
  <li><strong>Data Ingestion:</strong> Utilized Google Cloud Platform (GCP) for data storage and retrieval.</li>
  <li><strong>Data Preprocessing:</strong> Used an already annotated dataset for training and validation.</li>
  <li><strong>Model Training:</strong> Fine-tuned the bert-base-cased model on the annotated dataset for named entity recognition (NER).</li>
  <li><strong>Model Evaluation:</strong> Evaluated the fine-tuned model's performance using precision, recall, and F1 score metrics.</li>
  <li><strong>Model Deployment:</strong> Deployed the trained model in a production-grade environment using CircleCI for continuous integration and continuous deployment (CI/CD).</li>
  <li><strong>API Development:</strong> Developed a RESTful API using FastAPI to serve the NER model predictions.</li>
  <li><strong>Monitoring and Logging:</strong> Implemented logging and exception</li>
  <li><strong>Documentation:</strong> Created comprehensive documentation for the project setup, usage, workflow and flowcharts.</li>
</ul>


<h2>Project Overview : Business Perspective</h2>


<h2>Complete Project Setup and Workflow</h2>


<h2>Flowchart</h2>
**To be completed** 



