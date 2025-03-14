
# NorwegianFinanceQA

  

**NorwegianFinanceQA** is an open-source test framework designed to evaluate Retrieval-Augmented Generation (RAG) systems. The dataset consists of nine unstructured Norwegian financial documents of varying lengths and structures. Given the challenges posed by multimodal elements, this framework differentiates between standard text queries and table-based queries, enabling RAG pipeline developers to identify specific areas where their systems may fall short.

  

### Data Structure:

-  **Query**: The question being asked.

-  **Ground_truth**: The correct answer to the query.

-  **Necessary_keywords**: A list of key terms and phrases required in the context window for effective retrieval.

-  **Query_type**: Specifies whether the query relates to 'table' or 'text'.

-  **Text_query_type**: For text-based queries, this field is either `number_reasoning` or `text_reasoning`, depending on the type of information being retrieved.

-  **Page_number**: A list of page numbers where the information from the `necessary_keywords` can be located.

-   **File**: The source file from which the question was derived.

For additional details on the creation process or guidance on using the necessary_keywords for retrieval metrics, please refer to the thesis, which can be accessed [HERE](https://openaccess.nhh.no/nhh-xmlui/bitstream/handle/11250/3178510/no.nhh%3awiseflow%3a7200393%3a61696255.pdf?sequence=1&isAllowed=y).
