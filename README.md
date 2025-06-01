# portofolio-febi
 <html lang="id">
 <head>
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title>Portofolio Febi Handika Putra</title>
     <script src="https://cdn.tailwindcss.com"></script>
     <style>
         /* Mengatur font default menjadi Inter dan memastikan elemen memiliki sudut membulat */
         body {
             font-family: 'Inter', sans-serif;
             background-color: #f3f4f6; /* Warna latar belakang abu-abu muda */
             color: #374151; /* Warna teks gelap */
         }
         .container {
             max-width: 960px; /* Lebar maksimum konten */
             margin: 2rem auto; /* Margin atas/bawah dan tengah secara horizontal */
             padding: 1.5rem; /* Padding di dalam container */
             background-color: #ffffff; /* Latar belakang putih untuk konten utama */
             border-radius: 1.5rem; /* Sudut membulat */
             box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05); /* Bayangan lembut */
         }
         .section-title {
             border-bottom: 2px solid #e5e7eb; /* Garis bawah untuk judul bagian */
             padding-bottom: 0.75rem; /* Padding bawah judul */
             margin-bottom: 1.5rem; /* Margin bawah judul */
             color: #1f2937; /* Warna teks judul yang lebih gelap */
         }
         .card {
             background-color: #f9fafb; /* Latar belakang kartu yang sedikit lebih terang */
             border-radius: 1rem; /* Sudut membulat untuk kartu */
             padding: 1.5rem; /* Padding di dalam kartu */
             margin-bottom: 1.5rem; /* Margin bawah kartu */
             box-shadow: 0 1px 3px 0 rgba(0, 0, 0, 0.1), 0 1px 2px 0 rgba(0, 0, 0, 0.06); /* Bayangan kartu */
         }
         .list-item {
             margin-bottom: 0.5rem; /* Margin bawah untuk item daftar */
         }
         .image-placeholder {
             background-color: #d1d5db; /* Warna abu-abu untuk placeholder gambar */
             display: flex;
             align-items: center;
             justify-content: center;
             color: #6b7280;
             font-weight: bold;
             text-align: center;
             border-radius: 0.75rem; /* Sudut membulat untuk gambar */
             overflow: hidden; /* Memastikan gambar tidak keluar dari batas */
         }
         .image-placeholder img {
             width: 100%;
             height: 100%;
             object-fit: cover; /* Memastikan gambar mengisi area tanpa distorsi */
         }
     </style>
 </head>
 <body>
     <div class="container">
         <header class="text-center mb-8">
             <div class="w-32 h-32 mx-auto mb-4 image-placeholder rounded-full overflow-hidden border-4 border-blue-500">
                 <img src="https://placehold.co/128x128/D1D5DB/6B7280?text=Foto+Profil+Febi" alt="Foto Profil Febi Handika Putra">
             </div>
             <h1 class="text-4xl font-bold text-gray-900 mb-2">FEBI HANDIKA PUTRA</h1>
             <p class="text-xl text-gray-700 mb-4">Fresh Graduate S1 - Teknik Perminyakan</p>
             <div class="flex justify-center space-x-6 text-gray-600">
                 <a href="tel:+6282257473851" class="flex items-center hover:text-blue-600 transition duration-300">
                     <svg class="w-5 h-5 mr-1" fill="currentColor" viewBox="0 0 20 20"><path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.774a11.037 11.037 0 006.103 6.103l.774-1.548a1 1 0 011.06-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"></path></svg>
                     082257473851
                 </a>
                 <a href="mailto:febihandikaputra29@gmail.com" class="flex items-center hover:text-blue-600 transition duration-300">
                     <svg class="w-5 h-5 mr-1" fill="currentColor" viewBox="0 0 20 20"><path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"></path><path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"></path></svg>
                     febihandikaputra29@gmail.com
                 </a>
                 <a href="https://www.linkedin.com/in/febi-handika-putra/" target="_blank" class="flex items-center hover:text-blue-600 transition duration-300">
                     <svg class="w-5 h-5 mr-1" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.3 0H3.7C1.6 0 0 1.6 0 3.7v12.6C0 18.4 1.6 20 3.7 20h12.6c2.1 0 3.7-1.6 3.7-3.7V3.7C20 1.6 18.4 0 16.3 0zM6 17H3V7h3v10zM4.5 5.5a1.5 1.5 0 110-3 1.5 1.5 0 010 3zM17 17h-3v-5.5c0-1.3-.6-2-1.5-2-.8 0-1.3.5-1.5 1.3V17H8V7h3v1.5c.5-.8 1.2-1.3 2.5-1.3 1.8 0 3 1.2 3 3.5V17z" clip-rule="evenodd"></path></svg>
                     LinkedIn
                 </a>
             </div>
         </header>
 
         <section class="mb-8 p-6 card">
             <h2 class="text-2xl font-semibold section-title">1. Perkenalan Diri</h2>
             <p class="mb-4">Lulusan Sarjana Teknik Perminyakan dari Universitas Islam Riau dengan minat yang kuat dalam industri minyak dan gas. Memiliki pemahaman proses industri migas serta pengalaman dalam pengelolaan data produksi dan dokumentasi teknis.</p>
             <p class="mb-4">Terampil dalam administrasi, analisis data, dan koordinasi lintas tim. Seorang profesional dengan etos kerja yang kuat, daya tahan tinggi, jujur, rajin, dan cepat belajar. Mampu bekerja secara mandiri maupun berkelompok, menyukai tantangan, dan dapat bekerja baik di bawah tekanan.</p>
             <p>Dapat diandalkan dalam mengambil keputusan rumit dan kompleks, baik di dalam ruangan maupun di lapangan.</p>
         </section>
 
         <section class="mb-8 p-6 card">
             <h2 class="text-2xl font-semibold section-title">2. Project Penelitian (Tugas Akhir)</h2>
             <h3 class="text-xl font-medium mb-2">"Analisis dan Mitigasi Penyebab Premature Failure Pompa SRP Pasca Cyclic Stimulation di Lapangan Minyak Duri (2021-2022)."</h3>
             <p class="mb-2"><span class="font-semibold">Peran:</span> Petroleum Engineer - Proyek Penelitian Tugas Akhir di PT Pertamina Hulu Rokan, Lapangan Duri, Riau (Juni - November 2023).</p>
             <p class="mb-2"><span class="font-semibold">Ringkasan Proyek:</span> Menganalisis kegagalan prematur pompa Sucker Rod Pump (SRP) setelah cyclic stimulation di lapangan heavy oil Duri. Berhasil mengidentifikasi dan merekomendasikan solusi untuk mengurangi risiko premature failure pompa, seperti penggunaan Secondary Sand Control dan Special Pump. Rekomendasi teknis yang dirancang bertujuan meningkatkan keandalan pompa dan keberlanjutan produksi. Hasil analisis dijadikan acuan oleh engineer lapangan dalam strategi workover dan cyclic stimulation selanjutnya.</p>
             <p class="mb-2"><span class="font-semibold">Dampak Proyek:</span> Meningkatkan efisiensi operasional, menurunkan biaya perawatan, memperpanjang umur pompa, dan mengurangi dampak lingkungan. Memberikan manfaat signifikan bagi Petroleum Engineer dalam menentukan operasi berikutnya atau sebagai referensi workover.</p>
             <p class="mb-2"><span class="font-semibold">Prestasi/Penghargaan:</span> Mendapatkan Sertifikat Penghargaan Kontribusi Proyek Akhir dari PT. Pertamina Hulu Rokan.</p>
             <p class="mb-2"><span class="font-semibold">Keahlian Teknis yang Digunakan:</span> PL/SQL, Data Analysis, Artificial Lift System, Problem Diagnosis, Surface Facilities.</p>
             <p class="mb-4"><span class="font-semibold">Metodologi:</span> Studi field research dengan pengamatan langsung dan pengumpulan data manual menggunakan PL/SQL, diolah dengan Microsoft Excel, dan dianalisis menggunakan metode pengelompokan data Density Based Clustering.</p>
 
             <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mb-4">
                 <div class="image-placeholder h-48">
                     <img src="https://placehold.co/400x200/D1D5DB/6B7280?text=Peta+Lapangan+Duri" alt="Peta Lapangan Duri">
                 </div>
                 <div class="image-placeholder h-48">
                     <img src="https://placehold.co/400x200/D1D5DB/6B7280?text=Dyna+Card/Data+Pompa" alt="Dyna Card atau Data Pompa">
                 </div>
                 <div class="image-placeholder h-48">
                     <img src="https://placehold.co/400x200/D1D5DB/6B7280?text=Grafik+Run+Life" alt="Grafik Perbandingan Run Life">
                 </div>
                 <div class="image-placeholder h-48">
                     <img src="https://placehold.co/400x200/D1D5DB/6B7280?text=Sertifikat+Tugas+Akhir" alt="Sertifikat Tugas Akhir">
                 </div>
             </div>
         </section>
 
         <section class="mb-8 p-6 card">
             <h2 class="text-2xl font-semibold section-title">3. Magang (Internship)</h2>
             <p class="mb-2"><span class="font-semibold">Posisi:</span> Petroleum Engineer - Internship di PT Pertamina Hulu Rokan, Lapangan Duri, Riau (September 2022 - Maret 2023).</p>
             <p class="mb-2"><span class="font-semibold">Program:</span> Program Magang Mahasiswa Bersertifikat (PMMB) – Forum Human Capital Indonesia.</p>
             <p class="mb-4"><span class="font-semibold">Penempatan:</span> Rumbai Main Office, Departemen Asset Optimization Team Heavy Oil Drainage.</p>
             <h3 class="text-xl font-medium mb-2">Tugas & Tanggung Jawab Utama:</h3>
             <ul class="list-disc list-inside mb-4">
                 <li class="list-item">Membuat ringkasan laporan harian rapat pagi mengenai produksi, operasi harian, dan pekerjaan prioritas untuk operasi Minyak Berat Sumatra (Duri).</li>
                 <li class="list-item">Bertanggung jawab atas beberapa area di Duri Steam Flood.</li>
                 <li class="list-item">Memantau dan menganalisis data kinerja produksi serta merekomendasikan kegiatan untuk meningkatkan kinerja sumur.</li>
                 <li class="list-item">Mengembangkan strategi reduksi downtime sumur melalui kerja sama dengan tim workover.</li>
                 <li class="list-item">Menyusun program remedial sumur berbasis data (stimulasi, penyesuaian artificial lift) yang diadopsi dalam operasi lapangan.</li>
                 <li class="list-item">Mendalami sistem fasilitas operasi (separator, pompa, pipa) untuk mendukung kelancaran aliran produksi minyak.</li>
                 <li class="list-item">Berpengalaman solid dalam sistem artificial lift sucker rod pump.</li>
             </ul>
             <p class="mb-2"><span class="font-semibold">Dampak:</span> Meningkatkan efisiensi operasional, mengoptimalkan produksi minyak, dan memastikan keamanan operasional, yang berkontribusi pada peningkatan pendapatan dan maksimalkan potensi lapangan minyak Duri.</p>
             <p class="mb-4"><span class="font-semibold">Prestasi/Pencapaian:</span> Menerima penghargaan dari Kementerian BUMN sebagai peserta terbaik Magang Generasi Bertalenta (MAGENTA-2023). Dianugerahi Sertifikat Apresiasi MAGENTA 2023 oleh Kementerian BUMN atas partisipasi aktif dalam program magang nasional.</p>
             <p><span class="font-semibold">Keahlian yang Ditingkatkan:</span> Well Surveillance & Diagnosis, Well Intervention & Optimization, Cross-functional Coordination & Collaboration.</p>
             <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mt-4">
                 <div class="image-placeholder h-48">
                     <img src="https://placehold.co/400x200/D1D5DB/6B7280?text=Foto+Kegiatan+Magang" alt="Foto Kegiatan Magang">
                 </div>
                 <div class="image-placeholder h-48">
                     <img src="https://placehold.co/400x200/D1D5DB/6B7280?text=Sertifikat+MAGENTA" alt="Sertifikat MAGENTA">
                 </div>
             </div>
         </section>
 
         <section class="mb-8 p-6 card">
             <h2 class="text-2xl font-semibold section-title">4. Kerja Praktek</h2>
             <p class="mb-2"><span class="font-semibold">Posisi:</span> Petroleum Engineer - Kerja Praktek di PT Pertamina Hulu Rokan, Lapangan Duri, Riau (September 2023).</p>
             <p class="mb-4"><span class="font-semibold">Korelasi:</span> Merupakan bagian integral dari program magang mahasiswa bersertifikat (PMMB) yang dikonversi menjadi mata kuliah.</p>
             <h3 class="text-xl font-medium mb-2">Tujuan:</h3>
             <ul class="list-disc list-inside mb-4">
                 <li class="list-item">Mempelajari dan memahami berbagai aspek operasional lapangan minyak Duri, termasuk karakteristik formasi batuan, peta lokasi, ukuran unit pompa, regulasi, dan prosedur analisis sumur.</li>
                 <li class="list-item">Mengikuti rangkaian seminar dan pelatihan untuk meningkatkan pengetahuan dan keterampilan.</li>
                 <li class="list-item">Membuat laporan akhir untuk perusahaan dan universitas.</li>
             </ul>
             <p class="mb-2"><span class="font-semibold">Aktivitas & Pembelajaran:</span> Mempelajari operasional lapangan minyak, karakteristik formasi batuan, dan analisis reservoir. Melakukan pemetaan sumur, tipe completion, dan spesifikasi unit pompa. Mengikuti pelatihan internal terkait optimasi produksi dan HSE. Menyusun laporan akhir kerja praktek sebagai referensi evaluasi produktivitas oleh tim lapangan.</p>
             <p class="mb-2"><span class="font-semibold">Dampak:</span> Meningkatkan pengetahuan dan pemahaman tentang lapangan minyak Duri.</p>
             <p class="mb-4"><span class="font-semibold">Prestasi:</span> Meraih nilai "A" (Sangat Baik) dalam penilaian kinerja.</p>
             <p><span class="font-semibold">Keterampilan:</span> Well & Field Planning, Technical Reporting, Data Analysis & Management, Reservoir Understanding.</p>
             <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mt-4">
                 <div class="image-placeholder h-48">
                     <img src="https://placehold.co/400x200/D1D5DB/6B7280?text=Foto+Kerja+Praktek" alt="Foto Kegiatan Kerja Praktek">
                 </div>
                 <div class="image-placeholder h-48">
                     <img src="https://placehold.co/400x200/D1D5DB/6B7280?text=Laporan+Akhir/Nilai" alt="Dokumen Laporan Akhir atau Nilai">
                 </div>
             </div>
         </section>
 
         <section class="mb-8 p-6 card">
             <h2 class="text-2xl font-semibold section-title">5. Pendidikan & Keterampilan</h2>
             <h3 class="text-xl font-medium mb-2">Pendidikan:</h3>
             <ul class="list-disc list-inside mb-4">
                 <li class="list-item"><span class="font-semibold">Universitas Islam Riau</span> - Sarjana Teknik Perminyakan (Agustus 2018 - November 2023). IPK 3.36/4.00.</li>
                 <li class="list-item"><span class="font-semibold">SMK Negeri 01 Tanjung Baru</span> - Teknik Kendaraan Ringan (Mei 2015 - Mei 2018).</li>
             </ul>
             <h3 class="text-xl font-medium mb-2">Keterampilan Teknis:</h3>
             <ul class="list-disc list-inside mb-4">
                 <li class="list-item"><span class="font-semibold">Software Engineering:</span> PL/SQL (Intermediate), PIPESIM (Basic), OSDU Migas (Beginner).</li>
                 <li class="list-item"><span class="font-semibold">Data Visualization & Reporting:</span> Microsoft Office (Advanced), Power BI (Basic).</li>
             </ul>
             <h3 class="text-xl font-medium mb-2">Soft Skills:</h3>
             <ul class="list-disc list-inside">
                 <li class="list-item">Komunikasi & Kolaborasi: Presentasi teknis dan koordinasi efektif lintas tim.</li>
                 <li class="list-item">Adaptabilitas: Bekerja secara efektif di lingkungan dinamis (lapangan & kantor).</li>
                 <li class="list-item">Problem-Solving: Analisis akar masalah dengan solusi berbasis data.</li>
                 <li class="list-item">Manajemen Proyek: Penjadwalan, alokasi sumber daya, pelaporan progres.</li>
             </ul>
         </section>
 
         <section class="mb-8 p-6 card">
             <h2 class="text-2xl font-semibold section-title">6. Pengalaman Lain (Relevan)</h2>
             <div class="mb-4">
                 <h3 class="text-xl font-medium mb-1">Praktek Kerja Lapangan - Mekanik Otomotif</h3>
                 <p class="text-gray-600 mb-2">PT Astra Daihatsu - Tanjung Alam Service Station (Februari - Mei 2017)</p>
                 <ul class="list-disc list-inside mb-2">
                     <li class="list-item">Mendiagnosis kerusakan kendaraan dan melakukan perbaikan preventif.</li>
                     <li class="list-item">Bekerja sama dengan tim teknis untuk efisiensi waktu dan keselamatan kerja.</li>
                 </ul>
                 <p class="mb-2"><span class="font-semibold">Hasil:</span> Mempercepat waktu perbaikan & menurunkan biaya dengan solusi yang efisien.</p>
                 <p><span class="font-semibold">Keterampilan:</span> Troubleshooting, Preventive Maintenance, Technical Support Interface.</p>
             </div>
             <div>
                 <h3 class="text-xl font-medium mb-1">Kunjungan Lapangan Operasi Migas</h3>
                 <p class="text-gray-600 mb-2">PT SPR Langgak - Riau (Juni 2019)</p>
                 <ul class="list-disc list-inside mb-2">
                     <li class="list-item">Mengobservasi proses produksi migas, sistem artificial lift, jaringan pipa, dan fasilitas gathering station.</li>
                     <li class="list-item">Berinteraksi langsung dengan engineer lapangan dalam mempelajari tren produksi, tantangan operasional, serta praktik keselamatan kerja di lokasi migas.</li>
                 </ul>
                 <p class="mb-2"><span class="font-semibold">Pembelajaran Utama:</span> Integrasi geologi, teknikal, dan keselamatan dalam operasi migas.</p>
                 <p><span class="font-semibold">Keterampilan:</span> Production Insight, Operational & Safety Awareness, Technical Observation.</p>
             </div>
         </section>
 
         <section class="mb-8 p-6 card">
             <h2 class="text-2xl font-semibold section-title">7. Organisasi</h2>
             <ul class="list-disc list-inside">
                 <li class="list-item"><span class="font-semibold">Himpunan Mahasiswa Teknik Perminyakan</span> - Staf (Februari 2020 - Februari 2021).</li>
             </ul>
         </section>
 
         <footer class="text-center p-6 bg-blue-600 text-white rounded-xl">
             <h2 class="text-2xl font-semibold mb-4">Hubungi Saya</h2>
             <p class="mb-4">Silakan hubungi saya untuk kolaborasi atau peluang karir lebih lanjut.</p>
             <div class="flex justify-center space-x-6 text-lg">
                 <a href="mailto:febihandikaputra29@gmail.com" class="flex items-center hover:underline">
                     <svg class="w-6 h-6 mr-2" fill="currentColor" viewBox="0 0 20 20"><path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"></path><path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"></path></svg>
                     Email
                 </a>
                 <a href="https://www.linkedin.com/in/febi-handika-putra/" target="_blank" class="flex items-center hover:underline">
                     <svg class="w-6 h-6 mr-2" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.3 0H3.7C1.6 0 0 1.6 0 3.7v12.6C0 18.4 1.6 20 3.7 20h12.6c2.1 0 3.7-1.6 3.7-3.7V3.7C20 1.6 18.4 0 16.3 0zM6 17H3V7h3v10zM4.5 5.5a1.5 1.5 0 110-3 1.5 1.5 0 010 3zM17 17h-3v-5.5c0-1.3-.6-2-1.5-2-.8 0-1.3.5-1.5 1.3V17H8V7h3v1.5c.5-.8 1.2-1.3 2.5-1.3 1.8 0 3 1.2 3 3.5V17z" clip-rule="evenodd"></path></svg>
                     LinkedIn
                 </a>
             </div>
         </footer>
     </div>
 </body>
 </html>
 
