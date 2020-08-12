# alliance_bernstein_file_extrator

NLP tools are used to extract relevant information from 424B filings pulled from the Electronic Data Gathering, Analysis, and Retrieval (EDGAR) system. These are filings required by the SEC when a company is issuing certain types of securities. The purpose of these forms is to protect investors by requiring detailed information about the securities to be provided prior to selling the securities.

The main challenge of working with these filings is the lack of a common document format. The starter files that you have to work with, contained in the data folder, show some of this variety. Your goal is to build a robust extractor which can work not just on the selected documents, but one which also has success on documents formatted differently than the provided subset.

There are a number of key features contained in these filings, but for this project, we are only going to be focusing on a subset of these features. Contained in the data folder is an Excel file, nss_cadidate_edgar_docs.xls which contains the values of these fields for the provided documents. Warning: these fields were automatically extracted, so may not be 100% accurate. Use with caution.

The fields that you will focus on are as follows:

* issuer_name
* security_description
* cusip_id
* isin_id
* original_face_amount
* maturity_date
* coupon_type_code
* cpn_pay_frq_code
* is_callable

Detailed information about these fields is contained in the file 'EDGAR DOCUMENTATION Excerpt.docx'.
