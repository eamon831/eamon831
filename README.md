# MD Saiful Hossain

Software engineer in Dhaka, Bangladesh. Four years building cross-platform mobile apps at **Lazycoders LLC**, and increasingly building the AI systems around them.

### Mobile

Flutter and Dart across Android and iOS, with apps live on both stores.

The project I maintain is **Appza**, a no-code app builder for WordPress. The interesting part is a custom **JSON-to-Flutter rendering engine** that turns a site's configuration into a running app, with integrations for WooCommerce, TutorLMS, LearnDash and Fluent Community. We are a two-person mobile team and I am the senior one, so I own the architecture and mentor the junior developer.

Before that, **Nourish**: offline-first veterinary data collection for low-connectivity field work. 100+ SQLite tables, 90+ consolidated APIs. When the network is unreliable, sync conflict handling stops being a detail and becomes the product.

On the commerce side: dynamic product variant selection, and subscriptions and in-app purchases through **RevenueCat**.

State management with **GetX** in production, **Riverpod** on new work, **BLoC** where it fits.

### Release engineering

I own production releases end to end: signing, versioning, staged rollout, and iOS publishing automated with **Fastlane** and the App Store Connect API.

### AI systems

Two personal projects drive most of what I have learned recently.

**Studio-Ops** is an autonomous video studio built on **OpenClaw**, where a director agent coordinates per-channel bots and git serves as the shared memory between them. It produced twelve videos end to end before I paused it on GPU credits. Generation sits behind an adapter, currently LTX 2.3, Wan 2.2 and Flux.2 through the ComfyUI API, with thirty benchmarked workflow variants behind the model choices rather than guesswork.

**Master Mosai** is a retrieval service in Python: FastAPI, ChromaDB, LangChain chunking, Ollama embeddings, Redis and Postgres, with 128 tests.

Some of that work is public here — see [`runpod-comfyui-worker`](https://github.com/eamon831/runpod-comfyui-worker), a RunPod serverless worker for ComfyUI video generation.

### Background

BSc in Computer Science and Engineering, Uttara University. 166 Codeforces contests through university, and onsite inter-university programming contests at BUET, AUST and RUET. English at C1 (PTE Academic 67).

Open to Flutter and AI engineering roles, remote or with relocation.

### Contact

- LinkedIn: https://www.linkedin.com/in/saiful-hossain-cs/
- Portfolio: https://eamon831.github.io/
- Email: mdsaiful.rbs@gmail.com
