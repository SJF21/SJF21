erDiagram
    PIANO ||--o{ MODEL : ""
    MODEL ||--o{ DESIGNER : ""
    PIANO {
        string Serial_Number "Serial Number (PK)"
        date Mfg_Completion_Date "Manufacturing Completion Date"
        string Model_ID "Model ID (FK)"
    }
    MODEL {
        string ID_Number "ID Number (PK)"
        string Name "Name"
        string Designer_ID "Designer ID (FK)"
    }
    DESIGNER {
        string Designer_ID "Designer ID (PK)"
        string Designer_Name "Designer Name"
    }
 
