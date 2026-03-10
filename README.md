# Terrafy - Digital Land Verification Infrastructure

## Overview

Terrafy builds digital land verification infrastructure enabling **600M+ smallholder farmers** to access formal finance (credit, insurance, climate finance).

### The Problem
- **80% of sub-Saharan African land is undocumented**
- **500M+ smallholders locked out of $300B annual credit opportunity**
- Banks see smallholder lending as risky (30-40% default)
- Current verification costs $200-500/parcel, takes 3-6 months
- Insurance fraud is 15-25% without verification
- Climate finance can't reach unverified farmers

### The Solution: Three-Layer Trust Architecture™SATELLITE VERIFICATION
          ↓ (Sentinel-2 + ML)
          
    GROUND-TRUTH VERIFICATION
    ↓ (Farmer GPS + Photos)
    
    COMMUNITY VERIFICATION
    ↓ (Elder Digital Signature)
    
    INSTITUTIONAL-GRADE DIGITAL TITLE
    **Layer 1: Satellite Verification** (Technology)
- Sentinel-2 free EU satellite imagery
- ML boundary detection
- Cost: <$0.10/parcel | Speed: Real-time | Accuracy: 85-90%

**Layer 2: Ground-Truth (BYOD)** (Farmer Participation)
- Farmer smartphone GPS + photos
- Zero hardware cost
- Cost: $0 | Speed: 5-10 min | Accuracy: 95%+

**Layer 3: Community Validation** (Social Trust)
- Village elder digital signature
- Community consensus record
- Cost: $0 | Speed: 24-48h | Accuracy: 99%+

## Traction (Real Metrics)

**Operational Since:** July 2025 (9 months)

### Parcel Verification
- **20,000+ parcels verified**
- **Accuracy:** 94% (ground-truth validation)
- **Verification time:** Average 24 hours

### Credit Facilitation
- **Partner:** Equity Bank Kenya
- **Credit facilitated:** $3.5M USD
- **Default rate:** **ZERO** (vs. 30-40% industry)
- **Approval rate:** 85%+ (vs. typical 40-50%)

### Insurance Integration
- **Partner:** APA Insurance
- **Policies issued:** 5,500+
- **Fraud rate:** **ZERO** (vs. 15-25% industry)

### Financial Performance
- **Revenue (9 months):** $449,000
- **Profitability:** Month 9 EBITDA positive
- **Margin:** 81.7% gross, 37.9% net

### Institutional Validation
✅ **Equity Bank Kenya** - Live, expanding  
✅ **APA Insurance** - Live, expanding  
✅ **BRITAM Holdings** - LOI signed (Q3 2026)  
✅ **Machakos County** - MOU signed  
✅ **Rwanda Ministry of Lands** - MOU signed  
✅ **Uganda Ministry of Lands** - Partnerships signed  

## Team

- **Victor Shikoli** (CEO & Co-Founder) - Serial entrepreneur, Africa digital infrastructure
- **Humphrey Shikoli** (CTO & Co-Founder) - Geospatial AI expert
- **Leah Khasiala** (COO & Co-Founder) - 6+ years rural agent network expertise
- **Queta González Lizardi** (Strategic Advisor) - Techstars Director, 50+ exits

## Unit Economics

| Metric | Value |
|--------|-------|
| CAC (Customer Acquisition Cost) | $13.50 |
| LTV (Lifetime Value) | $114.59 |
| LTV/CAC Ratio | 8.48x |
| Payback Period | 12.4 months |
| Gross Margin | 81.7% |

## Technology Stack

**Backend:** Node.js / Express  
**Database:** PostgreSQL  
**Frontend:** React Native (Mobile), React (Dashboard)  
**AI/ML:** TensorFlow (Satellite ML), Python  
**Infrastructure:** Docker, Kubernetes, AWS  
**Blockchain:** Cryptographic signing (Community), Future: Hyperledger, Polygon  

## Deployment Status

### Live (Production)
- ✅ Kenya - Full operations (20,000 parcels)
- ✅ Equity Bank integration - Live lending
- ✅ APA Insurance integration - Live policies

### Launching (Q2 2026)
- 🚀 Rwanda - Government partnership launch
- 🚀 Uganda - Institutional partner integration

## Roadmap (12 Months)

**Phase 1: Geographic Replication (Q2)**
- Rwanda official launch
- 5,000 parcels verified
- 2 institutional partners
- $5M credit facilitated

**Phase 2: Institutional Scaling (Q3)**
- Uganda launch + Equity Bank expansion
- 50,000 cumulative parcels
- 5+ institutional partners
- Climate finance integration (TerraCarbon™)

**Phase 3: Product Enhancement (Q3-Q4)**
- Government registry API integration
- Advanced ML model (96%+ accuracy)
- Mobile app v2.0 release

**Phase 4: Consolidation (Q4-Q1 2027)**
- Tanzania launch (4th country)
- 150,000+ cumulative parcels
- 10+ institutional partners
- Series B fundraising readiness

## Impact Metrics

### Direct Impact
- **Smallholders reached:** 10,000 (Y1) → 150,000 (Y3)
- **Credit access unlocked:** $35M (Y1) → $300M+ (Y3)
- **Women farmers (40%):** 6,000 (Y1) → 60,000 (Y3)

### SDG Alignment
- **SDG 1 (No Poverty):** Credit access reduces poverty
- **SDG 2 (Zero Hunger):** Climate finance enables sustainable agriculture
- **SDG 5 (Gender Equality):** 40% of farmers are women
- **SDG 8 (Decent Work):** 200+ rural jobs created
- **SDG 10 (Reduced Inequality):** Financial inclusion for marginalized
- **SDG 13 (Climate Action):** $5B+ carbon market unlocked

## Getting Started

### Prerequisites
### Installation
```bash
git clone https://github.com/terrafy-africa/terrafy-verification-core.git
cd terrafy-verification-core
pip install -r requirements.txt
npm install
npm test
docker-compose up
```

## API Documentation

### Verify Parcel
```bash
POST /api/v1/parcels/verify
```

### Register Loan
```bash
POST /api/v1/institutions/loans
```

## Contributing

See CONTRIBUTING.md for guidelines.

## License

MIT License - See LICENSE file

## Contact

- **Email:** hello@terrafy.africa
- **Website:** https://www.terrafy.africa
- **LinkedIn:** [Terrafy Africa](https://www.linkedin.com/company/terrafy-africa/)

## For UNICEF Evaluators

This repository is part of the UNICEF Innovation Fund application.

**Key Documentation:**
- [ARCHITECTURE.md](./ARCHITECTURE.md) - Technical deep-dive
- [DEPLOYMENT-ROADMAP.md](./docs/DEPLOYMENT-ROADMAP.md) - 12-month plan

**Status:** Live Product | Active Users | Institutional Integration  
**Last Updated:** March 2026
