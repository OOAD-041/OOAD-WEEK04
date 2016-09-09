# OOAD-WEEK04 การให้นิยามวัตถุ (Abstraction)
Abstraction เป็นการให้นิยามวัตถุในโลกแห่งความเป็นจริงเพื่อจะนำไปสร้างเป็นซอฟต์แวร์ ประกอบด้วยกระบวนการหลักๆ 4 ขั้นตอน ได้แก่

1. Classification
 * เป็นการจำแนกวัตถุออกเป็นพวก จะทำให้ง่ายในการพิจารณาและทำความเข้าใจ 
 * การพิจารณาวัตถุในโดเมนต่างๆ เบื้องต้นไม่ควรที่จะให้มีจำนวนพวกของวัตถุมากเกินไป 
 * แต่ก็ควรที่จะพิจารณาให้ครอบคลุม วัตถุต่างๆทั้งหมด ไม่ตกหล่น
1. Aggregation
 * เป็นการพิจารณาว่า วัตถุหนึ่งๆ เกิดจากการรวมกันของวัตถุอื่นๆ หรือไม่ 
 * การพิจารณาในขั้นตอนนี้ จะทำให้มองเห็นภาพการรวมกันของ class ที่ต้องมีในโปรแกรม 
 * วัตถุย่อยๆ เหล่านั้นที่ประกอบกันเป็นวัตถุใหญ่ จะต้องมีแนวคิดของวัตถุที่ต่างกันโดยสิ้นเชิง
 * วัตถุใดที่สามารถแยกวัตถุย่อยไปใช้งานใหม่ได้ เรียกว่า เป็นการรวมแบบ aggregation
 * วัตถุใดที่ไม่สามารถแยกวัตถุย่อยไปใช้งานใหม่ได้เรียกว่าเป็นการรวมแบบ composition
1. Generalization
 * เป็นการพิจารณาว่าวัตถุในระบบ วัตถุใดบ้างที่มีคุณสมบัติร่วมกัน 
 * จะนำเอาวัตถุทั้งหมด มาหาคุณสมบัติที่มีร่วมกัน เพื่อลดภาระในการเขียนรายละเอียดของ class ต่างๆ 
 * ความสามารถหรือคุณสมบัติใดที่ซ้ำซ้อนกัน จะถูกนำไปไว้ในคลาสระดับบน เรียกว่า Generalization
 * ความสามารถหรือคุณสมบัติที่แตกต่าง จะถูกเก็บไว้ในคลาสระดับล่าง เรียกว่า Specialization
1. Association
 * ในกรณีที่วัตถุต่างๆ ในระบบไม่สามารถพิจารณาได้ตาม ความสัมพันธ์ทั้ง 3 ที่กล่าวมา แต่จำเป็นต้องใช้งานร่วมกันในระบบ ก็จะมีความสัมพันธ์อีกประเภทหนึ่งก็คือ association




