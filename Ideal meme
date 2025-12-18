import { motion } from "framer-motion"; import { Card, CardContent } from "@/components/ui/card"; import { Button } from "@/components/ui/button"; import { Calendar, Scissors, Star, Phone, MapPin, Instagram } from "lucide-react";

export default function BarberPro() { return ( <div className="min-h-screen bg-gradient-to-br from-black via-zinc-900 to-neutral-950 text-white"> {/* HERO */} <section className="relative overflow-hidden"> <motion.div initial={{ opacity: 0, y: 40 }} animate={{ opacity: 1, y: 0 }} transition={{ duration: 0.8 }} className="max-w-7xl mx-auto px-6 py-28 grid md:grid-cols-2 gap-12 items-center" > <div> <h1 className="text-5xl md:text-7xl font-extrabold leading-tight"> Самый <span className="text-amber-500">крутой</span><br /> барбер твоего города </h1> <p className="mt-6 text-lg text-zinc-300"> Стрижки • Бороды • Бритьё • Стиль. Премиум-сервис для тех, кто ценит внешний вид. </p> <div className="mt-8 flex gap-4"> <Button className="bg-amber-500 hover:bg-amber-600 text-black font-bold"> <Calendar className="mr-2" /> Записаться онлайн </Button> <Button variant="outline" className="border-zinc-600"> Наши работы </Button> </div> </div> <motion.div initial={{ scale: 0.9, opacity: 0 }} animate={{ scale: 1, opacity: 1 }} transition={{ delay: 0.3 }} className="rounded-2xl overflow-hidden shadow-2xl" > <img
src="https://images.unsplash.com/photo-1517832606299-7ae9b720a186"
alt="Barber"
className="object-cover w-full h-full"
/> </motion.div> </motion.div> </section>

{/* SERVICES */}
  <section className="py-24 bg-zinc-950">
    <div className="max-w-7xl mx-auto px-6">
      <h2 className="text-4xl font-bold mb-12 text-center">Услуги</h2>
      <div className="grid md:grid-cols-3 gap-8">
        {[
          { title: "Мужская стрижка", price: "1200₽" },
          { title: "Оформление бороды", price: "800₽" },
          { title: "Королевское бритьё", price
