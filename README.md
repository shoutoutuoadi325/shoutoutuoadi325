## Published Apps

| App | Description | Links |
| --- | --- | --- |
| **Numpad9 · 九键输入法** | Offline Chinese Pinyin and English input using a numeric keypad, with candidate selection and paging. | [Source code](https://github.com/shoutoutuoadi325/Numpad9) · [Microsoft Store](https://apps.microsoft.com/detail/9n82m2s3qs4c) |
| **KeyBridge** | Configurable Command-style shortcuts for Windows, with application-specific settings and local keyboard processing. | [Source code](https://github.com/shoutoutuoadi325/keybridge) · [Microsoft Store](https://apps.microsoft.com/detail/9nk4xxk1jh04) |
| **Qinglan: Path of Ascension** | A free, offline, single-player 3D xianxia action game for Windows and Apple Silicon macOS, featuring sword combat, Five Elements abilities, and cultivation progression. | [Source code](https://github.com/shoutoutuoadi325/qinglan-wendao) · [Microsoft Store](https://apps.microsoft.com/detail/9nglsm7p5cmb) |

[View all apps on Microsoft Store](https://apps.microsoft.com/search/publisher?name=Zhiqi+Zhang)

## Selected Open-Source Contributions

<details>
<summary>View all merged pull requests</summary>

| Repository | PR | Summary |
| --- | --- | --- |
| [TensorFlow](https://github.com/tensorflow/tensorflow) | [#129941](https://github.com/tensorflow/tensorflow/pull/129941) | Fixed Jacobian output dtypes for mixed-precision differentiation, restoring non-vectorized computation and correcting zero outputs for disconnected batch gradients. |
| [OpenClaw](https://github.com/openclaw/openclaw) | [#168375](https://github.com/openclaw/openclaw/pull/168375) | Discovered and fixed `oc-path` recursive-wildcard bugs that skipped direct matches and duplicated results. |
| [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh) | [#14161](https://github.com/ohmyzsh/ohmyzsh/pull/14161) | Discovered and fixed Python 3.10+ parsing in `pyuserpaths` using longest-match expansion, restoring user site-packages paths. |
| [Three.js](https://github.com/mrdoob/three.js) | [#35288](https://github.com/mrdoob/three.js/pull/35288) | Fixed quaternion tangent transforms in glTF cubic spline additive animations, preventing distorted interpolation. |
| [Ant Design](https://github.com/ant-design/ant-design) | [#59351](https://github.com/ant-design/ant-design/pull/59351) | Filled missing DatePicker and TimePicker placeholders and Carousel arrow accessibility labels across 28 locales. |
| [vLLM](https://github.com/vllm-project/vllm) | [#55669](https://github.com/vllm-project/vllm/pull/55669) | Fixed missing argument prefixes in Jamba streaming tool calls by tracking arguments already sent to the client, preventing invalid JSON. |
| [Vite](https://github.com/vitejs/vite) | [#23609](https://github.com/vitejs/vite/pull/23609) | Fixed percent-encoded `srcset` URL resolution in HTML builds, preventing missing assets and double encoding. |
| [Astro](https://github.com/withastro/astro) | [#18002](https://github.com/withastro/astro/pull/18002) | Discovered and fixed dynamic redirect corruption when route parameters contained JavaScript `$` replacement patterns, using callback-based literal substitution. |
| [Ultralytics (YOLO)](https://github.com/ultralytics/ultralytics) | [#26575](https://github.com/ultralytics/ultralytics/pull/26575) | Discovered and fixed missing `~=` lower-bound checks; also preserved version constraints after extras, preventing incompatible installed versions from being silently accepted. |
| [Hugging Face Diffusers](https://github.com/huggingface/diffusers) | [#14542](https://github.com/huggingface/diffusers/pull/14542) | Fixed distributed learning-rate scheduler calculations in the Kandinsky 2.2 decoder training script. |
| [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) | [#4598](https://github.com/openai/openai-agents-python/pull/4598) | Discovered and fixed a Realtime conversation-history regression by preserving server-reported item statuses during retrieval. |
| [MLX](https://github.com/ml-explore/mlx) | [#4324](https://github.com/ml-explore/mlx/pull/4324) | Fixed `mx.arange` silent saturation and wraparound for out-of-range inferred integers by widening them to `int64`. |
| [Angular](https://github.com/angular/angular) | [#71766](https://github.com/angular/angular/pull/71766) | Fixed resource cancellation when parameters become unavailable, aborting obsolete loads and releasing pending tasks that could block application stability. |
| [Puppeteer](https://github.com/puppeteer/puppeteer) | [#15731](https://github.com/puppeteer/puppeteer/pull/15731) | Fixed detached DOM-node leaks in ARIA queries by disposing temporary CDP binding handles while preserving exposed-function handle ownership. |
| [frp](https://github.com/fatedier/frp) | [#5608](https://github.com/fatedier/frp/pull/5608) | Fixed a port allocation race during proxy reconnection, preventing reuse of ports already acquired by another proxy before socket binding. |
| [Elixir](https://github.com/elixir-lang/elixir) | [#15888](https://github.com/elixir-lang/elixir/pull/15888) | Discovered and fixed misleading type-checker warnings from macro-generated clauses by marking four type-check macro expansions as generated. |
| [Farama Foundation Gymnasium](https://github.com/Farama-Foundation/Gymnasium) | [#1666](https://github.com/Farama-Foundation/Gymnasium/pull/1666) | Discovered and fixed biased integer sampling near `int8`/`int16`/`int32` limits by restricting float64 safety clipping to `int64`. |
| [Knip](https://github.com/webpro-nl/knip) | [#2042](https://github.com/webpro-nl/knip/pull/2042) | Fixed false unused-dependency reports for Node scripts by recognizing valueless CLI flags, with regression tests. |
| [Hugging Face Accelerate](https://github.com/huggingface/accelerate) | [#4307](https://github.com/huggingface/accelerate/pull/4307) | Reported and fixed a tuple-padding crash in `split_between_processes` by preserving tuple type during padding. |
| [FlashInfer](https://github.com/flashinfer-ai/flashinfer) | [#4401](https://github.com/flashinfer-ai/flashinfer/pull/4401) | Fixed FA2 attention failures on extreme negative logits and prevented NaNs in fully masked rows and empty split-KV states. |
| [Hugging Face Hub](https://github.com/huggingface/huggingface_hub) | [#4711](https://github.com/huggingface/huggingface_hub/pull/4711) | Discovered and fixed a CLI regression that silently skipped wildcard uploads by correcting upload-path resolution. |

</details>
