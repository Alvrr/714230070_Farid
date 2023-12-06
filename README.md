<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rental Mobil</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body>
    <header class="header top-0 bg-white shadow-md flex items-center justify-between px-8 py-02">
        <!-- logo -->
        <h1 class="w-3/12">
            <a href=""><b style="color: rgb(19, 165, 165);">FRM</b></a>
        </h1>
        <!-- navbar -->
        <nav class="nav font-semibold text-lg">
            <ul class="flex items-center">
                <li class="p-4 border-b-2 border-green-500 border-opacity-0 hover:border-opacity-100 hover:text-green-500 duration-200 active">
                  <a href="index.html">Home</a>
                </li>
                <li class="p-4 border-b-2 border-green-500 border-opacity-0 hover:border-opacity-100 hover:text-green-500 duration-200">
                  <a href="index.html">Category</a>
                </li>
                <li class="p-4 border-b-2 border-green-500 border-opacity-0 hover:border-opacity-100 hover:text-green-500 duration-200">
                  <a href="index.html">Products</a>
                </li>
                <li class="p-4 border-b-2 border-green-500 border-opacity-0 hover:border-opacity-100 hover:text-green-500 duration-200">
                  <a href="index.html">Contact</a>
                </li>
            </ul>
        </nav>
    </header>
    <div class="flex justify-center imgone">
        <img src="img/car_base.jpeg" class="images"  alt="">
    </div>
    <br><br>
    <div class="container mx-auto ">
        <div class="grid grid-cols-3 grad-4 ">
            <div class="max-w-sm rounded overflow-hidden shadow-lg">
                <img class="w-full" src="img/car_sport_bird.jpg" alt="Sunset in the mountains">
                <div class="px-6 py-4">
                  <div class="font-bold text-xl mb-2">Lambo</div>
                  <p class="text-gray-700 text-base">
                    Mobil terbaik sepanjang masa dengan kecepatan yang maksimal mesin awet mudah untuk di operasikan tahan dalam segala medan dan cuaca 
                  </p>
                </div>
              </div>
              <div class="max-w-sm rounded overflow-hidden shadow-lg">
                <img class="w-full" src="img/car_sport2.jpg" alt="Sunset in the mountains">
                <div class="px-6 py-4">
                  <div class="font-bold text-xl mb-2">Supra</div>
                  <p class="text-gray-700 text-base">
                    Mobil terbaik sepanjang masa dengan kecepatan yang maksimal mesin awet mudah untuk di operasikan tahan dalam segala medan dan cuaca 
                  </p>
                </div>
              </div>
              <div class="max-w-sm rounded overflow-hidden shadow-lg">
                <img class="w-full" src="img/car_sport2.jpg" alt="Sunset in the mountains">
                <div class="px-6 py-4">
                  <div class="font-bold text-xl mb-2">mazda</div>
                  <p class="text-gray-700 text-base">
                    Mobil terbaik sepanjang masa dengan kecepatan yang maksimal mesin awet mudah untuk di operasikan tahan dalam segala medan dan cuaca 
                  </p>
                </div>
              </div> 
        </div>   
        <br><br>
        <div class="flex justify-center">
            <h5><b>Tentang Kami</b></h5>
            <hr>
        </div>
        <br>
        <div class="flex justify-center">
            <a href="#" class="flex flex-col items-center bg-white border border-gray-200 rounded-lg shadow md:flex-row md:max hover:bg-gray-100 dark:border-gray-700 dark:bg-gray-800 dark:hover:bg-gray-700">
                <div class="flex flex-col justify-between p-4 leading-normal">
                    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Rental Mobil Sukses</h5>
                    <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Selamat datang di layanan rental mobil kami, di mana kenyamanan dan mobilitas berkumpul.
                        Kami menyediakan berbagai pilihan mobil berkualitas tinggi untuk memenuhi kebutuhan perjalanan Anda,
                        baik itu untuk liburan, bisnis, atau perjalanan sehari-hari. Dengan armada kami yang terawat dengan baik, Anda dapat mengandalkan kendaraan yang aman dan nyaman untuk membawa Anda ke tempat tujuan dengan gaya.</p>
                </div>
            </a>
        </div>
    </div>
    <div>
        <p id="number"></p>
    </div>
    <footer>
        <p>Test isi footer<br>
    </footer>
</body>
</html>
