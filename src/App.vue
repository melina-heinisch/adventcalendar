<template>
  <v-app>
    <div style="display: flex; justify-content: space-between;">
      <Fenster v-for="x in content1" :background-nr="x.backgroundNr" :text="x.text" :number="x.number" :key="x.number"></Fenster>
    </div>
    <div style="display: flex; justify-content: space-between;">
      <Fenster v-for="x in content2" :background-nr="x.backgroundNr" :text="x.text" :number="x.number" :key="x.number"></Fenster>
    </div>
    <div style="display: flex; justify-content: space-between;">
      <Fenster v-for="x in content3" :background-nr="x.backgroundNr" :text="x.text" :number="x.number" :key="x.number"></Fenster>
    </div>
    <div style="display: flex; justify-content: space-between;">
      <Fenster v-for="x in content4" :background-nr="x.backgroundNr" :text="x.text" :number="x.number" :key="x.number"></Fenster>
    </div>
  </v-app>
</template>

<script>
import Fenster from './components/Fenster.vue';

export default {
  name: 'App',

  components: {
    Fenster,
  },

  data: () => ({
    content1:[
      {
        backgroundNr: "one",
        text: "Heute Nacht sollst du davon träumen, mit deinen Kätzchen einen Schneespaziergang zu machen und einen Schneemann zu bauen.",
        number: "1"
      },
      {
        backgroundNr: "two",
        text: "Heute Nacht sollst du träumen, wie du morgen früh dein Geschenk von Nikolaus öffnest und dann Schoki zum Frühstück isst. Die Katzis haben Leckerli in ihrem Schuh.",
        number: "5"
      },
      {
        backgroundNr: "three",
        text: "Heute Nacht sollst du davon träumen, in einem riesigen Haufen Plätzchen zu liegen. Du bist ganz klein und ein Plätzchen ist größer als du. Du kannst so viel essen wie du willst!",
        number: "9"
      },
      {
        backgroundNr: "four",
        text: "Heute Nacht sollst du davon träumen, dass du durch Schnee schwimmen kannst. Es ist so leicht wie in Wasser,aber du entdeckst lauter verstecke und schlafende Welten unter der Schneedecke.",
        number: "13"
      },
      {
        backgroundNr: "one",
        text: "Heute Nacht sollst du davon träumen, dass du auf einem Elch durch den schnee-verschneiten Wald stapfst und auf ein Abenteuer gehst!",
        number: "17"
      },
      {
        backgroundNr: "two",
        text: "Heute Nacht sollst du davon träumen, mit deinen Kätzchen einen Schneespaziergang zu machen und einen Schneemann zu bauen.",
        number: "21"
      }
    ],
    content4: [
      {
        backgroundNr: "three",
        text: "Heute Nacht sollst du davon träumen, durch das Weltall zu fliegen. Du entdeckts neue Planeten und Galaxien und kannst sogar die andere Seite eines schwarzen Lochs bewundern",
        number: "14"
      },
      {
        backgroundNr: "four",
        text: "Heute Nacht sollst du davon träumen, ein Zauberer zu sein. Du kannst jeden erdenklichen Spruch aus Film Fernsehen und Fantasy auf einmal benutzen!",
        number: "18"
      },
      {
        backgroundNr: "one",
        text: "Heute Nacht sollst du davon träumen, dass du nochmal mit Baby Luna und Jojo Zeit verbringen kannst. Sie sind ganz klein und nicht ängstlich, einfach cute kleine Katzenbebis.",
        number: "22"
      },
      {
        backgroundNr: "two",
        text: "Heute Nacht sollst du davon träumen, ein Baum im Wind zu sein. Du spürst, wie der Wind durch deine Blätter und Äste weht und wie du dich leicht im Wind bewegst.",
        number: "2"
      },
      {
        backgroundNr: "three",
        text: "Heute Nacht sollst du davon träumen, nachts in einer Großstadt zu sein, aber alle Straßen sind leer. Du genießt die Ruhe und bestaunst die schöne Weihnachtsbeleuchtung.",
        number: "6"
      },
      {
        backgroundNr: "four",
        text: "Heute Nacht sollst du davon träumen, in einem Labyrinth zu sein. Aber es ist nicht gruselig, sondern du findest an jeder Ecke interessante neue Dinge. Wenn du ras willst, findest du ganz einfach raus. ",
        number: "10"
      }

    ],
    content3: [
      {
        backgroundNr: "one",
        text: "Heute Nacht sollst du davon träumen, dass du eine Schneeflocke bist und auf die Erde schneist. Am Ende wirst du zu einen schönen Schneemann gebaut.",
        number: "11"
      },
      {
        backgroundNr: "two",
        text: "Heute Nacht sollst du davon träumen, dass du eine Christbaumkugel am Tannenbaum bist. Luni schmeißt dich runter und rollt dich unters Bett.  ",
        number: "15"
      },
      {
        backgroundNr: "three",
        text: "Heute Nacht sollst du davon träumen, dass du einem Genie begegnest. Er erfüllt dir drei Wünsche deiner Wahl, wähle weise!",
        number: "19"
      },
      {
        backgroundNr: "four",
        text: "Heute Nacht sollst du davon träumen, dass du Musik bist. Du bist die Soundwelle, du fühlst wie du etwas in einem Menschen auslöst, immer und immer wieder. ",
        number: "3"
      },
      {
        backgroundNr: "one",
        text: "Heute Nacht sollst du davon träumen, dass du ein Grashalm bist, der von einer Schnecke angeknabbert wird. Es tut nicht weh, sondern kitzelt nur ein bisschen und wächst schnell wieder nach.",
        number: "7"
      },
      {
        backgroundNr: "two",
        text: "Heute Nacht sollst du davon träumen, dass du ein Edelstein bist der noch in der Erde liegt. Du wirst ausgegraben und geschliffen. Dann wirst du verschenkt und bekommst einen ehrenplatz im Schrank. ",
        number: "23"
      }
    ],
    content2: [
      {
        backgroundNr: "three",
        text: "Heute Nacht sollst du davon träumen, dass du ein Gestaltenwandler bist. Du kannst alles sein was du willst, also sei kreativ! Willst du ein Drache sein, eine Katze? Endlose Möglichkeiten!",
        number: "4"
      },
      {
        backgroundNr: "four",
        text: "Heute Nacht sollst du davon träumen, dass du eine große Party mit all deine Freunden schmeißt. Alle verstehen sich gut und ihr habt super viel Spaß!",
        number: "16"
      },
      {
        backgroundNr: "one",
        text: "Heute Nacht sollst du davon träumen, dass du ein Qualle bist. Einfach mal kein Gehirn haben ist schon cool oder? Du schwimmst einfach durchs Wasser und lässt dich treiben.",
        number: "20"
      },
      {
        backgroundNr: "two",
        text: "Heute Nacht sollst du davon träumen, dass du einen schönen Abend mit mir verbringst. Es gibt ganz viele cules and kisses and back scratches and head scratches <3",
        number: "24"
      },
      {
        backgroundNr: "three",
        text: "Heute Nacht sollst du davon träumen, dass du au dem Mond bist. Du genießt die wenige Anziehungskraft und hüpfst über die Oberfläche. Du erkundest Krater und nimmst einen Stein für deine Sammlung mit.",
        number: "8"
      },
      {
        backgroundNr: "four",
        text: "Heute Nacht sollst du davon träumen, dass du auch eine kleine Katze bist und zusammen mit Luna und Jojo spielen kannst. Ihr könnt reden und du erfährst, was deine kleinen denken und weißt genau was sie von dir wollen.",
        number: "12"
      },
    ]


  }),
};
</script>
