<template>
    <div class="info-main">
        <div class="text-block text-title"> О журнале </div>

        <div class="text-block text-highlighted-1">
           Научно-практический журнал «Водное хозяйство России: проблемы, технологии, управление»
        </div>

        <div class="text-block">
           Журнал является периодическим печатным научным рецензируемым журналом. 
           Издается с 1999 г. Периодичность выхода журнала – 6 номеров в год. 
           Издание журнала осуществляется в рамках государственного задания, 
           утвержденного Федеральным агентством водных ресурсов. 
           Учредитель и издатель – 
           ФГБУ «Российский научно-исследовательский институт комплексного использования и охраны водных ресурсов» 
           (Екатеринбург, Россия).
        </div>

        <div class="text-block text-highlighted-2 flex flex-col">
           <a href="https://waterjournal.ru/files/docs/ISSN.jpg"> 
              Международный стандартный серийный номер ISSN 1999-4508. 
           </a>
           <a href="https://waterjournal.ru/files/docs/eISSN.pdf">  
              Электронный международный стандартный серийный номер еISSN 2686-8253 
           </a>
           <a href="https://waterjournal.ru/files/docs/reg_num_040322.pdf">
              Издание зарегистрировано в Федеральной службе по надзору в сфере связи, 
              информационных технологий и массовых коммуникаций 4 марта 2022 г., 
              регистрационный номер: серия ПИ № ФС77-82772
           </a>             
        </div>

        <div class="text-block">
           Журнал распространяется по подписке и адресной рассылке по всей территории Российской Федерации, подписной индекс 39076.
           Подписаться на журнал вы можете: через Объединенный каталог «Пресса России»
           <a class="inline" href="https://www.pressa-rf.ru/cat/1/edition/y_e39076/   "> www.pressa-rf.ru </a>       
        </div>

        <hr>

        <div class="text-block">
           Журнал включен в Перечень ведущих рецензируемых научных журналов и изданий, 
           в которых должны быть опубликованы основные научные результаты диссертаций 
           на соискание ученых степеней доктора и кандидата наук и в Российский индекс 
           научного цитирования (РИНЦ).
        </div>

        <hr>

        <div class="text-block">
           Электронная версия журнала размещается на сайте 
           Научной электронной библиотеки (eLIBRARY.RU).
        </div>

        <hr>

        <div class="text-block">
           <p class="font-semibold inline">Главной целью журнала</p> является научное обеспечение развития водного хозяйства, 
           совершенствование методов управления в области использования, 
           восстановления и охраны водных ресурсов, 
           а также распространение научно-практического 
           опыта и научных разработок, способных повысить 
           эффективность работы водохозяйственной отрасли.
        </div>

        <div class="text-block">
           Журнал «Водное хозяйство России: проблемы, технологии, управление» 
           ставит перед собой следующие <b>задачи</b>:
           <ul class="list-disc">
              <div class="ml-5 my-2">
                 <li>
                    публикация статей, соответствующих международным стандартам использования 
                    концепций, исследовательских техник;
                 </li>
                    
                 <li>
                    расширение географии авторов, активное привлечение зарубежных исследователей;
                 </li>
                    
                 <li>
                    постоянное совершенствование системы научного рецензирования статей с 
                    привлечением широкого круга ученых в соответствии с тематикой публикаций;
                 </li>

                 <li>
                    формирование оптимальных условий для научных дискуссий, взаимодействия и 
                    коммуникации авторов и читателей журнала.
                 </li>  

              </div>                  
           </ul>

           <hr>

           <div class="text-block">
              Публикация статей бесплатная.
           </div>
        </div>

    </div>

</template>

<style scoped>
   
   .info-main {
      @apply
         flex flex-col justify-center
         px-4
         max-w-3xl
   }

   .text-highlighted-1 {
      @apply
         backdrop-brightness-90
   }

   .text-highlighted-2 {
      @apply
         bg-zinc-300
         drop-shadow
   }


   a {
      @apply
         text-blue-500
   }
   
   a:hover {
      @apply underline
   }
   
</style>