# ⚙️ Perbandingan FP16, FP32, dan AMP pada Pelatihan Model Deep Learning Sederhana

Proyek ini bertujuan untuk membandingkan **kecepatan pelatihan** antara tiga mode presisi floating-point di PyTorch:

- **FP16 (Half Precision)**
- **FP32 (Full Precision)**
- **AMP (Automatic Mixed Precision)**

        FP16      FP32      AMP
  loss  Nan       Ada        Ada
  Time  29.78s    44.66s    31.82

  *nilai loss menandakan presisi sebuah mode, apabila nan berarti presisinya sangat rendah jika ada menandakan presisinya bagus
  *time menandakan kecepatan model dalam melatih data
  
