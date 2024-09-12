# Índice

- [Ir a la Introducción](#sección-1-introducción)
- [Ir a la Conclusión](#sección-2-conclusión)

## Sección 1: Introducción

Este es el contenido de la introducción.

## Sección 2: Conclusión

Este es el contenido de la conclusión.


## Table of Contents

- [Índice](#índice)
  - [Sección 1: Introducción](#sección-1-introducción)
  - [Sección 2: Conclusión](#sección-2-conclusión)
  - [Table of Contents](#table-of-contents)
- [Using Plastilinn](#using-plastilinn)
    - [Plain Text](#plain-text)
    - [Markdown](#markdown)
    - [Local Storage](#local-storage)
  - [Structured Business Model](#structured-business-model)
  - [Editing Your Plastilinn Doc](#editing-your-plastilinn-doc)
  - [Using Markers](#using-markers)
  - [Export Content](#export-content)
  - [xBoK](#xbok)
  - [Artifacts](#artifacts)
    - [Idea Definition Canvas](#idea-definition-canvas)
    - [Lean Canvas](#lean-canvas)
    - [Business Model Canvas](#business-model-canvas)
    - [Empathy Map](#empathy-map)
    - [Think \& Feel](#think--feel)
    - [Hear](#hear)
    - [See](#see)
    - [Say \& Do](#say--do)
    - [Pain](#pain)
    - [Gain](#gain)
    - [Value Proposition Canvas](#value-proposition-canvas)

# Using Plastilinn

[Plastilinn app](https://xbokmd.github.io/plastilinn/app.html)

[GitHub](https://github.com/xbokmd/plastilinn)

In Plastilinn, everything revolves around your Plastilinn doc, which is a single document containing your entire business model.

A business model is a simplified representation of the logic that makes a business profitable. That is, your business model is captured in your Plastilinn doc, which is a document that gathers all relevant information about your business. It includes information about who your customers are, what problems you help them solve, what channels you will use for them to get to know you, etc.

A Plastilinn doc is simply a plain text file in Markdown format.

### Plain Text

Plain text files are the simplest files and can be edited with any text editor. All operating systems come with a default plain text editor (for example, Notepad on Windows), so by using this file format, we ensure it is always editable regardless of the operating system or environment used by the user. You can edit it on Windows, Mac, Linux, etc.

### Markdown

Markdown is a lightweight markup language designed to be easy to write and read. It is characterized by its simplicity, allowing users to format text using a series of simple symbols and characters, such as asterisks for bold and underscores for italic, among others. The great advantage of Markdown is that it allows you to focus on the content of the text without distractions, making it easy to create well-structured and readable documents both in their raw form and in their final version, once converted to HTML or other formats. This makes it especially popular for writing technical documentation, README files in software projects, and for content creators on blogging platforms and content management systems seeking an efficient and accessible way to write.

### Local Storage

Your document is saved on your hard drive like other documents you work with. Inside your "Plastilinn" folder on your hard drive, both the current version of your document and previous versions are stored. Other tools similar to Plastilinn operate with a software-as-a-service (SaaS) model, where your information is stored in a cloud database and controlled by the service provider. This means you are tied to them, and you may lose access to the information you've created if they decide to increase prices, you want to stop paying for the service for any reason, or the service provider goes out of business.

## Structured Business Model

A Plastilinn doc allows you to describe your business model in a structured manner. You could describe your business model simply by writing a narrative document (as if it were a novel) that outlines the logic through which your business makes money. However, in that format, you cannot leverage the information effectively. Instead, in Plastilinn, your business model is described using a predefined structure, which uses the following components:

| Type | Examples: 🆔Element, 📖description and (example of Space X)|
|------------|-------------------------------------------------------|
| **Section** Content units that describe specific aspects of the business model. | **Mission:** Fundamental purpose of the organization ("Make human life multi-planetary")<br>**Profile Satellite Launch Customers - Goals:** Problems, needs, or desires of the relevant stakeholders for the business. (Reduce launch costs, Increase launch reliability, Expand global satellite internet coverage.)<br>**Revenue Lines:** Sources of income generated by the business. (Commercial launches, Contracts with government agencies, Starlink internet services.)|
| **Class** Elements representing key concepts or components within the business model. | **Key:** Critical elements for success. (Reusable rocket technology)<br>**Solution:** Offered solutions. (Starship for Mars missions)<br>**Offering:** Value proposition. (Launch services for satellites and payloads into space) |
| **Marker** Indicators or notes that help evaluate, classify, or prioritize components of the business model. | **Weight:** Importance of components. (Reusable rocket technology has a weight of "*****")<br>**Priority:** Urgency of development. (Starship development has a priority of "!!!!!")<br>**Certainty:** Reliability of the component. (Feasibility of reusable rockets is marked with "=")|
[Plastilinn documentation](https://xbokmd.github.io/plastilinn/index.html#/)

## Editing Your Plastilinn Doc

You can edit your Plastilinn doc directly in the application <a href="https://stackedit.io/app#" target="_blank">Stackedit</a>

## Using Markers

| marker | low | high |
| --- | --- | --- |
| weight | <span data-tag='*'>*</span><kbd class='kbd kbd-xs'>#*</kbd> | <kbd class='kbd kbd-xs'>#*****</kbd> <span data-tag='*****'>*****</span> |
| completion | <span data-tag='>'>></span><kbd class='kbd kbd-xs'>#></kbd> | <kbd class='kbd kbd-xs'>#>>>>></kbd> <span data-tag='>>>>>'>>>>>></span> |
| priority | <span data-tag='!'>!</span><kbd class='kbd kbd-xs'>#!</kbd> | <kbd class='kbd kbd-xs'>#!!!!!</kbd> <span data-tag='!!!!!'>!!!!!</span> |
| uncertainty | <span data-tag='?'>?</span><kbd class='kbd kbd-xs'>#?</kbd> | <kbd class='kbd kbd-xs'>#?????</kbd> <span data-tag='?????'>?????</span> |
| risk | <span data-tag='¡'>¡</span><kbd class='kbd kbd-xs'>#¡</kbd> | <kbd class='kbd kbd-xs'>#¡¡¡¡¡</kbd> <span data-tag='¡¡¡¡¡'>¡¡¡¡¡</span> |
| validation | <span data-tag='='>=</span><kbd class='kbd kbd-xs'>#=</kbd> | <kbd class='kbd kbd-xs'>#=====</kbd> <span data-tag='====='>=====</span> |

## Export Content

At any time, you can export your document as HTML by clicking the "export" button in the upper right corner. Your document will be exported as clean HTML that you can open, import, or copy and paste into your favorite document editor (MS Word, Google Docs, etc.). The following <a href="https://drive.google.com/drive/folders/1IbMu1j6hqWG0BLllePYftHpzubjxCEQy?usp=sharing" target="_blank">link opens a Google Drive folder where you can view a sample of all these documents</a>.

## xBoK

The metamodel describes the structure and essential elements that should be considered when designing and analyzing business models. This structure includes components such as "key", "organization", "journey", "assumption", "solution", "offering", and many more, each with its own symbol, color, and detailed definition. These elements cover a wide range of critical aspects of a business, from key resources and activities to value propositions, customer segments, and relationships with them.

For example, the term "key" refers to the essential components that are crucial for the business's success, such as resources, activities, partners, or key value propositions. "Organization" refers to the structure and arrangement of the company, encompassing how tasks, responsibilities, and resources are distributed and coordinated. "Journey" describes the process or path a customer follows from becoming aware of a product or service to making a purchase and beyond.

Additionally, the metamodel includes "markers" that allow you to rate aspects such as importance, completion, priority, certainty, and risk of different building blocks of the business model. It also includes sections that address the business summary, business idea, opportunities, inspiration behind the model, current state of the business, challenges, unfair advantages, business objectives, mission, vision, strategy, organizational values, and more.

This metamodel is a comprehensive tool designed to facilitate in-depth analysis and the construction of robust and well-founded business models, considering all key aspects that can influence their success and sustainability in the market.

## Artifacts

### Idea Definition Canvas

This guide will help you outline your business idea in Plastilinn at a very high level.

1. #### Provide a brief description of your business idea

    Describe your business idea in one or two paragraphs by editing the content of the [business summary](<#Business summary>) section.

2. #### Who will be the user of the product or service?

    Define the target customer segments you want to serve.

  #id [profile/Main profile](<#profile Main profile>)
    
3. #### Problem

  List the top three problems your target customers face.

  #id [goals](<#goals>)

4. #### Solution

  Outline the proposed solutions to the top problems you've identified.

    #id [solution](<#solution>)

### Lean Canvas

1. #### Customer Segments

    Define the target customer segments you want to serve.

  #id [Main profile](<#profile Main profile>)
    
2. #### Problem

  List the top three problems your target customers face.

  #id [goals](<#Main profile - Goals>)

3. #### Unique Value Proposition

  Describe the unique and compelling value you offer to your customers that sets you apart from the competition.

    #id [value proposition](<#Main profile - Value proposition>)

4. #### Solution

  Outline the proposed solutions to the top problems you've identified.

    #id [solution](<#Main Solution - Solution>)

5. #### Channels

  List the channels you'll use to reach your target customers.

    #id [channels](<#Main profile - Channels>)

6. #### Revenue Streams

  Identify the ways your business will generate revenue.

    #id [revenue lines](<#Revenue lines>)

7. #### Cost Structure

  Enumerate the main costs associated with your business model.

    #id [cost lines](<#Cost lines>)

8. #### Key Metrics

  Define the key metrics that will help you track your business's success.

    #id [metric list](<#Metric list>)

9. #### Unfair Advantage

  Describe any unfair advantage you may have that cannot be easily copied or bought by competitors.

    #id [unfair advantage](<#Unfair advantage>)

### Business Model Canvas

### Empathy Map

### Think & Feel
What are the thoughts and feelings that occupy the customer's mind? Consider worries, aspirations, and how the environment affects them.
#id think-feel

### Hear
What does the customer hear from their environment, friends, colleagues, and in the media? Include both positive and negative influences.
#id hear

### See
What does the customer see in their immediate environment, the market, and in the media? Capture their view of the world.
#id see

### Say & Do
What does the customer say and do in their environment? How do they behave in public, and what might they be telling others?
#id say-do

### Pain
Identify the customer's pains. What frustrates them, causes them problems, or prevents them from achieving their goals?
#id pain

### Gain
What are the customer's gains? Consider what successes look like, their hopes, and what they would consider a win.
#id gain

### Value Proposition Canvas

**Customer Segment**  
Describe the specific group of customers you are targeting.

#id customer-profile

**Customer Jobs**  
Enumerate the tasks your customers are trying to complete, problems they are trying to solve, or needs they are trying to satisfy.

#id customer-jobs

**Customer Pains**  
Detail the negative experiences, emotions, and risks that your customers experience in the process of getting the job done.

#id customer-pains

**Customer Gains**  
Describe the benefits your customers dream of, including how they measure success and the positive outcomes they wish to achieve.

#id customer-gains

**Value Proposition**  
Articulate the unique value your product or service provides in addressing the customer jobs, relieving pains, and creating gains.

#id value-proposition

**Pain Relievers**  
Specify how your product or service alleviates specific customer pains.

#id pain-relievers

**Gain Creators**  
Explain how your product or service creates customer gains, enhancing positive outcomes and benefits.

#id gain-creators

**Products & Services**  
List the products or services you offer that tie into your value proposition.

#id products-services