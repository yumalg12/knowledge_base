
단순 유명인 목록이 아니라 **LiB 논문을 읽을 때 저자 이름만 보고도 연구 계보와 관점이 연결되도록** 정리해보겠습니다.

### LiB 연구자 계보도

| 분야 | 기반을 만든 연구자 | 이후 핵심 연구자/그룹 | 이름을 보면 떠올릴 것 |
|---|---|---|---|
| **LIB 기원** | Whittingham | Goodenough → Yoshino | intercalation → high-V cathode → practical LIB |
| **Layered oxide** | Goodenough | Thackeray → Ceder / Sun / Meng | LCO, NCM/NCA, 구조 안정성 |
| **Ni-rich cathode** | — | **Yang-Kook Sun**, Khalil Amine, Shirley Meng | Ni-rich NCM, gradient, degradation |
| **Li-rich / O-redox** | Thackeray | **Peter Bruce**, Ceder, Grey | Li-rich, oxygen redox, O loss |
| **Graphite anode** | **Rachid Yazami** | Dahn → Winter / Aurbach | graphite staging, SEI |
| **SEI** | **Emanuel Peled** | **Aurbach → Kang Xu** | SEI → electrolyte decomposition → interphase chemistry |
| **Electrolyte** | **Michel Armand** | Aurbach / Kang Xu / Passerini | salt, solvent, solvation, additives |
| **Polymer electrolyte** | **Armand** | Passerini 등 | PEO, Li-salt, polymer ionics |
| **Operando 분석** | — | **Clare Grey**, Chueh, Meng | NMR, XAS, heterogeneity |
| **계산재료과학** | — | **Gerbrand Ceder** | DFT, phase stability, materials discovery |
| **수명/열화** | — | **Jeff Dahn**, Chueh | parasitic reactions, CE, lifetime |
| **Solid-state** | — | **Jürgen Janek**, Peter Bruce, Meng | SSE/electrode interface |
| **Li metal** | — | Aurbach, Cui, Archer 등 | plating, dendrite, SEI |

이걸 조금 더 구체적으로 보면 다음처럼 연결됩니다.

---

## 1. 양극재 계보

**John Goodenough**
→ 여기서 사실상 현대 oxide cathode 계보가 출발합니다.

**Goodenough**
→ LiCoO₂  
→ layered transition-metal oxide  
→ NCA / NCM 계열

그리고 이후 연구가 크게 갈립니다.

**Gerbrand Ceder**
→ thermodynamics  
→ phase stability  
→ cation ordering  
→ DFT  
→ materials discovery

즉 Ceder 논문에서는 단순히 "성능이 좋아졌다"보다 **왜 그 조성과 구조가 안정한가**를 보는 시각이 강합니다.

반면,

**Yang-Kook Sun**
→ Ni-rich NCM  
→ concentration-gradient  
→ core-shell / full-gradient  
→ high-Ni cathode stabilization

즉 **실제 고에너지밀도 Ni-rich cathode 설계**의 흐름에서 매우 중요한 계보입니다.

그리고

**Peter Bruce / Clare Grey / William Chueh**

쪽으로 가면 관심사가 조금 달라집니다.

> 충방전하면서 실제 결정구조와 산소와 TM에 무슨 일이 일어나는가?

라는 쪽입니다.

특히

**Bruce**
→ Li-rich  
→ oxygen redox  
→ O loss  
→ structural rearrangement

**Grey**
→ NMR / operando characterization  
→ local environment  
→ reaction mechanism

**Chueh**
→ spatial heterogeneity  
→ particle-to-particle reaction  
→ local SOC  
→ chemo-mechanical degradation

으로 기억하면 상당히 편합니다.

---

## 2. Electrolyte → SEI/CEI 계보

여기는 역사적으로 이름을 연결해서 알아두는 게 좋습니다.

### Emanuel Peled
**SEI 개념**

1970년대에 alkali-metal/non-aqueous electrolyte 계면을 설명하기 위해 **solid electrolyte interphase model**을 제안한 사람입니다.

그래서

**Peled = SEI**

라고 거의 공식처럼 기억하면 됩니다.

↓

### Doron Aurbach

이 개념을 실제 Li/graphite battery chemistry와 연결하여 엄청나게 발전시킨 연구자입니다.

**Aurbach = surface chemistry + electrolyte decomposition + SEI**

XPS/FTIR/electrochemistry 등을 이용해

> 전해액이 어떤 물질로 분해되고  
> 어떤 surface film을 만들며  
> 그것이 전극 거동에 어떻게 영향을 미치는가

를 연구하는 계보입니다.

↓

### Kang Xu

여기서 electrolyte 자체를 더 molecular level로 들어갑니다.

**Kang Xu = solvation → electrolyte chemistry → interphase**

즉,

