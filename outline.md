# Digital Twin Survey Paper Outline

## General Digital Twin Description

A digital twin is a digital representation of a physical object

Generally, a digital twin consists of three main components:

1. The physical object
1. The digital representation
1. Channel which links the physical and digital spaces together

Digital twin relies on a two-way flow of information between these virtual and physical spaces. Essentially the virtual space leads to changes in the physical space and changes in the physical space lead to changes in the virtual. However, this concept leads to very different implementations and requirements across industries.

Analysis of some related survey papers indicates that information management is still a massive challenge for digital twin technology. Specifically in regards to the areas of data fusion, quality, storage, security, and communication between the virtual and physical components.

Digital twin has seen the most popularity in the manufacturing industry, where the technology is a driving force of Industry 4.0 efforts. However, the benefits and applications of digital twin can be seen in many more industries. In this paper, digital twins across the aerospace, manufacturing, construction, education, energy, information technology, marine, and transportation industries will be considered.

I am going to look at digital twim implementations across multiple industries and compare their methods of addressing the following information management challenges, identifying areas that can be adapted to multiple industries, summarizing the currently open issues related to these challenges, and discussing future research directions.

![digital twin](image.png)

## related surveys

To the best of my knowledge, a comprehensive survey specifically focusing on how industries are addressing information management challenges has not yet been addressed previously.

## Information Management Challenges

1. Data fusion
1. Data quality
1. Data storage
1. Data security and governance
1. Data communication

## Industries considered

1. Aerospace/Aviation
1. Manufacturing
1. Construction
1. Education
1. Energy (Electricity)
1. Information Technology (IT)
1. Marine
1. Transportation

## Methodology

How am I selecting my sources?
Papers from IEEE or ACM journals discussing digital twin implementations in their abstracts
Further evaluation is conducted to determine the industry being contributed to and whether the paper has a comprehensive discussion about one or many of the information management challenges being investigated.
create a table that outlines discussions for these challenges

## FIRST ATTEMPT

### Abstract

A digital twin is an accurate digital representation of a physical object, offering significant benefits in areas such as product development, process optimization, and verification and validation testing for many industries. The basis of a digital twin relies on a two-way flow of information between the virtual and physical spaces. The specific requirements of this information flow varies depending on application and industry. However, a digital twin oftentimes has to process vast amounts of heterogenous data coming from physical and digital sources. This leads to many challenges surrounding information management in a digital twin, such as data fusion methods, big data storage, data quality analysis, data transmission, and data security. This paper provides a review of how different industries are addressing these challenges in digital twins and aims to provide direction for further developments in this field.

### Introduction

Digital twins have applications in many different industries, ranging from being a crucial to the goals of Industry 4.0 and smart manufacturing to optimizing retail supply chains \cite{singh_applications_2022}.

Generally, a digital twin consists of:
\begin{enumerate}
\item physical space or component
\item digital representaion of the physical space
\item A channel which facilitiates the feedback loop between the physical and digital mediums
\end{enumerate}

% highlight what would be the complete, ideal digital twin

The authors of \cite{singh_applications_2022} rigorously detail the advantages and applications of digital twins across 13 different industries, but notes that digital twins still suffer from common shortcomings of a novel technology such as high development costs, lack of standardization, and security concerns.

In \cite{boyes_digital_2022}, the researchers identified information management as a chief concern for digital twim implementations, emphasizing the need for methods to ensure data quality. Furthermore, \cite{}

### Challenges

My research has identified information management to be the biggest bottleneck for digital twin implementations across multiple industries. Within this bottleneck, five main challenges were identified: data fusion, data storage, data quality, data communication, and data security.

A digital twin is an accurate digital representation of a physical object, a concept that has recently recently become feasible due to sufficient advancements in the technologies that enable it. As a result, digital twin research has seen an exponential increase in the last decade.
Originally, digital twin was envisioned as a means for optimizing product lifecycle management, primarily utilized by the manufacturing industry to enable the goals of Industry 4.0. However, through this research, many more applications across a wide range of industries were discovered \cite{mihai_digital_2022} \cite{singh_applications_2022} \cite{b_heluany_survey_2023}.

Generally, digital twins rely on a two-way flow of information between the physical and virtual spaces, as illustrated in figure \ref{digital_twin}.
Essentially, the changes in the virtual space will lead to changes in the physical, and changes in the physical space leads to changes in the virtual. Thus, the basic general architecture of a digital twin can be defined as follows:
\begin{enumerate}
\item The physical object or space
\item A digital representation of the physical space
\item A communication channel that links these spaces together
\end{enumerate}
