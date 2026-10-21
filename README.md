# Student REST API

Node.js болон Express ашиглан хийсэн Оюутны бүртгэлийн REST API (CRUD).

## Төслийг ажиллуулах заавар

1. Сангуудыг суулгах:
   npm install

2. Серверийг хөгжүүлэлтийн горимд ажиллуулах:
   npm run dev

## Endpoints
//commit
- GET /api/v1/students - Бүх оюутны жагсаалт (шүүлт, хуудаслалттай)
- GET /api/v1/students/:id - Нэг оюутны мэдээлэл
- POST /api/v1/students - Шинэ оюутан нэмэх
- PUT /api/v1/students/:id - Оюутны мэдээлэл шинэчлэх
- DELETE /api/v1/students/:id - Оюутан устгах,,,,
//commit