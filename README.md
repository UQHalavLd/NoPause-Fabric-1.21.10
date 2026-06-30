# ⚡ NoPause (Fabric 1.21.10) ⚡

<p align="center">
  <img src="son.png" alt="NoPause Showcase" width="600" />
</p>

<p align="center">
  <i><b>EN:</b> I tried to talk with the owner of the mod but he is an asshole, so I didn't mention him.</i><br>
  <i><b>TR:</b> Modun sahibiyle konuşmaya çalıştım ama tam bir pislik; o yüzden kendisinden bahsetmedim.</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Minecraft-1.21.10-green?style=for-the-badge&logo=minecraft&logoColor=white" />
  <img src="https://img.shields.io/badge/Fabric-Loader-blue?style=for-the-badge&logo=fabric&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Optimized-orange?style=for-the-badge" />
</p>

---

### 📖 Overview / Genel Bakış

| 🇬🇧 English | 🇹🇷 Türkçe |
| :--- | :--- |
| An updated, lightweight Fabric mod that prevents Minecraft from automatically pausing the game when it loses focus (e.g., when you press `Alt+Tab` or switch windows). | Minecraft'ın odak kaybolduğunda (örneğin `Alt+Tab` yaptığınızda veya pencere değiştirdiğinizde) oyunu otomatik olarak duraklatmasını engelleyen, hafif bir Fabric modudur. |
| This repository contains a **fixed and bytecode-optimized release** specifically modified to run smoothly on **Minecraft 1.21.10**, resolving critical crashes caused by version-specific Mojang mappings. | Bu depo, orijinal modun **Minecraft 1.21.10** sürümündeki haritalama (mapping) uyumsuzluklarından kaynaklanan çökme hatalarını çözmek amacıyla bytecode seviyesinde düzenlenmiş sürümünü içerir. |

---

### ✨ Features / Özellikler

* **🚀 Background Play / Arka Planda Akış**
  * `EN:` Keep your game running smoothly in the background while multitasking or being AFK.
  * `TR:` Siz arkada başka işlerle uğraşırken veya AFK iken oyununuz arka planda akmaya devam eder.
* **🛠️ 1.21.10 Compatibility / Tam Uyumluluk**
  * `EN:` Patched severe initialization crashes related to Fabric's `KeyBindingHelper` and Mojang mappings.
  * `TR:` Sürüm değişikliklerinden dolayı oyunun açılışta çökmesine neden olan tuş atama kütüphane hataları tamamen yamandı.
* **🪶 Lightweight & Clean / Hafif ve Sade**
  * `EN:` Stripped down from breaking dependencies to ensure maximum performance and friction-free launching.
  * `TR:` Çakışma yaratan eski bağımlılıklar temizlendi, böylece mod en sade ve kararlı haliyle çalışır.

---

### 🚀 Usage & Commands / Kullanım ve Komutlar

> [!IMPORTANT]
> **EN:** The mod is need to be enabled using: `/nopause enable`  
> **TR:** Modun etkinleştirilmesi için şu yöntem kullanılmalıdır: `/nopause enable`

* `/nopause enable` 
  * `EN:` Ensures the mod is active and running perfectly.
  * `TR:` Modun aktif ve çalışır durumda olduğundan emin olur.

> [!WARNING]
> **Technical Note / Teknik Not:**  
> * **EN:** Due to a specific mapping conflict with the chat packet system in 1.21.10, running the disable routine might cause a client crash. It is highly recommended to leave the mod on 'enable' (default).
> * **TR:** 1.21.10 sürümündeki sohbet paketi sisteminin haritalama farklılıklarından dolayı, oyun içinden `/nopause disable` komutunu çalıştırmak çökme (crash) yaratabilir. Modu sürekli 'enable' (aktif) konumda bırakmanız tavsiye edilir.

---

### 🛠️ How to Install / Nasıl Kurulur?

```yaml
1. [EN] Make sure you have the latest Fabric Loader installed for 1.21.10.
   [TR] Minecraft 1.21.10 için en güncel Fabric Loader'ın kurulu olduğundan emin olun.

2. [EN] Drop the compiled .jar file into your .minecraft/mods directory.
   [TR] Derlenmiş .jar dosyasını .minecraft/mods klasörünüzün içine atın.

3. [EN] Launch the game and enjoy seamless multitasking!
   [TR] Oyunu başlatın ve pencereler arası rahatça geçiş yapmanın keyfini çıkarın!
