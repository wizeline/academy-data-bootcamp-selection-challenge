# Exploratory Analysis

The Customer Service team at Profeco wants to analyze the monitored products in Mexico. The IT team downloaded the database into an Google Drive on a CSV file of about 20GB. Your task as a Data Engineer is processing the data and creating an exploratory analysis with Python Pandas without using pure Python functions.
The Customer Service team at Profeco wants to analyze the monitored products in Mexico. The IT team downloaded the database into an S3 bucket on a CSV file of about 20GB. Your task as a Data Engineer is processing the data and creating an exploratory analysis with Python Pandas without using pure Python functions.

Once the working environment and data are ready, this exercise takes approximately three hours to complete.

The following is the structure of the CSV file:
<br>


| producto                | presentacion                                  | marca            | categoria        | catalogo         | precio | fechaRegistro      | cadenaComercial    | giro       | nombreComercial                         | direccion                             | estado           | municipio | latitud  | longitud   |
| ------------------------- | ----------------------------------------------- | ------------------ | ------------------ | ------------------ | -------- | -------------------- | -------------------- | ------------ | ----------------------------------------- | --------------------------------------- | ------------------ | ----------- | ---------- | ------------ |
| CUADERNO FORMA ITALIANA | 96 HOJAS PASTA DURA. CUADRICULA CHICA         | ESTRELLA         | MATERIAL ESCOLAR | UTILES ESCOLARES | 25.9   | 2011-05-18 0:00:00 | ABASTECEDORA LUMEN | PAPELERIAS | ABASTECEDORA LUMEN SUCURSAL VILLA COAPA | CANNES No. 6 ESQ. CANAL DE MIRAMONTES | DISTRITO FEDERAL | TLALPAN   | 19.29699 | -99.125417 |
| CRAYONES                | CAJA 12 CERAS. JUMBO. C.B. 201423             | CRAYOLA          | MATERIAL ESCOLAR | UTILES ESCOLARES | 27.5   | 2011-05-18 0:00:00 | ABASTECEDORA LUMEN | PAPELERIAS | ABASTECEDORA LUMEN SUCURSAL VILLA COAPA | CANNES No. 6 ESQ. CANAL DE MIRAMONTES | DISTRITO FEDERAL | TLALPAN   | 19.29699 | -99.125417 |
| CRAYONES                | CAJA 12 CERAS. TAMANO REGULAR C.B. 201034     | CRAYOLA          | MATERIAL ESCOLAR | UTILES ESCOLARES | 13.9   | 2011-05-18 0:00:00 | ABASTECEDORA LUMEN | PAPELERIAS | ABASTECEDORA LUMEN SUCURSAL VILLA COAPA | CANNES No. 6 ESQ. CANAL DE MIRAMONTES | DISTRITO FEDERAL | TLALPAN   | 19.29699 | -99.125417 |
| COLORES DE MADERA       | CAJA 12 PIEZAS LARGO. TRIANGULAR. C.B. 640646 | PINCELIN         | MATERIAL ESCOLAR | UTILES ESCOLARES | 46.9   | 2011-05-18 0:00:00 | ABASTECEDORA LUMEN | PAPELERIAS | ABASTECEDORA LUMEN SUCURSAL VILLA COAPA | CANNES No. 6 ESQ. CANAL DE MIRAMONTES | DISTRITO FEDERAL | TLALPAN   | 19.29699 | -99.125417 |
| COLOR LARGO             | CAJA 36 PIEZAS. CON SACAPUNTAS. 68-4036       | CRAYOLA          | MATERIAL ESCOLAR | UTILES ESCOLARES | 115    | 2011-05-18 0:00:00 | ABASTECEDORA LUMEN | PAPELERIAS | ABASTECEDORA LUMEN SUCURSAL VILLA COAPA | CANNES No. 6 ESQ. CANAL DE MIRAMONTES | DISTRITO FEDERAL | TLALPAN   | 19.29699 | -99.125417 |
| BOLIGRAFO               | BLISTER 3 PIEZAS. PUNTO FINO. GEL             | BIC. CRISTAL GEL | MATERIAL ESCOLAR | UTILES ESCOLARES | 32.5   | 2011-05-18 0:00:00 | ABASTECEDORA LUMEN | PAPELERIAS | ABASTECEDORA LUMEN SUCURSAL VILLA COAPA | CANNES No. 6 ESQ. CANAL DE MIRAMONTES | DISTRITO FEDERAL | TLALPAN   | 19.29699 | -99.125417 |
| CINTA ADHESIVA          | BOLSA 1 PIEZA. 12 MM. X 33 M. C.B. 100317     | SCOTCH 3M. 600   | MATERIAL ESCOLAR | UTILES ESCOLARES | 9      | 2011-05-18 0:00:00 | ABASTECEDORA LUMEN | PAPELERIAS | ABASTECEDORA LUMEN SUCURSAL VILLA COAPA | CANNES No. 6 ESQ. CANAL DE MIRAMONTES | DISTRITO FEDERAL | TLALPAN   | 19.29699 | -99.125417 |

#### **Respond to the following questions:**

1. How many commercial chains are monitored, and therefore, included in this database?
2. What are the top 10 monitored products by State?
3. Which is the commercial chain with the highest number of monitored products?
4. Use the data to find an interesting fact.
5. What are the lessons learned from this exercise?
6. Can you identify other ways to approach this problem? Explain.

### Deliverables

* Python Code (Plain Script or Jupyter Notebook) on GitHub.

* Create a report that includes the responses to the questions, the lessons learned, and any additional comments. In this report, you can include diagrams and images that support your solution.
