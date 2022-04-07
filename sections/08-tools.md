# Tools

เครื่องมือต่างๆ ในโลก Data Engineering

## Airbyte

https://airbyte.io/

Airbyte เป็นเครื่องมือโอเพ่นซอร์สที่ช่วยทำให้ข้อมูลเชื่อมต่อ และสอดคล้องกันระหว่างแอพพลิเคชั่น API
และฐานข้อมูล กับระบบปลายทางที่เก็บข้อมูลอื่นๆ อาทิ เช่น Data Warehouse หรือ Data Lake

## Airflow

https://airflow.apache.org/

Airflow หรือ Apache Airflow คือโอเพ่นซอร์สแพลตฟอร์มที่เราสามารถที่จะตรวจสอบ ทำตารางเวลา และเฝ้าสังเกต กระแสงาน หรือ Workflow ขั้นตอนการประมวลผลได้

การที่เราสามารถเขียนโค้ดเพื่อกำหนด Workflow ได้ จะทำให้เราดูแลรักษา Workflow ได้ง่ายขึ้น สามารถเก็บเป็นเวอร์ชั่น สามารถทดสอบ
และสามารถทำให้การทำงานร่วมกันง่ายขึ้นได้

* [Airflow 2.0 มีอะไรใหม่บ้าง มาดูกัน 🤩](https://medium.com/odds-team/airflow-2-0-%E0%B8%A1%E0%B8%B5%E0%B8%AD%E0%B8%B0%E0%B9%84%E0%B8%A3%E0%B9%83%E0%B8%AB%E0%B8%A1%E0%B9%88%E0%B8%9A%E0%B9%89%E0%B8%B2%E0%B8%87-%E0%B8%A1%E0%B8%B2%E0%B8%94%E0%B8%B9%E0%B8%81%E0%B8%B1%E0%B8%99-362aa07472ba)
* [เขียน Document ใน Airflow โดยใช้ doc_md](https://medium.com/pyconth/%E0%B9%80%E0%B8%82%E0%B8%B5%E0%B8%A2%E0%B8%99-document-%E0%B9%83%E0%B8%99-airflow-%E0%B9%82%E0%B8%94%E0%B8%A2%E0%B9%83%E0%B8%8A%E0%B9%89-doc-md-e2a29b489f7b)

## Amundsen

https://www.amundsen.io/

## AWS S3

https://aws.amazon.com/s3/

AWS S3 หรือ Amazon Simple Storage Service เป็นพื้นที่จัดเก็บไฟล์บนคลาวด์ของทาง Amazon Web Services (AWS) เหมาะกับการใช้งานที่หลากหลาย เช่น จัดเก็บข้อมูลดิบ เว็บไซต์ แอปพลิเคชันมือถือ การสำรองข้อมูลและการคืนค่า การเก็บข้อมูลแบบถาวร รวมทั้งการวิเคราะห์ Big Data

## Azure Blob Storage

https://azure.microsoft.com/services/storage/blobs

Azure Blob Storage เป็นพื้นที่จัดเก็บไฟล์บนคลาวด์ของทาง Microsoft Azure ที่เหมาะสำหรับ Unstructured data โดยเฉพาะ

## Dataprep

https://cloud.google.com/dataprep

Dataprep คือ serverless service สำหรับการจัดการ Data ของทาง Google Cloud โดยที่เราไม่จำเป็นต้องเขียน Code ซึ่งสามารถใช้งานผ่าน Web Browser ได้ รองรับการทำงานกับ Data หลากหลายแบบ เช่น Cleansing, Preparing Transform จนถึงการสร้าง Data Pipeline แบบครบวงจร

## Data Studio

https://datastudio.google.com/

Data Studio คือเครื่องมือสำหรับสร้าง Dashboard ของทาง Google สามารถสร้างและใช้งานผ่าน Web Browser ได้ โดยสามารถแสดงข้อมูลในรูปแบบ Chart, Table, Maps และอื่น ๆ รวมถึงรองรับการเชื่อมต่อกับ service ภายนอกเช่น BigQuery, Dataprep, Google Analytics, Google Cloud Storage เป็นต้น

## dbt

https://www.getdbt.com/

* [dbt คืออะไรนะ?](https://zkan.hashnode.dev/what-is-dbt)
* [เริ่มต้นกับ dbt](https://zkan.hashnode.dev/get-started-with-dbt)
* [การจัดการโมเดลใน dbt และการทดสอบ](https://zkan.hashnode.dev/dbt-models-and-tests)

## Debezium

https://debezium.io/

## Druid

https://druid.apache.org/

## Google Cloud Storage

https://cloud.google.com/storage

Google Cloud Storage เป็นพื้นที่จัดเก็บไฟล์บนคลาวด์ของทาง Google Cloud ที่สามารถเลือกภูมิภาค (region) ในการจัดเก็บไฟล์ได้หลากหลาย ซี่งช่วยให้การรับส่งไฟล์มีความหน่วงน้อย (low latency)

## Great Expectations

https://greatexpectations.io/

Great Expectations เป็นเครื่องมือที่ช่วยให้เราดูแลรักษาคุณภาพของข้อมูล (data quality) ไว้ โดยผ่านฟังก์ชั่นการทำงานที่เข้าใจได้ง่าย อย่างเช่น `expect_table_row_count_to_be_between` ที่เอาไว้ตรวจสอบจำนวนแถวของตารางว่าควรจะมีจำนวนแถวอยู่ระหว่างเท่าไหร่ถึงเท่าไหร่เป็นต้น

## Kafka

https://kafka.apache.org/

## Logstash

https://www.elastic.co/logstash/

Logstash คือ โอเพ่นซอร์สสำหรับงานประมวลผลข้อมูลฝั่งเซิร์ฟเวอร์ ที่สามารถนำเข้าข้อมูลจากแหล่งต่าง ๆ พร้อมกับแปลงข้อมูลให้อยู่ในรูปแบบที่ต้องการได้

## Marquez

https://marquezproject.github.io/marquez/

## MongoDB

https://www.mongodb.com/

MongoDB คือ โอเพ่นซอร์สสำหรับฐานข้อมูลเอกสาร (Document Database: ฐานข้อมูล NoSQL ชนิดหนึ่งซึ่งมีการเก็บข้อมูลในรูปแบบ JSON Object) ที่มีประสิทธิภาพสูง (High Performance) มีความพร้อมใช้งานสูง (High Availability) และมีการปรับขนาดอัตโนมัติ (Automatic Scaling)

## Orchest

https://www.orchest.io/

## Pulsar

https://pulsar.apache.org/

## RapidMiner

https://rapidminer.com/

## Snowflake

https://www.snowflake.com/

## Spark

https://spark.apache.org/

Spark หรือ Apache Spark เป็นเครื่องมือที่เราจะเอาไว้ประมวลผลข้อมูลขนาดใหญ่ หรือสร้างโมลเดล Machine Learning จากข้อมูลขนาดใหญ่ โดยที่เราสามารถนำเอาไปใช้กับ batch processing หรือ real-time processing ก็ได้

เครื่องมือตัวนี้แทบจะเป็นตัวเลือกในอันดับต้นๆ เลยก็ว่าได้ที่เอามาใช้ในการประมวลผลข้อมูลขนาดใหญ่ ตอนที่ประมวลผล Spark จะประมวลผลแบบ in-memory ทำให้การประมวลผลนั้นทำได้รวดเร็วมาก เมื่อเทียบกับ Hadoop MapReduce ที่ใช้การอ่านเขียนข้อมูลที่เป็นไฟล์จาก disk

## Superset

https://superset.apache.org/
