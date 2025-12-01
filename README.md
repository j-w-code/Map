# Jeffrey Wiley Archive Ecosystem - Visual Architecture

**Created:** December 1, 2025  
**Purpose:** Visual map of archive structure, cross-references, and domain relationships  
**Format:** Mermaid diagrams (render in Markdown viewers or Mermaid Live Editor)

---

## MASTER ARCHITECTURE: Archive Ecosystem

```mermaid
graph TB
    subgraph CORE["🎯 CORE ARCHIVE"]
        ARCHIVE[Jeffrey_Wiley_Resume_Archive_v1.5.1<br/>FSIQ 117 | GAI 122<br/>13,500 words]
    end
    
    subgraph COGNITIVE["🧠 COGNITIVE ASSESSMENT"]
        WAIS[WAIS-V Profile<br/>VCI 122 | WMI 122<br/>FRI 120 | PSI 120<br/>VSI 108]
        FSIQ[FSIQ: 117<br/>87th percentile<br/>Employment Positioning]
        GAI[GAI: 122<br/>93rd percentile<br/>Learning Potential]
        SPIKY[Spiky Profile<br/>14-point spread<br/>VSI 108 → VCI/WMI 122]
    end
    
    subgraph PROFESSIONAL["💼 PROFESSIONAL EXPERIENCE"]
        FREEMAN[Freeman Hybrid Tech Lead<br/>Apr 2024 - Oct 2025<br/>Training/Documentation]
        CHS[CHS Events Stage Manager<br/>Jan 2021 - Mar 2024<br/>Super Bowl LVI]
        HOLIUM[Holium Copywriter<br/>Aug-Nov 2023<br/>Urbit Assembly]
        FANSIDED[FanSided Writer<br/>Jun-Dec 2018<br/>22 Articles]
    end
    
    subgraph CREATIVE["🎨 CREATIVE OUTPUT"]
        MUSIC[4 Music Releases<br/>16 tracks, 97 minutes<br/>2015-2017]
        BOOKS[2 Editorial Credits<br/>ISBNs verified<br/>2021-2023]
        ARTICLES[22 Published Articles<br/>FanSided Network<br/>2018]
    end
    
    subgraph TECHNICAL["⚙️ TECHNICAL PROJECTS"]
        J3K[J3K Blockchain DAO<br/>GitHub<br/>FinTech Bootcamp A]
        AI_DEV[AI-Assisted Dev<br/>Python/React<br/>Oct 2025-Present]
    end
    
    subgraph LEARNING["📚 LEARNING PATHS"]
        ALGO[Algorithmic Composition<br/>Month 1: TidalCycles<br/>GAI 122 Track]
        PROMPT[AI Prompting Master<br/>Phase 2 Start<br/>FSIQ 117 Track]
    end
    
    subgraph EVIDENCE["📊 PORTFOLIO EVIDENCE"]
        URL_FANSIDED[dorksideoftheforce.com<br/>Author Page]
        URL_GITHUB[github.com/j-w-code/J3K<br/>Blockchain Repo]
        URL_BANDCAMP[jwdance.bandcamp.com<br/>Music Releases]
        URL_AMAZON[Amazon ISBNs<br/>Book Credits]
    end
    
    %% Core relationships
    ARCHIVE --> WAIS
    ARCHIVE --> PROFESSIONAL
    ARCHIVE --> CREATIVE
    ARCHIVE --> TECHNICAL
    ARCHIVE --> LEARNING
    ARCHIVE --> EVIDENCE
    
    %% Cognitive domain relationships
    WAIS --> FSIQ
    WAIS --> GAI
    WAIS --> SPIKY
    
    %% Professional to cognitive mapping
    FREEMAN -.->|Uses WMI 122| WAIS
    CHS -.->|Uses WMI 122| WAIS
    HOLIUM -.->|Uses VCI 122| WAIS
    FANSIDED -.->|Uses VCI 122| WAIS
    
    %% Creative to cognitive mapping
    MUSIC -.->|Demonstrates FRI 120| WAIS
    ARTICLES -.->|Demonstrates VCI 122| WAIS
    
    %% Learning path alignment
    ALGO -.->|Targets GAI 122| GAI
    PROMPT -.->|Professionalizes FSIQ 117| FSIQ
    
    %% Evidence verification
    ARTICLES --> URL_FANSIDED
    J3K --> URL_GITHUB
    MUSIC --> URL_BANDCAMP
    BOOKS --> URL_AMAZON
    
    style ARCHIVE fill:#2c3e50,stroke:#3498db,stroke-width:4px,color:#ecf0f1
    style WAIS fill:#8e44ad,stroke:#9b59b6,stroke-width:3px,color:#ecf0f1
    style FSIQ fill:#27ae60,stroke:#2ecc71,stroke-width:2px,color:#ecf0f1
    style GAI fill:#e74c3c,stroke:#c0392b,stroke-width:2px,color:#ecf0f1
```

