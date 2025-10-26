# 🧩 **Data Integration with XML**

Java application developed for **data extraction, transformation, and integration** from heterogeneous web sources (Wikipedia and DB-City).  
The system consolidates country information into a structured XML document, ensuring **data validation, querying, and transformation** through modern XML technologies.  

---

## 🚀 Setup / Execution

1. Open the project folder DataIntegration_Project/ in **Eclipse, IntelliJ IDEA**, or another Java IDE.
2. Ensure **Java 11** (or higher) and the required XML libraries (JAXP, XQuery processor) are configured.
3. Run the main Java class to start the data integration process.
4. The program will extract data from Wikipedia and DB-City, process it, and generate a validated XML file.
5. You can then use the provided XSLT and XQuery scripts to transform and query the XML data.
6. After these steps, the system will produce a structured XML dataset ready for analysis or visualization.

---

## 🗺 Project Diagram

Below is a simplified view of the **Data Integration workflow**, representing how information flows from external sources through the integration and transformation stages:
```
[Wikipedia]        [DB-City]
      ↓                  ↓
   Data Extraction & Parsing (Java)
              ↓
       XML Normalization
              ↓
     Validation (DTD / XSD)
              ↓
   Querying (XPath / XQuery)
              ↓
     Transformation (XSLT)
              ↓
  Output: Integrated XML / HTML / Text
```


(If the image doesn’t load, check the PDF version in Data_Integration_Report/DataIntegration_Diagram.pdf.)


---

## 📁 **Project Structure**

- **DataIntegration_Project/** → Source code and XML processing logic  
- **Data_Integration_Report/** → Documentation and project report  
- **README.md** → Project overview and technical description  

---

## ⚙️ **Main Features**

- **Data integration** from external web sources (Wikipedia, DB-City)  
- **Data normalization and transformation** into unified XML format  
- **DTD and XSD validation** to ensure data consistency  
- **XPath and XQuery** for structured queries  
- **XSLT transformations** to convert XML into HTML and text formats  
- **Graphical user interface (GUI)** for managing and visualizing data  

---

## 🧩 **Technologies Used**

- **Java** (data handling, XML parsing, and GUI implementation)  
- **XML / DTD / XSD** (data structure and validation)  
- **XPath / XQuery / XSLT** (data querying and transformation)  

---

## 🧠 **Learning Outcomes**

- Experience with **structured data representation (XML)**  
- Implementation of **data validation and transformation pipelines**  
- Application of **query languages (XPath, XQuery)** for information retrieval  
- Development of a **user-friendly data management interface**

---

## 📚 **About**

Developed for the **Data Integration and Information Systems** course at the **Instituto Superior de Engenharia de Coimbra (ISEC)**.  
The project focuses on practical application of **data extraction, integration, and transformation techniques**, simulating a real-world data processing workflow.  

---