Li⁺ solvation structure  
→ anion/solvent reduction·oxidation  
→ SEI/CEI composition  
→ electrochemical stability

라는 현대적인 electrolyte–interphase 연결입니다.

그래서 논문에서

> LiPF₆ decomposition  
> LiF  
> LixPOyFz  
> PF₅  
> solvent decomposition  
> CEI

같은 것을 보고 있다면 **Aurbach / Kang Xu 계열 문헌을 상당히 자주 만나게 됩니다.**

---

# 3. 배터리 수명 연구

여기서는 **Jeff Dahn**을 따로 기억해두는 게 좋습니다.

Dahn의 중요한 특징은

> 배터리를 반드시 죽을 때까지 돌려봐야 수명을 알 수 있는가?

라는 문제입니다.

그래서

**high-precision coulometry**

를 이용해 아주 작은 parasitic reaction을 측정하고,

CE  
→ charge endpoint capacity slippage  
→ electrolyte oxidation/reduction  
→ impedance  
→ long-term lifetime

등을 연결합니다.

따라서

**Dahn = electrolyte + parasitic reaction + high precision + lifetime**

정도로 기억하면 됩니다.

Calendar aging이나 electrolyte degradation을 한다면 꽤 중요한 계보입니다.

---

# 4. Characterization 계보

여기서 한 명만 먼저 외운다면

## Clare Grey

입니다.

**Grey = battery NMR**

라고 시작하면 됩니다.

그런데 현재는 단순 NMR 연구자라기보다

**operando battery characterization**

의 대표적인 연구자 중 하나로 보는 것이 적절합니다.

즉 기존 방식이

충전 → 해체 → XPS/XRD → "아마 이런 일이 일어났을 것이다"

였다면,

Grey 계열은

충전 중  
↓  
Li 이동  
↓  
local structure 변화  
↓  
phase transformation

을 직접 추적하려는 방향입니다.

이 계열이 현재의 **operando/in situ characterization** 발전에 큰 영향을 미쳤습니다.

---

# 5. 계산을 한다면 Ceder는 거의 필수

## Gerbrand Ceder

배터리 소재 연구와 computational materials science를 강하게 결합한 대표적인 연구자입니다.

대표적으로 연결해야 할 개념은

**DFT**  
**phase diagram**  
**cluster expansion**  
**cation ordering**  
**voltage prediction**  
**high-throughput screening**

입니다.

특히 layered oxide에서

> 왜 이 조성이 안정한가?  
> 왜 이 TM arrangement가 나타나는가?  
> vacancy formation energy는 어떠한가?  
> delithiation에 따라 구조가 어떻게 변하는가?

같은 질문은 Ceder 계열 연구와 상당히 맞닿아 있습니다.

---

# 6. Solid-state battery

여기는 계보가 조금 별도로 형성됩니다.

대표적으로

**Jürgen Janek**  
**Peter Bruce**  
**Shirley Meng**

정도는 알아두는 것이 좋습니다.

Janek의 경우 특히

**solid–solid interface**

가 핵심입니다.

SSE 자체의 ionic conductivity만 보는 게 아니라

SSE | cathode  
SSE | Li

계면에서 발생하는

space-charge  
interphase formation  
contact loss  
chemo-mechanical degradation

등을 다룹니다.

그래서 **interface degradation** 관점에서 읽을 만한 논문이 많습니다.

---

# 7. Li metal로 넘어가면

여기서는 연구자 풀이 다시 달라집니다.

**Doron Aurbach**
→ Li surface chemistry

**Yi Cui**
→ Li metal / Si / nanostructured electrodes / interface engineering

**Lynden Archer**
→ Li metal / electrolyte / dendrite

그리고 더 넓게 보면 Li-metal electrolyte 연구에서 **Y. Shirley Meng, Kang Xu** 등의 이름도 계속 겹칩니다.

---

# 결국 머릿속에는 이렇게 있어야 합니다

```text
                         Li-ion battery
                               │
        ┌──────────────────────┼─────────────────────┐
        │                      │                     │
     Cathode                Electrolyte            Anode
        │                      │                     │
   Goodenough                Armand                Yazami
        │                      │                     │
   ┌────┴────┐            ┌────┴────┐              │
 Ceder      Sun          Peled    Aurbach          Dahn
   │          │            │         │               │
DFT/       Ni-rich        SEI    surface chem.   graphite/
design      NCM                     │             lifetime
                                     │
                                  Kang Xu
                                     │
                           solvation/interphase
```

그리고 characterization 쪽에서 이 전체를 가로지르는 사람들이

**Clare Grey — local structure / NMR / operando**  
**William Chueh — heterogeneity / operando / degradation**  
**Shirley Meng — advanced characterization / cathode / interface**

라고 생각하면 큰 틀이 잡힙니다.