---

## DOMAIN BREAKDOWN: Cognitive → Professional Mapping

```mermaid
graph LR
    subgraph COGNITIVE_INDICES["WAIS-V Index Scores"]
        VCI[VCI: 122<br/>Verbal Comprehension<br/>93rd percentile]
        WMI[WMI: 122<br/>Working Memory<br/>93rd percentile]
        FRI[FRI: 120<br/>Fluid Reasoning<br/>91st percentile]
        PSI[PSI: 120<br/>Processing Speed<br/>91st percentile]
        VSI[VSI: 108<br/>Visual Spatial<br/>70th percentile]
    end
    
    subgraph PROFESSIONAL_ROLES["Where Skills Deploy"]
        TW[Technical Writing<br/>Tier 1 Target]
        COORD[Coordination Roles<br/>Current Path]
        CREATIVE_TECH[Creative Technology<br/>Future Path]
    end
    
    subgraph EVIDENCE_BASE["What Proves It"]
        WRITING[22 Articles<br/>2 Book Credits]
        EVENTS[8+ Years<br/>Live Production]
        COMPOSITION[16 Tracks<br/>97 Minutes]
        SESSION[43-Min Update<br/>Zero Errors]
    end
    
    %% VCI applications
    VCI -->|Primary strength| TW
    WRITING -->|Validates| VCI
    
    %% WMI applications
    WMI -->|Primary strength| COORD
    EVENTS -->|Validates| WMI
    
    %% FRI applications
    FRI -->|Underutilized| CREATIVE_TECH
    COMPOSITION -->|Validates| FRI
    
    %% PSI applications
    PSI -->|Session-validated| TW
    SESSION -->|Proves| PSI
    
    %% VSI limitations
    VSI -.->|Avoid| DESIGN[Graphic Design<br/>CAD/Spatial]
    
    style VCI fill:#3498db,stroke:#2980b9,stroke-width:3px,color:#fff
    style WMI fill:#3498db,stroke:#2980b9,stroke-width:3px,color:#fff
    style FRI fill:#e67e22,stroke:#d35400,stroke-width:3px,color:#fff
    style PSI fill:#e67e22,stroke:#d35400,stroke-width:3px,color:#fff
    style VSI fill:#95a5a6,stroke:#7f8c8d,stroke-width:2px,color:#fff
    style TW fill:#27ae60,stroke:#229954,stroke-width:3px,color:#fff
```

---

## CAREER STRATEGY: FSIQ vs GAI Deployment

