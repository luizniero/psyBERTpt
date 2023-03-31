# psyBERTpt
psyBERTpt: A Clinical NER model specialized in psychiatric health notes

psyBERTpt is one of the few language models for clinical NER available in Portuguese, such as BioBERTpt PUC models.

HuggingFaceAPI: https://huggingface.co/psybertpt/psyBERTpt/

psyBERTpt is a NER model built from the fine tuning of BERT-portuguese-large-cased.

psyBERTpt used, in the fine tuning stage, a corpus composed of 300 medical records of admission to a specialized psychiatric hospital, which was annotated by 5 doctors and nurses specialized in psychiatry in the following NER categories:

- Self-Destructive Behavior
- Diagnosis
- Drug
- Pharmaceutical
- Psychic Function
- Family History
- Patient History
- Observation
- Symptom and Psychological Complaint

psyBERTpt achieved a precision of 0.65, recall of 0.69 and f1-score of 0.67.

The scientific article that presents the psyBERTpt is waiting to be published =)

My thanks to everyone who was part of this project:

- Ms. Luiz Henrique Pereira Niero (me) (luiz.niero@unesp.br)
- Prof. Dr. Ivan Rizzo Guilherme (ivan.guilherme@unesp.br)
- Prof. Dr. Lucas Emanuel Silva e Oliveira (kunkaweb@gmail.com)
- Prof. Dr. Gerardo Maria de Araújo Filho (gerardo.filho@famerp.br)
- Dr. Gabriel
- Enf. Giovanna Favareto
- Dra. Leisa
- Dra. Loíse
- Hospital Dr. Adolfo Bezerra de Menezes
