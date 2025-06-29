 ``` mermaid
graph TB
    A[Autism Spectrum Disorder] --> B[Genetic Factors<br/>80-90% Heritability]
    A --> C[Environmental Factors<br/>10-20% Contribution]
    
    B --> D[Single Gene Mutations]
    B --> E[Copy Number Variants]
    B --> F[Polygenic Risk]
    B --> G[De Novo Mutations]
    
    D --> D1[SHANK3<br/>Synaptic Function]
    D --> D2[MECP2<br/>Rett Syndrome]
    D --> D3[FMR1<br/>Fragile X Syndrome]
    D --> D4[PTEN<br/>Cell Growth/Migration]
    D --> D5[CHD8<br/>Chromatin Remodeling]
    D --> D6[SCN2A<br/>Sodium Channel]
    
    E --> E1[16p11.2 Deletion/Duplication]
    E --> E2[15q11-13 Duplication]
    E --> E3[22q11.2 Deletion]
    E --> E4[7q11.23 Duplication]
    
    F --> F1[Common Variants<br/>100+ Risk Loci]
    F --> F2[Additive Effects<br/>Small Individual Impact]
    
    G --> G1[Paternal Age Effect<br/>Increased Risk >40 years]
    G --> G2[Spontaneous Mutations<br/>Not Inherited]
    
    C --> H[Prenatal Factors]
    C --> I[Perinatal Factors]
    C --> J[Postnatal Factors]
    C --> K[Maternal Factors]
    
    H --> H1[Maternal Infections<br/>Rubella, Cytomegalovirus]
    H --> H2[Prenatal Medications<br/>Valproic Acid, Thalidomide]
    H --> H3[Maternal Diabetes]
    H --> H4[Prenatal Stress]
    
    I --> I1[Premature Birth<br/><32 weeks]
    I --> I2[Low Birth Weight<br/><2500g]
    I --> I3[Birth Complications<br/>Hypoxia, Trauma]
    I --> I4[Cesarean Delivery]
    
    J --> J1[Air Pollution Exposure]
    J --> J2[Heavy Metal Exposure<br/>Lead, Mercury]
    J --> J3[Pesticide Exposure]
    J --> J4[Nutritional Deficiencies<br/>Folate, Vitamin D]
    
    K --> K1[Advanced Maternal Age<br/>>35 years]
    K --> K2[Maternal Autoimmune<br/>Disorders]
    K --> K3[Maternal Mental Health<br/>Depression, Anxiety]
    K --> K4[Inter-pregnancy Interval<br/><12 months]
    
    L[Gene-Environment Interaction] --> A
    L --> L1[Genetic Susceptibility<br/>+ Environmental Triggers]
    L --> L2[Epigenetic Modifications<br/>Gene Expression Changes]
    L --> L3[Critical Developmental<br/>Windows]
    
    M[Neurodevelopmental Pathways] --> A
    M --> M1[Synaptic Development<br/>Connectivity Disruption]
    M --> M2[Neural Migration<br/>Cortical Organization]
    M --> M3[Myelination<br/>White Matter Changes]
    M --> M4[Neurotransmitter Systems<br/>GABA/Glutamate Balance]
    
    N[Cellular Mechanisms] --> A
    N --> N1[Protein Synthesis<br/>mTOR Pathway]
    N --> N2[Calcium Signaling<br/>Synaptic Transmission]
    N --> N3[Immune Dysfunction<br/>Microglial Activation]
    N --> N4[Mitochondrial Function<br/>Energy Metabolism]
    
    style A fill:#ff6b6b,stroke:#333,stroke-width:3px,color:#fff
    style B fill:#4ecdc4,stroke:#333,stroke-width:2px
    style C fill:#45b7d1,stroke:#333,stroke-width:2px
    style L fill:#96ceb4,stroke:#333,stroke-width:2px
    style M fill:#feca57,stroke:#333,stroke-width:2px
    style N fill:#ff9ff3,stroke:#333,stroke-width:2px
```
