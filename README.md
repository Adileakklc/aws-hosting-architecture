# Hosting-101.com için AWS Bulut Mimarisi Tasarımı

Bu proje, yüksek trafikli bir WordPress tabanlı web sitesi için AWS üzerinde **yüksek erişilebilirlik**, **ölçeklenebilirlik** ve **güvenlik** odaklı bir bulut mimarisi tasarımını içerir.

Tasarım kapsamında:

- VPC & CIDR planlaması  
- Public / Private / Data subnet segmentasyonu  
- Application Load Balancer (Layer 7 yönlendirme)  
- NAT Gateway (çoklu AZ yapı)  
- RDS (MariaDB) izole veri tabanı katmanı  
- EFS ile paylaşımlı dosya sistemi  
- AWS WAF ile web uygulama güvenliği  
- Route 53 ile DNS yönlendirme  
- IAM ile least-privilege yetkilendirme  
- AWS Pricing Calculator ile maliyet analizi  

## 📁 Klasör Yapısı

```text
aws-hosting-architecture/
 ├── cost/
 │   └── calculator-link.txt
 ├── docs/
 │   └── aws-mimari.pdf
 ├── architecture/
 │   └── awsproje.drawio.png
 └── README.md
```

## 📄 Dokümanlar

- Detaylı AWS mimarisi PDF: `docs/aws-mimari.pdf`
