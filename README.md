# Auto Deployment via SSH over ZeroTier menggunakan GitHub Actions

## Approach

Dalam beberapa kasus, dibutuhkan cara untuk mengakses sebuah perangkat dari luar jaringan, contohnya dengan menggunakan IP Publik, namun seringkali sulit untuk mendapatkan IP Publik. Sehingga banyak orang yang menggunakan layanan tunnels seperti Ngrok, Cloudflare Zero Trust dan ZeroTier untuk memudahkan masalah tersebut, sehingga dapat mengakses sebuah localhost dari luar jaringan (Internet).

Kebutuhan tiap-tiap orang juga berbeda, misalnya untuk keperluan monitoring IoT, hosting website sederhana dan lain sebagainya. Karena membeli sebuah VPS untuk beberapa orang tergolong hal yang mahal untuk kasus yang sederhana, sehingga pemanfaatan sebuah perangkat contohnya komputer lawas yang mampu untuk menjalankan sebuah "webserver" ataupun keperluan lainnya sehingga dapat membantu menyelesaikan masalah tersebut, atau hanya sekedar memanfaatkan barang bekas.

## GitHub Actions

Singkatnya, Github Actions merupakan salah satu fitur pada GitHub untuk mengimplementasikan CI/CD dalam sebuah repository, contohnya melakukan testing, build, dan auto-deployment secara otomatis.

Selengkapnya mengenai GitHub Actions dapat dibaca pada dokumentasi berikut :
[https://docs.github.com/en/actions](https://docs.github.com/en/actions)

Hingga pada suatu ketika, penulis mempunyai keinginan untuk melakukan auto deployment sebuah project, namun server letak mendeploy project tersebut bukanlah sebuah VPS, melainkan sebuah mini komputer tanpa IP Publik dan hanya diakses menggunakan Network ZeroTier.

Lalu dibuatlah artikel ini yang isinya akan membahas mengenai Auto Deployment via SSH melalui ZeroTier dengan menggunakan GitHub Actions.

## The Goals

Tujuan dari artikel ini adalah intinya membuat otomasi dimana ketika membuat sebuah perubahan pada branch utama repository (push atau merge dari pull request), deploy ke server dilakukan secara otomatis oleh GitHub Actions, yang mana server tersebut berada dalam Network Zerotier.

## Setup Project
... (will be updated soon)
