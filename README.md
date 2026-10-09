# Data-Smartread-AI

Dữ liệu mô hình trí tuệ nhân tạo ngoại tuyến (Offline AI Engine Models) phục vụ ứng dụng đọc sách thông minh **SmartRead AI**.

## Cấu trúc thư mục

### 1. `vieneu/` - Mô hình Tiếng Việt (VieNeu V3 Turbo AI)
- `config.json`
- `tokenizer.json`
- `voice_catalog.json`
- `voices_v3_turbo.json`
- `vieneu_prefill.onnx`
- `vieneu_decode_step.onnx`
- `vieneu_acoustic_cached.onnx`
- `vieneu_backbone_shared.data`
- `vieneu_v3_heads.json`
- `vieneu_v3_heads.f32`
- `moss_audio_tokenizer_decode_full.onnx`
- `moss_audio_tokenizer_decode_shared.data`
- `sea_g2p.bin`

### 2. `supertonic/` - Mô hình đa ngôn ngữ (Supertonic 3 AI)
- `onnx/duration_predictor.onnx`
- `onnx/text_encoder.onnx`
- `onnx/vocoder.onnx`
- `onnx/vector_estimator.onnx`
- `onnx/tts.json`
- `onnx/unicode_indexer.json`
- `voice_styles/` (M1 - M5, F1 - F5)

### 3. Gói nén cài đặt ngoại tuyến (.zip Data Packs)
- `vieneu_data_pack.zip` (~171 MB)
- `supertonic_data_pack.zip` (~355 MB)

## Tải về ứng dụng
Ứng dụng SmartRead AI hỗ trợ tự động tải các tệp tin này hoặc nhập tệp ZIP trực tiếp từ máy để sử dụng 100% offline.
