import React from "react";
import { Mail, Phone, Globe } from "lucide-react";
import { Button } from "@/components/ui/button";
import { Input } from "@/components/ui/input";
import { Textarea } from "@/components/ui/textarea";
import { motion } from "framer-motion";
import { BrowserRouter as Router, Routes, Route, Link } from "react-router-dom";

const allServices = [
  {
    name: "Work Permit",
    description: "Apply to legally work in Canada with employer-specific or open work permits."
  },
  {
    name: "Visitor Visa",
    description: "Explore Canada for tourism or family visits with a Temporary Resident Visa."
  },
  {
    name: "Visitor Record",
    description: "Extend your stay in Canada or modify conditions on your existing visitor status."
  },
  {
    name: "Study Permit Extension",
    description: "Continue your education by extending your current study permit."
  },
  {
    name: "Study Permit from Outside Canada",
    description: "Begin your studies in Canada by applying for a study permit from abroad."
  },
  {
    name: "Post Graduate Work Permit",
    description: "Work in Canada after graduating from a designated learning institution."
  },
  {
    name: "Spousal Open Work Permit",
    description: "Spouses or partners of foreign students/workers can work in Canada."
  },
  {
    name: "Bridging Open Work Permit",
    description: "Continue working in Canada while awaiting a decision on your PR application."
  }
];

function Navbar() {
  return (
    <nav className="bg-[#FEFAF7] text-[#154D57] shadow-md px-6 py-4 sticky top-0 z-50">
      <div className="max-w-7xl mx-auto flex justify-between items-center">
        <span className="font-bold text-xl">Angad Consulting</span>
        <ul className="flex space-x-6 text-sm">
          <li><Link to="/" className="hover:underline">Home</Link></li>
          <li><Link to="/services" className="hover:underline">Services</Link></li>
          <li><Link to="/expect" className="hover:underline">What to Expect</Link></li>
          <li><Link to="/results" className="hover:underline">Proven Results</Link></li>
          <li><Link to="/contact" className="hover:underline">Contact</Link></li>
        </ul>
      </div>
    </nav>
  );
}

function Home() {
  return (
    <section className="relative h-[90vh] bg-cover bg-center flex items-center justify-center" style={{ backgroundImage: "url('/immigration-hero.jpg')" }}>
      <motion.div
        className="bg-[#154D57] bg-opacity-80 p-16 rounded-xl text-center text-white max-w-3xl"
        initial={{ opacity: 0, y: 40 }}
        animate={{ opacity: 1, y: 0 }}
        transition={{ duration: 0.9 }}
      >
        <h1 className="text-5xl font-bold mb-6 tracking-wide">Angad Consulting</h1>
        <p className="text-lg mb-6 leading-relaxed">Canadian Immigration Solutions Tailored to You</p>
        <Button className="bg-white text-[#154D57] font-medium hover:bg-[#FEFAF7] px-8 py-3 rounded-xl">Book a Free Consultation</Button>
      </motion.div>
    </section>
  );
}

function Services() {
  return (
    <section className="px-6 py-24 bg-[#FEFAF7]">
      <div className="text-center mb-16">
        <h2 className="text-4xl font-semibold mb-4">Canada Immigration Services</h2>
        <p className="text-[#154D57] text-lg max-w-2xl mx-auto">From work permits to study extensions, we provide comprehensive support for all your Canadian immigration needs.</p>
      </div>
      <div className="max-w-6xl mx-auto grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-8 text-base">
        {allServices.map(service => (
          <motion.div
            key={service.name}
            className="bg-[#FEFAF7] rounded-xl shadow-md p-6 text-left hover:bg-[#B7A08B] transition"
            whileHover={{ scale: 1.03 }}
          >
            <p className="font-semibold text-[#154D57] mb-2">{service.name}</p>
            <p className="text-sm text-[#000000]">{service.description}</p>
          </motion.div>
        ))}
      </div>
    </section>
  );
}

