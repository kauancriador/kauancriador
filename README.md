export default function PortfolioKauan() {
  return (
    <div className="min-h-screen bg-slate-950 text-white p-6 flex items-center justify-center">
      <div className="max-w-4xl w-full bg-slate-900 rounded-3xl shadow-2xl overflow-hidden grid md:grid-cols-3">
        <div className="bg-blue-700 p-8 flex flex-col justify-center">
          <h1 className="text-4xl font-bold">Kauan de Lima</h1>
          <p className="mt-3 text-blue-100">
            Estudante de TI
          </p>

          <div className="mt-8 space-y-3 text-sm">
            <p>📍 Itapevi - SP</p>
            <p>💻 Buscando estágio em TI</p>
            <p>📚 Jovem Aprendiz na Guima</p>
          </div>
        </div>

        <div className="md:col-span-2 p-8 space-y-8">
          <section>
            <h2 className="text-2xl font-bold text-blue-400 mb-3">Sobre mim</h2>
            <p className="text-slate-300 leading-relaxed">
              Tenho 18 anos, sou estudante de TI e jovem aprendiz na Guima.
              Possuo conhecimentos em Front-End, JavaScript, Java Fundamentals,
              UX/UI e Pacote Office. Sou dedicado, organizado e busco uma
              oportunidade de estágio para crescer na área de tecnologia.
            </p>
          </section>

          <section>
            <h2 className="text-2xl font-bold text-blue-400 mb-3">Formação & Cursos</h2>
            <div className="grid sm:grid-cols-2 gap-3 text-slate-300">
              <div className="bg-slate-800 p-3 rounded-xl">Front-End - 2024</div>
              <div className="bg-slate-800 p-3 rounded-xl">JavaScript - 2026</div>
              <div className="bg-slate-800 p-3 rounded-xl">Java Fundamentals - 2024</div>
              <div className="bg-slate-800 p-3 rounded-xl">UX/UI - 2025</div>
              <div className="bg-slate-800 p-3 rounded-xl">Pacote Office - 2023</div>
              <div className="bg-slate-800 p-3 rounded-xl">Blockchain - 2026</div>
            </div>
          </section>

          <section>
            <h2 className="text-2xl font-bold text-blue-400 mb-3">Habilidades</h2>
            <div className="flex flex-wrap gap-3">
              {[
                'HTML',
                'CSS',
                'JavaScript',
                'Front-End',
                'GitHub',
                'Trabalho em equipe'
              ].map((skill) => (
                <span
                  key={skill}
                  className="bg-blue-600 px-4 py-2 rounded-full text-sm"
                >
                  {skill}
                </span>
              ))}
            </div>
          </section>
        </div>
      </div>
    </div>
  )
}
