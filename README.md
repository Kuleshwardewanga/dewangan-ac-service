# dewangan-ac-service
Professional AC, Fridge &amp; Washing Machine Service and Repair Website for Dewangan Refrigeration and Air Conditioning in Durg Bhilai.
export default function BusinessWebsite() { return ( <div className="min-h-screen bg-gray-100 text-gray-800"> {/* Header */} <header className="bg-black text-white shadow-lg"> <div className="max-w-7xl mx-auto px-6 py-5 flex justify-between items-center"> <h1 className="text-3xl font-bold">Dewangan - Refrigeration and Air Conditioning</h1> <nav className="space-x-6 text-lg"> <a href="#home" className="hover:text-yellow-300">Home</a> <a href="#services" className="hover:text-yellow-300">Services</a> <a href="#about" className="hover:text-yellow-300">About</a> <a href="#contact" className="hover:text-yellow-300">Contact</a> </nav> </div> </header>

{/* Hero Section */}
  <section id="home" className="bg-white py-20 px-6 text-center">
    <h2 className="text-5xl font-bold mb-6 text-blue-500">
      All Type AC, Fridge & Washing Machine Service & Repair
    </h2>
    <p className="text-xl max-w-3xl mx-auto mb-8 text-gray-600">
      Fast, Reliable and Affordable AC, Fridge & Washing Machine Repair & Maintenance Service at Your Doorstep.
    </p>
    <button className="bg-black hover:bg-gray-900 text-white px-8 py-4 rounded-2xl text-lg shadow-lg">
      Book Service Now
    </button>
  </section>

  {/* Services */}
  <section id="services" className="py-20 px-6 bg-gray-100">
    <h3 className="text-4xl font-bold text-center mb-14">Our Expert Services</h3>

    <div className="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto">
      <div className="bg-white rounded-3xl shadow-lg p-8 text-center">
        <h4 className="text-2xl font-semibold mb-4 text-blue-500">AC Repair</h4>
        <p className="text-gray-600">
          Split AC, Window AC, Cooling Problem, Gas Leakage, Compressor Repair and all types of AC servicing and repairing.
        </p>
      </div>

      <div className="bg-white rounded-3xl shadow-lg p-8 text-center">
        <h4 className="text-2xl font-semibold mb-4 text-blue-500">AC Installation</h4>
        <p className="text-gray-600">
          Professional AC installation, shifting, fridge setup and washing machine fitting service with complete safety.
        </p>
      </div>

      <div className="bg-white rounded-3xl shadow-lg p-8 text-center">
        <h4 className="text-2xl font-semibold mb-4 text-blue-500">AC Maintenance</h4>
        <p className="text-gray-600">
          Regular cleaning, gas charging, water leakage fixing and complete maintenance for AC, fridge and washing machine.
        </p>
      </div>
    </div>
  </section>

  {/* About */}
  <section id="about" className="bg-white py-20 px-6">
    <div className="max-w-5xl mx-auto text-center">
      <h3 className="text-4xl font-bold mb-8 text-blue-500">About Us</h3>
      <p className="text-lg text-gray-600 leading-8">
        We provide trusted AC, refrigerator and washing machine repair solutions with experienced technicians. Our mission is to deliver quality work, affordable pricing and complete customer satisfaction in Durg Bhilai and nearby areas.
      </p>
    </div>
  </section>

  {/* Contact */}
  <section id="contact" className="py-20 px-6 bg-black text-white text-center">
    <h3 className="text-4xl font-bold mb-8">Contact Us</h3>
    <div className="space-y-4 text-xl">
      <p>📞 Mobile: +91 9285435345</p>
      <p>📍 Address: Durg Bhilai, Chhattisgarh</p>
      <p>✉️ Email: kuleshwardewangan1382@gmail.com</p>
    </div>

    <button className="mt-10 bg-white text-blue-500 px-8 py-4 rounded-2xl text-lg font-semibold shadow-lg hover:bg-gray-100">
      Call Now
    </button>
  </section>

  {/* Customer Reviews */}
  <section className="bg-white py-20 px-6">
    <h3 className="text-4xl font-bold text-center mb-14 text-blue-500">Customer Reviews</h3>

    <div className="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto">
      <div className="bg-gray-100 rounded-3xl shadow-lg p-8">
        <p className="text-gray-600 mb-4">
          “Bahut fast service aur AC cooling problem turant solve kar diya.”
        </p>
        <h4 className="font-bold text-lg">- Ravi Verma</h4>
      </div>

      <div className="bg-gray-100 rounded-3xl shadow-lg p-8">
        <p className="text-gray-600 mb-4">
          “Fridge repair ka kaam professional tarike se kiya aur charge bhi reasonable tha.”
        </p>
        <h4 className="font-bold text-lg">- Neha Sharma</h4>
      </div>

      <div className="bg-gray-100 rounded-3xl shadow-lg p-8">
        <p className="text-gray-600 mb-4">
          “Washing machine service bahut achhi thi. Technician experienced tha.”
        </p>
        <h4 className="font-bold text-lg">- Aman Patel</h4>
      </div>
    </div>
  </section>

  {/* Service Charges */}
  <section className="bg-gray-100 py-20 px-6">
    <h3 className="text-4xl font-bold text-center mb-14 text-blue-500">Service Charges</h3>

    <div className="max-w-4xl mx-auto bg-white rounded-3xl shadow-lg overflow-hidden">
      <table className="w-full text-left">
        <thead className="bg-black text-white">
          <tr>
            <th className="p-5">Service</th>
            <th className="p-5">Starting Price</th>
          </tr>
        </thead>
        <tbody>
          <tr className="border-b">
            <td className="p-5">AC Service</td>
            <td className="p-5">₹499</td>
          </tr>
          <tr className="border-b">
            <td className="p-5">AC Gas Charging</td>
            <td className="p-5">₹1999</td>
          </tr>
          <tr className="border-b">
            <td className="p-5">Fridge Repair</td>
            <td className="p-5">₹399</td>
          </tr>
          <tr>
            <td className="p-5">Washing Machine Repair</td>
            <td className="p-5">₹499</td>
          </tr>
        </tbody>
      </table>
    </div>
  </section>

  {/* Booking Form */}
  <section className="bg-white py-20 px-6">
    <div className="max-w-3xl mx-auto bg-gray-100 rounded-3xl shadow-lg p-10">
      <h3 className="text-4xl font-bold text-center mb-10 text-blue-500">Book a Service</h3>

      <form className="space-y-6">
        <input
          type="text"
          placeholder="Your Name"
          className="w-full p-4 rounded-2xl border"
        />

        <input
          type="tel"
          placeholder="Mobile Number"
          className="w-full p-4 rounded-2xl border"
        />

        <textarea
          placeholder="Describe Your Problem"
          rows="5"
          className="w-full p-4 rounded-2xl border"
        ></textarea>

        <button className="w-full bg-black text-white py-4 rounded-2xl text-lg font-semibold hover:bg-gray-900">
          Submit Booking
        </button>
      </form>
    </div>
  </section>

  {/* WhatsApp Button */}
  <a
    href="https://wa.me/919285435345"
    target="_blank"
    className="fixed bottom-6 right-6 bg-green-500 text-white px-6 py-4 rounded-full shadow-2xl text-lg font-bold hover:bg-green-600"
  >
    WhatsApp Chat
  </a>

  {/* Footer */}
  <footer className="bg-gray-900 text-white text-center py-6">
    <p>© 2026 Dewangan - Refrigeration and Air Conditioning. All Rights Reserved.</p>
  </footer>
</div>

); }