```mermaid
graph TD
    subgraph CURRENT_STATE["Current Economic Deployment"]
        FSIQ_USE[FSIQ 117<br/>87th percentile<br/>Coordination Roles]
        COORD_WORK[CHS Events<br/>Freeman Company<br/>WMI 122 Focus]
    end
    
    subgraph TARGET_IMMEDIATE["Immediate Target: Technical Writing"]
        TW_GOAL[Technical Writing<br/>Uses: VCI 122 + PSI 120<br/>$70k-$95k Entry]
        TW_COMPANIES[Tier 1: Atlassian, GitLab<br/>Tier 2: Stripe, Twilio<br/>Tier 3: HubSpot, Notion]
        TW_EVIDENCE[Portfolio: 22 Articles<br/>+ 2 Editorial Credits<br/>+ 8yr Operations Background]
    end
    
    subgraph TARGET_LONGTERM["Long-term: Creative Technology"]
        GAI_USE[GAI 122<br/>93rd percentile<br/>Learning Potential]
        CREATIVE_TECH_GOAL[Algorithmic Composition<br/>Generative Systems<br/>$60k-$130k]
        GRAD_PROGRAMS[MIT Media Lab<br/>NYU ITP<br/>CCRMA Stanford]
    end
    
    subgraph LEARNING_PATHS["Active Learning"]
        AI_PROMPT[AI Prompting<br/>Phase 2<br/>3-5 hrs/week]
        ALGO_COMP[Algorithmic Composition<br/>Month 1<br/>8-10 hrs/week]
    end
    
    %% Current path
    FSIQ_USE --> COORD_WORK
    
    %% Immediate transition
    COORD_WORK -->|Pivot using| TW_EVIDENCE
    TW_EVIDENCE --> TW_GOAL
    TW_GOAL --> TW_COMPANIES
    
    %% Learning path integration
    AI_PROMPT -.->|Professionalizes| TW_GOAL
    
    %% Long-term path
    GAI_USE --> CREATIVE_TECH_GOAL
    CREATIVE_TECH_GOAL --> GRAD_PROGRAMS
    ALGO_COMP -.->|Prepares for| GRAD_PROGRAMS
    
    style FSIQ_USE fill:#95a5a6,stroke:#7f8c8d,stroke-width:2px,color:#fff
    style GAI_USE fill:#e74c3c,stroke:#c0392b,stroke-width:3px,color:#fff
    style TW_GOAL fill:#27ae60,stroke:#229954,stroke-width:3px,color:#fff
    style CREATIVE_TECH_GOAL fill:#9b59b6,stroke:#8e44ad,stroke-width:3px,color:#fff
```

---

## ARCHIVE CROSS-REFERENCE MAP

```mermaid
graph TB
    subgraph MAIN_ARCHIVE["Jeffrey_Wiley_Resume_Archive_v1.5.1"]
        SEC1[1. Contact Info]
        SEC2[2. Professional Summary]
        SEC3[3. Work Experience]
        SEC4[4. Education]
        SEC5[5. Training & Certs]
        SEC6[6. Technical Skills]
        SEC7[7. Portfolio]
        SEC8[8. Cognitive Assessment]
        SEC9[9. Career Paths]
        SEC10[10. AI Instructions]
        SEC11[11. References]
        SEC12[12. Keywords]
        SEC13[13. Achievements]
        SEC14[14. File Locations]
    end
    
    subgraph EXTERNAL_DOCS["External Documents"]
        ALGO_PATH[Algorithmic_Composition<br/>Learning_Path.md]
        AI_PATH[AI_Prompting<br/>Master_Path.md]
        RESUME_PDF[Jeffrey Wiley<br/>Resume 2025.pdf]
        OLD_ARCHIVE[Jeffrey_Wiley<br/>Resume_Archive.md<br/>v1.0]
    end
    
    subgraph ONLINE_EVIDENCE["Online Portfolio"]
        FANSIDED_URL[dorksideoftheforce.com<br/>22 Articles]
        GITHUB_URL[github.com/j-w-code/J3K<br/>Blockchain DAO]
        BANDCAMP_URL[jwdance.bandcamp.com<br/>4 Music Releases]
        AMAZON_URL[Amazon<br/>2 Book ISBNs]
    end
    
    %% Internal references
    SEC2 -->|References| SEC7
    SEC2 -->|References| SEC8
    SEC3 -->|Validated by| SEC7
    SEC8 -->|Informs| SEC9
    SEC9 -->|References| SEC14
    SEC10 -->|References| SEC8
    
    %% External document links
    SEC9 -->|Links to| ALGO_PATH
    SEC9 -->|Links to| AI_PATH
    SEC14 -->|Links to| ALGO_PATH
    SEC14 -->|Links to| AI_PATH
    SEC14 -->|Links to| RESUME_PDF
    SEC14 -->|Links to| OLD_ARCHIVE
    
    %% Online evidence
    SEC7 -->|Verified at| FANSIDED_URL
    SEC7 -->|Verified at| GITHUB_URL
    SEC7 -->|Verified at| BANDCAMP_URL
    SEC7 -->|Verified at| AMAZON_URL
    
    %% Learning paths reference main archive
    ALGO_PATH -.->|Requires| SEC8
    AI_PATH -.->|Requires| SEC3
    
    style MAIN_ARCHIVE fill:#2c3e50,stroke:#3498db,stroke-width:3px
    style EXTERNAL_DOCS fill:#34495e,stroke:#7f8c8d,stroke-width:2px
    style ONLINE_EVIDENCE fill:#16a085,stroke:#1abc9c,stroke-width:2px
```

