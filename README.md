# drift_challenge.py
print("🏁 Welcome to the Drift Quiz Challenge! 🏎️💨")
print("🔥 Асуулт бүр 10 оноо. 3-с дээш бол чи Drift Legend! 👑")

score = 0

# 1-р асуулт
print("\n1️⃣ Drift хийхэд хамгийн чухал зүйл юу вэ?")
print("a) Удирдлага\nb) Хурд\nc) Дугуй")
ans1 = input("👉 Хариулт: ").lower()
if ans1 == "a":
    print("✅ Зөв! Удирдлага drift-д амин чухал.")
    score += 10
else:
    print("❌ Буруу. Удирдлага хамгийн чухал.")

# 2-р асуулт
print("\n2️⃣ 'Tokyo Drift' кино аль франчайзад багтдаг вэ?")
print("a) Fast & Furious\nb) Transformers\nc) Need for Speed")
ans2 = input("👉 Хариулт: ").lower()
if ans2 == "a":
    print("✅ Мундаг!")
    score += 10
else:
    print("❌ Fast & Furious байлаа шүү~")

# 3-р асуулт
print("\n3️⃣ Drift-нд аль араа тохиромжтой вэ?")
print("a) 5-р араа\nb) 2-р араа\nc) Reverse")
ans3 = input("👉 Хариулт: ").lower()
if ans3 == "b":
    print("✅ 2-р араа хамгийн зохимжтой!")
    score += 10
else:
    print("❌ 2-р араа байхгүй бол drift хэцүү дээ!")

# 4-р асуулт
print("\n4️⃣ Drift хийх үед хамгийн түрүүнд юу хийдэг вэ?")
print("a) Тоормос гишгэх\nb) Руль эргүүлэх\nc) Хурд нэмэх")
ans4 = input("👉 Хариулт: ").lower()
if ans4 == "b":
    print("✅ Зөв хариулт!")
    score += 10
else:
    print("❌ Рулийг эргүүлж эхэлдэг шүү дээ!")

# 5-р асуулт
print("\n5️⃣ Drift хийхийг анх аль улсад 'урлаг' гэж нэрлэж эхэлсэн бэ?")
print("a) Япон\nb) Герман\nc) АНУ")
ans5 = input("👉 Хариулт: ").lower()
if ans5 == "a":
    print("✅ Браво! Японд анх drift 'урлаг' болсон.")
    score += 10
else:
    print("❌ Япон бол drift-ийн эх орон шүү~ 🇯🇵")

# 🎉 Дүн:
print("\n🏆 Чиний нийт оноо:", score, "/ 50")

if score >= 30:
    print("🔥 DRIFT LEGEND! 👑 Шинэ үеийн жолооч байна!")
else:
    print("🚗 Хөөрхөн эхлэл! Дахин оролдоорой, rookie racer~")
