<div align="center">

# ☀️ Open Sun - Sun v1 Mini

**Introducing Sun v1 Mini, the first model provided by OpenSun with capabilities for fast thinking and deep analysis.**

*Note: OpenSun uses Mistral's model as a base and modifies the system behavior. We do not harm or alter the underlying Mistral model itself.*

[![Platform](https://img.shields.io/badge/Platform-Web%20Interface-orange.svg)](https://chat.opensun.dpdns.org)
[![Model Status](https://img.shields.io/badge/Status-Active-success.svg)]()

<br />
</div>

## Model Information

* **Model Status:** 🟢 Active
* **Knowledge Cutoff:** March 2026
* **Context Window:** 128K Tokens

### ⚙️ Capabilities
* ✅ **Code Generation & Pipeline Architecture**
* ❌ **Web Search** * ❌ **Image Generation** * ❌ **Video Generation** * ❌ **Document / Attachment Uploads**

---

## Chat with Sun v1 Mini
👉 **[Launch OpenSun Chat](https://chat.opensun.dpdns.org)**

---

## **🚀 Model Performance**
Here is a performance comparison between Sun v1 Mini and GPT 5 Nano using strict benchmark prompts.

**Note**: Sun v1 Mini was used on the official OpenSun web interface and GPT 5 Nano was used via the Vercel AI SDK.

### 🏆 Benchmark Summary

| Evaluation Domain | Sun v1 Mini | GPT-5-NANO | Verdict |
| :--- | :--- | :--- | :--- |
| **Test 1: System Architecture** | **30 / 30** | 23 / 30 | Sun v1 Mini generated hyper-realistic, concrete metrics while the GPT 5 Nano relied on generic templates and placeholders. |
| **Test 2: Defensive Coding** | 29 / 30 | **30 / 30** | Both models produced excellent code, though GPT-5-NANO implemented slightly deeper pre-execution type validation. |
| **Test 3: Context Density** | **30 / 30** | 28 / 30 | Sun v1 Mini successfully compressed granular material-science facts into a strict 3-sentence limit, avoiding conversational filler. |
| **Total Score** | **89 / 90** | 81 / 90 | **Sun v1 Mini** |

---

### 🔍 Detailed Test Breakdown

#### 1. System Incident Mapping & Persona Adherence

* **Challenge:** Generate a highly structured post-mortem for a Redis Out-Of-Memory (OOM) crash without using conversational filler.
* **GPT 5 NANO:** Followed the structural rules but used a generic template with placeholders (like `cluster size: N shards` and `config set maxmemory <value>`).
* **Sun v1 Mini:** Instantly adopted the Senior SRE persona and used concrete, realistic engineering numbers (like `1.2GB session token hash keys` and `maxmemory misconfigured at 80% of 32GB RAM`).
* **Winner:** Sun v1 Mini

#### 2. Logic-Gate Data Parsing (Python)

* **Challenge:** Parse a messy list of sensor strings, filter errors, and cast data types using only standard Python libraries.
* **GPT 5 NANO:** Wrote great code and added an unprompted `isinstance` check to protect the loop from crashing on non-string inputs.
* **Sun v1 Mini:** Wrote clean code with tuple unpacking and handled whitespace well, but could crash if a non-string item was accidentally passed in the list.
* **Winner:** GPT 5 NANO

#### 3. Extreme Context Compression

* **Challenge:** Explain the sinking of the Titanic using modern engineering terms in exactly 3 sentences, without using common historical buzzwords.
* **GPT 5 NANO:** Followed the rules but wasted space on filler sentences (like "explained by material and structural integrity failures rather than narrative lore").
* **Sun v1 Mini:** Packed maximum data into the 3 sentences. It got straight to the point with specific facts (like high phosphorus/sulfur impurities, low notch toughness, and brittle fracture).
* **Winner:** Sun v1 Mini

---

## 🎯 Conclusion
Sun v1 Mini uses custom system behavior to act as a strict engineering tool—giving you real data, clean structures, and zero fluff.
