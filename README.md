# 🌊 WaveMaker 

**The Unified Brain for Brand Content Assets in the AI-Native Era.**

[![Status](https://img.shields.io/badge/Status-Private_Beta-blue.svg)]()
[![Architecture](https://img.shields.io/badge/Architecture-Agentic_Workflow-green.svg)]()
[![Industry](https://img.shields.io/badge/Industry-FMCG_%2F_Retail-orange.svg)]()

> "WaveMaker is not a traditional DAM or CMS. We don't just manage files and workflows; we manage **Understanding**—understanding of the brand, the audience, and why content performs well, driving content production across all channels."

## 💡 The Problem: Content Schizophrenia

Today, a consumer brand with 500M+ RMB in revenue scatters its content assets across at least 6 battlefields: Performance Ads (Qianchuan), Seeding (Xiaohongshu/Douyin), E-commerce, Live-streaming, Influencers, and Brand Campaigns.

Each team fights its own battle.
The winning hook in a performance ad doesn't flow to the Xiaohongshu seeding team. The pain-point description validated in a viral post doesn't automatically update the e-commerce product page. Six teams, facing the same brand and consumers, are blindly reinventing the wheel. 

This is not an execution issue; it is a structural defect caused by the lack of a unified brain. WaveMaker is the cure.

## 🏗️ Core Architecture 

WaveMaker is built on a robust 3-layer architecture, utilizing Agentic workflows to bridge data silos:

### Layer 1: Brand Content Graph (The Brain)
The dynamic foundation that continuously answers 5 core questions based on real-time data:
- **Identity:** What is the brand? (Dynamic validation of brand guidelines)
- **Products:** What are we selling? (Omni-channel USP heatmaps)
- **Audience:** Who are we talking to? (Cross-channel behavioral tracking)
- **History:** What have we said? (Structured historical data & attribution)
- **Market:** What is happening? (Competitor intelligence monitoring)

### Layer 2: Omni-channel Taxonomy (The Language)
A unified 4-layer taxonomy that allows all channel engines to "speak" to each other:
1. **Intent Layer:** Awareness, Interest, Trust, Conversion, Retention.
2. **Structure Layer:** E.g., Hook -> Body -> CTA.
3. **Presentation Layer:** Visuals, tone of voice, pacing.
4. **Metadata Layer:** Cross-channel adaptation mapping, performance metrics.

### Layer 3: Channel Content Engines (The Execution)
Specialized Agent clusters for each battlefield:
- 🚀 **MUSE Engine (Performance Ads):** Competitor insight, script generation, automated ROI attribution.
- 🌱 **Seeding Engine (Xiaohongshu/Douyin):** Topic recommendation, influencer matching, viral pattern recognition.
- 🛒 **E-commerce Engine:** Dynamic product page optimization based on omni-channel USP data.
- 🎙️ **Live-streaming Engine:** Automated script generation and highlight-clipping for ad recycling.
- 👑 **Brand Content Engine:** Brief generation and tone-consistency checking.

## 🧠 Technical Moat: Data Structure Demo

To achieve "Content Routing Intelligence," we abstract unstructured content into highly structured data blocks. 

*Below is a simplified JSON representation of how WaveMaker parses a high-converting Xiaohongshu post to automatically generate a Qianchuan Ad Hook:*

```json
{
  "asset_id": "XHS-202602-09A",
  "source_channel": "Xiaohongshu",
  "taxonomy": {
    "intent_layer": "Pain-point Trigger -> Trust",
    "structure_layer": {
      "hook": "Who else is wiping their phone screen with their sleeve?",
      "body": "Deeyeo wet wipes deep cleaning test...",
      "cta": "Link in bio"
    },
    "presentation_layer": {
      "tone": "Relatable / Best-friend style",
      "visual": "Close-up macro shot"
    }
  },
  "omni_routing_action": {
    "target_channel": "Qianchuan_Ads",
    "adaptation_strategy": "Extract `structure_layer.hook` -> Re-generate video script with `expert` tone -> Push to MUSE Engine"
  }
}
```

## 🚀 Go-to-Market & Expansion Roadmap

**Ideal Customer Profile (ICP):** Consumer brands with 50M+ RMB annual revenue (prioritizing skincare, food & beverage, apparel, home, etc.), with an in-house content team of 5+ members, and strict data security requirements.

WaveMaker adopts an agile deployment path of "single-engine validation, phased expansion, and continuous graph enrichment":

- [x] **Phase 1: MUSE Performance Ad Engine Validation**
  - The MUSE engine has completed client validation, laying the groundwork for omni-channel expansion.
- [ ] **Phase 2: Seeding Content Engine Launch**
  - The most natural next step, as seeding and performance ads share the strongest synergy. 
- [ ] **Phase 3: E-commerce Content Engine Launch**
  - Optimizing e-commerce product page USP rankings becomes data-driven using converging performance and seeding data.
- [ ] **Phase 4: Live-streaming Content Engine Launch**
  - Live stream highlights become premium sources for ad creatives, forming a complete closed data loop.
- [ ] **Phase 5: Brand Content Engine Launch**
  - The system provides unprecedented data support for brand campaigns.

> **💡 The Network Effect:**
> Every time a new engine is deployed, the value of existing engines increases synchronously. The second engine provides more than twice the value of the first. This is an exponential network effect, not a linear addition.

## 🛡️ The Ultimate Vision

What we ultimately deliver to our clients is not "just another handy SaaS tool," but a continuously appreciating **Brand Content Agent**.

It understands all the content experiences of the brand across all channels. It never resigns, never forgets, and never has a bias. It gets smarter with every use—every new piece of content produced and every data point fed back deepens its understanding of the brand.

**In the AI era, this Agent is the true moat for brand growth.**

---
*Note: This repository currently serves as the architectural overview and open-standard taxonomy documentation for WaveMaker. Core proprietary Agent workflows and engine source code are maintained in private repositories.*
