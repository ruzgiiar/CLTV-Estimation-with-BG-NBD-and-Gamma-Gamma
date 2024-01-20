# CLTV Estimation with BG NBD and Gamma-Gamma
---

## Business Problem (İş Problemi)

- **A UK-based retail company wants to determine a roadmap for its sales and marketing activities. In order for the company to make medium-long term plans, it is necessary to estimate the potential value that existing customers will provide to the company in the future.**

  - *(İngiltere merkezli perakende şirketi satış ve pazarlama faaliyetleri için roadmap belirlemek istemektedir. Şirketin orta uzun vadeli plan yapabilmesi için var olan müşterilerin gelecekte şirkete sağlayacakları potansiyel değerin tahmin edilmesi gerekmektedir.)*

---

## Data Set Story (Veri Seti Hikayesi)

- **The dataset named "Online Retail II" contains online sales transactions of a UK-based retail company between 01/12/2009 and 09/12/2011. The company's product catalog includes gift items, and it is known that most of its customers are wholesalers.**

  - (*Online Retail II isimli veri seti İngiltere merkezli bir perakende şirketinin  01/12/2009 - 09/12/2011 tarihleri arasındaki online satış işlemlerini içeriyor. Şirketin ürün kataloğunda hediyelik eşyalar yer almaktadır ve çoğu müşterisinin toptancı olduğu bilgisi mevcuttur.*)

- **InvoiceNO** : *If this code starts with C, it means that the transaction has been cancelled* (Eğer bu kod C ile başlıyorsa işlemin iptal edildiğini ifade eder)

- **StockCode** : *Unique code for each product* (Her bir ürün için eşşiz kod)

- **Description** : *Product Name* (Ürün İsmi)

- **Quantity** : *How many of the products on the invoices were sold* (Faturalardaki ürünlerden kaçar tane satıldığı)

- **InvoiceDate** : (Fatura Tarihi)

- **UnitPrice** : *Invoice price in sterling* (Sterlin Cinsinden Fatura Fiyatı)

- **CustomerID** : *Unique Customer Numbers* (Eşsiz müşteri Numaraları)

- **Country** : (Ülke)