function WhatToExpect() {
  return (
    <section className="bg-[#FFFFFF] py-24 px-6">
      <div className="max-w-4xl mx-auto text-center">
        <h3 className="text-4xl font-semibold mb-12 text-[#154D57]">What To Expect</h3>
        <div className="grid md:grid-cols-3 gap-8">
          <div className="bg-[#FEFAF7] p-6 rounded-xl shadow">
            <h4 className="font-bold mb-2">01. Consult + Propose</h4>
            <p>Schedule a meeting to discuss your needs and develop a personalized proposal.</p>
          </div>
          <div className="bg-[#FEFAF7] p-6 rounded-xl shadow">
            <h4 className="font-bold mb-2">02. Create + Execute</h4>
            <p>We handle documentation, form completion, and submissions.</p>
          </div>
          <div className="bg-[#FEFAF7] p-6 rounded-xl shadow">
            <h4 className="font-bold mb-2">03. Analyze + Review</h4>
            <p>Detailed updates and outcome evaluation to ensure satisfaction.</p>
          </div>
        </div>
      </div>
    </section>
  );
}

function ProvenResults() {
  return (
    <section className="bg-[#FEFAF7] py-24 px-6">
      <div className="max-w-4xl mx-auto text-center">
        <h3 className="text-4xl font-semibold mb-12 text-[#154D57]">Proven Client Results</h3>
        <div className="grid md:grid-cols-3 gap-8">
          <div className="bg-white p-6 rounded-xl shadow">
            <h4 className="text-xl font-bold mb-2">95%+ Approval Rate</h4>
            <p>Our applications are thoroughly reviewed to maximize success.</p>
          </div>
          <div className="bg-white p-6 rounded-xl shadow">
            <h4 className="text-xl font-bold mb-2">500+ Satisfied Clients</h4>
            <p>We’re proud to have supported hundreds of journeys to Canada.</p>
          </div>
          <div className="bg-white p-6 rounded-xl shadow">
            <h4 className="text-xl font-bold mb-2">24-48 Hr Response Time</h4>
            <p>Get answers quickly from a responsive, dedicated team.</p>
          </div>
        </div>
      </div>
    </section>
  );
}

function Contact() {
  return (
    <section className="bg-[#FFFFFF] py-24 px-6">
      <div className="max-w-xl mx-auto bg-[#FEFAF7] p-12 rounded-3xl shadow-md">
        <h2 className="text-4xl font-semibold text-center mb-4">Get in Touch</h2>
        <p className="text-center text-[#154D57] mb-8">Have questions? We're here to help.</p>
        <form className="space-y-5">
          <Input placeholder="Full Name" required className="rounded-xl" />
          <Input placeholder="Email Address" type="email" required className="rounded-xl" />
          <Input placeholder="Phone Number" type="tel" className="rounded-xl" />
          <Textarea placeholder="Your Message" rows={4} required className="rounded-xl" />
          <Button type="submit" className="w-full bg-[#154D57] hover:bg-[#B7A08B] text-white font-medium rounded-xl">
            Send Message
          </Button>
        </form>
      </div>
    </section>
  );
}

function Footer() {
  return (
    <footer className="bg-[#154D57] text-[#FFFFFF] text-sm py-12 px-6">
      <div className="max-w-6xl mx-auto flex flex-col md:flex-row justify-between gap-6">
        <div>
          <p className="font-semibold text-white text-lg mb-3">Angad Consulting</p>
          <div className="flex items-center gap-2 mb-1"><Mail size={16} /> contact@angadconsulting.com</div>
          <div className="flex items-center gap-2 mb-1"><Phone size={16} /> +1 (437) 855-9664</div>
          <div className="flex items-center gap-2"><Globe size={16} /> www.angadconsulting.com</div>
        </div>
        <div className="flex flex-col md:items-end gap-2">
          <p>Made with ❤️ in Toronto</p>
          <p>&copy; 2025 Angad Consulting. All rights reserved.</p>
        </div>
      </div>
    </footer>
  );
}

export default function App() {
  return (
    <Router>
      <main className="font-light text-[#000000]" style={{ fontFamily: 'Verdana' }}>
        <Navbar />
        <Routes>
          <Route path="/" element={<Home />} />
          <Route path="/services" element={<Services />} />
          <Route path="/expect" element={<WhatToExpect />} />
          <Route path="/results" element={<ProvenResults />} />
          <Route path="/contact" element={<Contact />} />
        </Routes>
        <Footer />
      </main>
    </Router>
  );
}
