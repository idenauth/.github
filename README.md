<div align="center">

<img src="https://www.idenauth.com/logo.svg" alt="Idenauth" width="120" />

# Idenauth

### Infraestructura de identidad para LATAM

[![Website](https://img.shields.io/badge/website-www.idenauth.com-18c964?style=flat-square)](https://www.idenauth.com)
[![Status](https://img.shields.io/badge/status-Producci%C3%B3n-18c964?style=flat-square)](https://www.idenauth.com)
[![Países](https://img.shields.io/badge/cobertura-5%20pa%C3%ADses-18c964?style=flat-square)](https://www.idenauth.com)
[![Compliance](https://img.shields.io/badge/compliance-LGPD%20%7C%20LFPDPPP%20%7C%20Ley%201581-18c964?style=flat-square)](https://www.idenauth.com)

</div>

---

## ¿Qué es Idenauth?

Idenauth es una plataforma de verificación de identidad (KYC) que centraliza la validación de personas en **5 países de América Latina** a través de una sola API REST. Conectamos fuentes oficiales gubernamentales, bases judiciales y validación biométrica en tiempo real, sin intermediarios ni caché obsoleto.

### Cobertura

| País | Documento | Fuente |
|------|-----------|--------|
| 🇲🇽 México | CURP, INE | RENAPO, INE |
| 🇨🇴 Colombia | Cédula, RUT | Registraduría, DIAN |
| 🇵🇪 Perú | DNI, RUC | RENIEC, SUNAT |
| 🇨🇱 Chile | RUN/RUT | SRCeI, SII |
| 🇧🇷 Brasil | CPF, CNPJ | Receita Federal |

### Capacidades

- **Verificación de documentos** — Validación de identidad contra fuentes oficiales
- **Comparación facial** — Biometría facial con detección de vida (liveness)
- **FaceBlock** — Detección de fraude transversal entre verificaciones
- **CrossLinks** — Detección de identidades vinculadas y relaciones sospechosas
- **Compliance por diseño** — Alineación automática con leyes locales de protección de datos
- **Grabación de sesión** — Auditoría completa con video de cada verificación
- **Webhooks** — Notificación en tiempo real del estado de cada verificación

---

## Arquitectura

```
Cliente → API REST → Orquestador → Fuentes oficiales (5 países)
                         ↓
                    Trazabilidad + Logs auditables
                         ↓
                    Webhook → Cliente
```

- **Cifrado**: TLS 1.3 en tránsito, AES-256 en reposo
- **Alta disponibilidad**: Multi-zona con failover automático (SLA 99.9%)
- **Privacidad por diseño**: No almacenamos datos biométricos ni documentos oficiales
- **Procesamiento**: Descarte inmediato post-verificación

---

## Compliance y regulación

| Normativa | País | Estado |
|-----------|------|--------|
| LFPDPPP | México | ✅ |
| Ley 1581 | Colombia | ✅ |
| Ley 29733 | Perú | ✅ |
| Ley 19.628 | Chile | ✅ |
| LGPD | Brasil | ✅ |

---

## Enlaces

- 🌐 **Sitio web**: [www.idenauth.com](https://www.idenauth.com)
- 📧 **Contacto comercial**: [www.idenauth.com/#solicitar-acceso](https://www.idenauth.com/#solicitar-acceso)
- ⚖️ **Legal**: legal@idenauth.com
- 📝 **Blog**: [www.idenauth.com/blog](https://www.idenauth.com/blog)
- ❓ **FAQ**: [www.idenauth.com/faq](https://www.idenauth.com/faq)

---

<div align="center">

**Idenauth®** — La infraestructura de identidad para LATAM.

Idenauth® es una plataforma tecnológica y no sustituye las obligaciones regulatorias, legales o de debida diligencia de sus clientes.

</div>
