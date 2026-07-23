<div align="center">


### Infraestructura de identidad (KYC) para LATAM

[![Website](https://img.shields.io/badge/website-www.idenauth.com-18c964?style=flat-square)](https://www.idenauth.com)
[![Cobertura](https://img.shields.io/badge/cobertura-5%20pa%C3%ADses-18c964?style=flat-square)](https://www.idenauth.com)
[![Compliance](https://img.shields.io/badge/compliance-LGPD%20%7C%20LFPDPPP%20%7C%20Ley%201581-18c964?style=flat-square)](https://www.idenauth.com)
[![Status](https://img.shields.io/badge/status-Producci%C3%B3n-18c964?style=flat-square)](https://www.idenauth.com)

</div>

---

## Acerca de Idenauth

<a href="https://www.idenauth.com" target="_blank">Idenauth</a> es una plataforma de verificación de identidad (KYC) que centraliza la validación de personas en **5 países de América Latina** a través de una sola API REST. Conectamos fuentes oficiales gubernamentales, bases judiciales y validación biométrica en tiempo real, sin intermediarios ni caché obsoleto.

#### Aquí puedes:
<ul>
    <li>Revisar código e información de releases
    <li>Proponer Pull Requests
    <li>Hacer fork del proyecto
</ul>

Para solicitar soporte, visita [www.idenauth.com/faq](https://www.idenauth.com/faq) o contáctanos en [www.idenauth.com/#solicitar-acceso](https://www.idenauth.com/#solicitar-acceso).

---

## Repos de Idenauth

### Plataforma KYC

La plataforma principal de Idenauth permite verificar la identidad de personas en 5 países de LATAM mediante una sola API REST.

#### Principales características
<ul>
    <li>Verificación contra fuentes oficiales en tiempo real
    <li>Biometría facial con detección de vida (liveness)
    <li>Compliance por diseño — alineación con leyes locales
    <li>Webhooks para notificación en tiempo real
    <li>Auditoría completa con trazabilidad de cada verificación
</ul>

#### Repos relacionados
<ul>
    <li><a href="https://github.com/idenauth/Idenauth">Idenauth</a> — Plataforma principal (Backend + Frontend + infraestructura)
</ul>

---

### Cobertura

| País | Documento | Fuente |
|------|-----------|--------|
| 🇲🇽 México | CURP, INE | RENAPO, INE |
| 🇨🇴 Colombia | Cédula, RUT | Registraduría, DIAN |
| 🇵🇪 Perú | DNI, RUC | RENIEC, SUNAT |
| 🇨🇱 Chile | RUN/RUT | SRCeI, SII |
| 🇧🇷 Brasil | CPF, CNPJ | Receita Federal |

---

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

## Contribuir

¡Las contribuciones de código son bienvenidas! Por favor envía tus Pull Requests contra la rama `main`.

Los auditorías de seguridad y feedback son bienvenidos. Puedes abrir un issue o escribirnos privately si el reporte es sensible en naturaleza.

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