---

## EVIDENCE VALIDATION CHAIN

```mermaid
graph LR
    subgraph CLAIMS["Archive Claims"]
        CLAIM_VCI[VCI 122<br/>Exceptional Verbal]
        CLAIM_WMI[WMI 122<br/>Superior Working Memory]
        CLAIM_FRI[FRI 120<br/>Superior Fluid Reasoning]
        CLAIM_PSI[PSI 120<br/>Superior Processing Speed]
    end
    
    subgraph EVIDENCE["Verifiable Evidence"]
        EVIDENCE_ARTICLES[22 Published Articles<br/>URLs verified ✓]
        EVIDENCE_BOOKS[2 Editorial Credits<br/>ISBNs verified ✓]
        EVIDENCE_EVENTS[8+ Years Coordination<br/>LinkedIn verified ✓]
        EVIDENCE_SUPERBOWL[Super Bowl LVI<br/>Documented ✓]
        EVIDENCE_MUSIC[16 Tracks, 97 Minutes<br/>Bandcamp verified ✓]
        EVIDENCE_SESSION[43-Min System Update<br/>Timestamped ✓]
    end
    
    subgraph VALIDATION["Ground Truth Status"]
        VALID_VCI[✓ VALIDATED<br/>93rd percentile]
        VALID_WMI[✓ VALIDATED<br/>93rd percentile]
        VALID_FRI[✓ VALIDATED<br/>91st percentile]
        VALID_PSI[✓ CORRECTED<br/>91st percentile<br/>Was: 79th]
    end
    
    %% VCI validation chain
    CLAIM_VCI --> EVIDENCE_ARTICLES
    EVIDENCE_ARTICLES --> VALID_VCI
    CLAIM_VCI --> EVIDENCE_BOOKS
    EVIDENCE_BOOKS --> VALID_VCI
    
    %% WMI validation chain
    CLAIM_WMI --> EVIDENCE_EVENTS
    EVIDENCE_EVENTS --> VALID_WMI
    CLAIM_WMI --> EVIDENCE_SUPERBOWL
    EVIDENCE_SUPERBOWL --> VALID_WMI
    
    %% FRI validation chain
    CLAIM_FRI --> EVIDENCE_MUSIC
    EVIDENCE_MUSIC --> VALID_FRI
    
    %% PSI validation chain
    CLAIM_PSI --> EVIDENCE_SESSION
    EVIDENCE_SESSION --> VALID_PSI
    
    style VALID_VCI fill:#27ae60,stroke:#229954,stroke-width:3px,color:#fff
    style VALID_WMI fill:#27ae60,stroke:#229954,stroke-width:3px,color:#fff
    style VALID_FRI fill:#27ae60,stroke:#229954,stroke-width:3px,color:#fff
    style VALID_PSI fill:#f39c12,stroke:#e67e22,stroke-width:3px,color:#fff
```

---

## SPIKY PROFILE VISUALIZATION

