PyTorch GS: temporally conditioned 3D Gaussian splatting for BlendedMVS. Multi-scale CNN + GRU predicts dynamic Gaussian deformation; differentiable splat renderer trains with photometric (L1+SSIM), temporal/geo losses and optional weak cues. Saves previews, PSNR/SSIM/LPIPS metrics and ablations.

BlendedMVS Dataset Sample
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/1ed254cc-83d7-4a6b-9edd-5cc433c3a8f6" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/7c8608af-0db7-46ac-a84b-83188c7649f8" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/64cab36a-3344-4949-ab59-64abad614825" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/6699c5ed-0447-4302-ab91-bb1821cd82e3" />

<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/00ca0bb6-f39d-46e7-b87b-00552d28c12e" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/76ad5047-facf-42e8-a421-a1f611cd5fb8" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/74277b66-903c-4dfa-b208-32cec2bbc96e" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/80da2d28-517b-4d91-8427-0d222a22993f" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/101ca01c-a31e-4719-b3fb-0f79adabc0e7" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/0902f027-879f-42b1-8724-2fd4195c8e2b" />

<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/f32d899e-83e7-45b4-8ba8-f09602d8044f" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/a65c130d-da26-45a3-b8df-eb486403611a" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/d9fc816f-a48e-445f-bcbf-0b1753998791" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/9621e68c-2112-4d46-a53a-34907fb4e2ff" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/860b465f-db87-4348-8f96-57a466ba1a28" />

<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/42ede679-a425-4028-8614-a1727affea6a" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/519e6aef-335e-4b2d-864c-d0f31149490d" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/b6a65f7a-a9e0-4ea3-ae05-ade02c757893" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/e4288911-500e-45a6-8f8c-3bf23d575654" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/d5c0fe95-acae-49ca-ad9c-607628f1cad9" />

<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/ae008064-40e1-474f-97bf-3d433c2ac510" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/d99e2fbd-ef46-4f1d-bfc1-a9b1665f314d" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/a01cbd2e-3f8a-4d8c-877b-9679d73e250c" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/16af608d-10b8-4c60-9e5f-7bfea6931f48" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/dd404e53-79c6-4778-b900-00664d73c3b3" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/b813c5c0-490a-45a1-a311-a298c90808b1" />

<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/8f459019-4044-4764-9c5b-62d1c83e5f11" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/736782a5-5ad6-4f6f-a12a-cfb9acd17af5" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/f9141f05-22fe-4263-ad5a-e80d27c474d4" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/d94106b9-3a8c-41f6-b5bf-4954c89683ac" />

<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/902ffe88-69d4-473b-91c0-49d8ceb1d8b9" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/f032d3e4-6185-455a-9d9b-8b9f1866410e" />
<img width="768" height="576" alt="Image" src="https://github.com/user-attachments/assets/deb30466-c382-48b4-ae0e-2ee46d746488" />
