---
title: "Paragraph-citation Topic Models for Corpora with Citation Networks"
collection: talks
type: "Talk"
permalink: /talks/pctm
---
Co-authored with ByungKoo Kim and Yuki Shiraito

Abstract: 

Social scientists often analyze a corpus with a citation network among its documents, such as the corpus of the U.S. Supreme Court decisions. Existing topic models for document networks assume that the topic of a citation is the aggregation of the topics of all the words in the same document. However, the context in which citations arise varies within each document. This paper proposes the Paragraph-citation Topic Models (PCTM) to address this issue. In PCTM, citations within a document may have different topics across paragraphs. The topic of each citation is shared by the words in the same paragraph, and the likelihood of citing a previous document depends on the prevalence of the same topic in that document. Therefore, the topic of a citation is inferred from its paragraph and the document it cites. We derive an efficient inference algorithm using the variational method coupled with negative sampling. Using the corpus of the U.S. Supreme Court opinion, our model illustrates that the topic of citations do vary within a document, and the topical similarity as well as the citation popularity of precedents play a critical role in how Justices make citations.