```mermaid
graph TD
    subgraph INDEX_SCORES["WAIS-V Index Scores"]
        VCI_SCORE[VCI: 122<br/>🔵🔵🔵🔵🔵<br/>PEAK]
        WMI_SCORE[WMI: 122<br/>🔵🔵🔵🔵🔵<br/>PEAK]
        FRI_SCORE[FRI: 120<br/>🔵🔵🔵🔵◯<br/>SUPERIOR]
        PSI_SCORE[PSI: 120<br/>🔵🔵🔵🔵◯<br/>SUPERIOR]
        VSI_SCORE[VSI: 108<br/>🔵🔵◯◯◯<br/>AVERAGE]
    end
    
    subgraph COMPOSITES["Composite Scores"]
        FSIQ_COMP[FSIQ: 117<br/>87th percentile<br/>All 5 indices]
        GAI_COMP[GAI: 122<br/>93rd percentile<br/>VCI+VSI+FRI only]
    end
    
    subgraph INTERPRETATION["Profile Analysis"]
        SPIKY_NATURE[Spiky Profile<br/>14-point spread<br/>Functional 10-point]
        STRENGTH_VERBAL[Strength:<br/>Verbal/Memory<br/>93rd percentile]
        STRENGTH_REASONING[Strength:<br/>Reasoning/Speed<br/>91st percentile]
        WEAKNESS_SPATIAL[Moderate:<br/>Visual-Spatial<br/>70th percentile]
    end
    
    VCI_SCORE --> FSIQ_COMP
    WMI_SCORE --> FSIQ_COMP
    FRI_SCORE --> FSIQ_COMP
    PSI_SCORE --> FSIQ_COMP
    VSI_SCORE --> FSIQ_COMP
    
    VCI_SCORE --> GAI_COMP
    FRI_SCORE --> GAI_COMP
    VSI_SCORE --> GAI_COMP
    
    FSIQ_COMP --> SPIKY_NATURE
    GAI_COMP --> SPIKY_NATURE
    
    VCI_SCORE --> STRENGTH_VERBAL
    WMI_SCORE --> STRENGTH_VERBAL
    
    FRI_SCORE --> STRENGTH_REASONING
    PSI_SCORE --> STRENGTH_REASONING
    
    VSI_SCORE --> WEAKNESS_SPATIAL
    
    style VCI_SCORE fill:#3498db,stroke:#2980b9,stroke-width:4px,color:#fff
    style WMI_SCORE fill:#3498db,stroke:#2980b9,stroke-width:4px,color:#fff
    style FRI_SCORE fill:#e67e22,stroke:#d35400,stroke-width:3px,color:#fff
    style PSI_SCORE fill:#e67e22,stroke:#d35400,stroke-width:3px,color:#fff
    style VSI_SCORE fill:#95a5a6,stroke:#7f8c8d,stroke-width:2px,color:#fff
    style GAI_COMP fill:#e74c3c,stroke:#c0392b,stroke-width:3px,color:#fff
    style FSIQ_COMP fill:#27ae60,stroke:#229954,stroke-width:3px,color:#fff
```

---

## USAGE INSTRUCTIONS

### How to View These Diagrams

**Option 1: Mermaid Live Editor (Recommended)**
1. Go to https://mermaid.live/
2. Copy any diagram code block above
3. Paste into the editor
4. Diagram renders instantly
5. Export as PNG/SVG if needed

**Option 2: VS Code**
1. Install "Markdown Preview Mermaid Support" extension
2. Open this file in VS Code
3. Right-click → "Markdown: Open Preview to the Side"
4. Diagrams render in preview pane

**Option 3: GitHub**
1. Push this file to a GitHub repo
2. GitHub natively renders Mermaid diagrams in .md files
3. View directly in browser

### Diagram Reference

- **Master Architecture**: Complete ecosystem overview
- **Domain Breakdown**: Cognitive indices → Professional roles
- **Career Strategy**: FSIQ vs GAI deployment paths
- **Cross-Reference Map**: Archive internal + external links
- **Evidence Validation**: Claims → Evidence → Verification chain
- **Spiky Profile**: Visual index score distribution

---

**File Location:** `C:\Users\jeffr\Documents\Work\Archive_Visual_Map.md`  
**Created:** December 1, 2025  
**Purpose:** Visual companion to Jeffrey_Wiley_Resume_Archive_v1.5.1
