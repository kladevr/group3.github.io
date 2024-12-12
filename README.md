@charset "UTF-8";
/*!
Animate.css - http://daneden.me/animate
Licensed under the MIT license - http://opensource.org/licenses/MIT

Copyright (c) 2014 Daniel Eden
*/

.animated {
  -webkit-animation-duration: 1s;
          animation-duration: 1s;
  -webkit-animation-fill-mode: both;
          animation-fill-mode: both;
}

.animated.infinite {
  -webkit-animation-iteration-count: infinite;
          animation-iteration-count: infinite;
}

.animated.hinge {
  -webkit-animation-duration: 2s;
          animation-duration: 2s;
}

@-webkit-keyframes bounce {
  0%, 20%, 53%, 80%, 100% {
    -webkit-transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
            transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
    -webkit-transform: translate3d(0,0,0);
            transform: translate3d(0,0,0);
  }

  40%, 43% {
    -webkit-transition-timing-function: cubic-bezier(0.755, 0.050, 0.855, 0.060);
            transition-timing-function: cubic-bezier(0.755, 0.050, 0.855, 0.060);
    -webkit-transform: translate3d(0, -30px, 0);
            transform: translate3d(0, -30px, 0);
  }

  70% {
    -webkit-transition-timing-function: cubic-bezier(0.755, 0.050, 0.855, 0.060);
            transition-timing-function: cubic-bezier(0.755, 0.050, 0.855, 0.060);
    -webkit-transform: translate3d(0, -15px, 0);
            transform: translate3d(0, -15px, 0);
  }

  90% {
    -webkit-transform: translate3d(0,-4px,0);
            transform: translate3d(0,-4px,0);
  }
}

@keyframes bounce {
  0%, 20%, 53%, 80%, 100% {
    -webkit-transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
            transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
    -webkit-transform: translate3d(0,0,0);
            transform: translate3d(0,0,0);
  }

  40%, 43% {
    -webkit-transition-timing-function: cubic-bezier(0.755, 0.050, 0.855, 0.060);
            transition-timing-function: cubic-bezier(0.755, 0.050, 0.855, 0.060);
    -webkit-transform: translate3d(0, -30px, 0);
            transform: translate3d(0, -30px, 0);
  }

  70% {
    -webkit-transition-timing-function: cubic-bezier(0.755, 0.050, 0.855, 0.060);
            transition-timing-function: cubic-bezier(0.755, 0.050, 0.855, 0.060);
    -webkit-transform: translate3d(0, -15px, 0);
            transform: translate3d(0, -15px, 0);
  }

  90% {
    -webkit-transform: translate3d(0,-4px,0);
            transform: translate3d(0,-4px,0);
  }
}

.bounce {
  -webkit-animation-name: bounce;
          animation-name: bounce;
  -webkit-transform-origin: center bottom;
      -ms-transform-origin: center bottom;
          transform-origin: center bottom;
}

@-webkit-keyframes flash {
  0%, 50%, 100% {
    opacity: 1;
  }

  25%, 75% {
    opacity: 0;
  }
}

@keyframes flash {
  0%, 50%, 100% {
    opacity: 1;
  }

  25%, 75% {
    opacity: 0;
  }
}

.flash {
  -webkit-animation-name: flash;
          animation-name: flash;
}

/* originally authored by Nick Pettit - https://github.com/nickpettit/glide */

@-webkit-keyframes pulse {
  0% {
    -webkit-transform: scale3d(1, 1, 1);
            transform: scale3d(1, 1, 1);
  }

  50% {
    -webkit-transform: scale3d(1.05, 1.05, 1.05);
            transform: scale3d(1.05, 1.05, 1.05);
  }

  100% {
    -webkit-transform: scale3d(1, 1, 1);
            transform: scale3d(1, 1, 1);
  }
}

@keyframes pulse {
  0% {
    -webkit-transform: scale3d(1, 1, 1);
            transform: scale3d(1, 1, 1);
  }

  50% {
    -webkit-transform: scale3d(1.05, 1.05, 1.05);
            transform: scale3d(1.05, 1.05, 1.05);
  }

  100% {
    -webkit-transform: scale3d(1, 1, 1);
            transform: scale3d(1, 1, 1);
  }
}

.pulse {
  -webkit-animation-name: pulse;
          animation-name: pulse;
}

@-webkit-keyframes rubberBand {
  0% {
    -webkit-transform: scale3d(1, 1, 1);
            transform: scale3d(1, 1, 1);
  }

  30% {
    -webkit-transform: scale3d(1.25, 0.75, 1);
            transform: scale3d(1.25, 0.75, 1);
  }

  40% {
    -webkit-transform: scale3d(0.75, 1.25, 1);
            transform: scale3d(0.75, 1.25, 1);
  }

  50% {
    -webkit-transform: scale3d(1.15, 0.85, 1);
            transform: scale3d(1.15, 0.85, 1);
  }

  65% {
    -webkit-transform: scale3d(.95, 1.05, 1);
            transform: scale3d(.95, 1.05, 1);
  }

  75% {
    -webkit-transform: scale3d(1.05, .95, 1);
            transform: scale3d(1.05, .95, 1);
  }

  100% {
    -webkit-transform: scale3d(1, 1, 1);
            transform: scale3d(1, 1, 1);
  }
}

@keyframes rubberBand {
  0% {
    -webkit-transform: scale3d(1, 1, 1);
            transform: scale3d(1, 1, 1);
  }

  30% {
    -webkit-transform: scale3d(1.25, 0.75, 1);
            transform: scale3d(1.25, 0.75, 1);
  }

  40% {
    -webkit-transform: scale3d(0.75, 1.25, 1);
            transform: scale3d(0.75, 1.25, 1);
  }

  50% {
    -webkit-transform: scale3d(1.15, 0.85, 1);
            transform: scale3d(1.15, 0.85, 1);
  }

  65% {
    -webkit-transform: scale3d(.95, 1.05, 1);
            transform: scale3d(.95, 1.05, 1);
  }

  75% {
    -webkit-transform: scale3d(1.05, .95, 1);
            transform: scale3d(1.05, .95, 1);
  }

  100% {
    -webkit-transform: scale3d(1, 1, 1);
            transform: scale3d(1, 1, 1);
  }
}

.rubberBand {
  -webkit-animation-name: rubberBand;
          animation-name: rubberBand;
}

@-webkit-keyframes shake {
  0%, 100% {
    -webkit-transform: translate3d(0, 0, 0);
            transform: translate3d(0, 0, 0);
  }

  10%, 30%, 50%, 70%, 90% {
    -webkit-transform: translate3d(-10px, 0, 0);
            transform: translate3d(-10px, 0, 0);
  }

  20%, 40%, 60%, 80% {
    -webkit-transform: translate3d(10px, 0, 0);
            transform: translate3d(10px, 0, 0);
  }
}

@keyframes shake {
  0%, 100% {
    -webkit-transform: translate3d(0, 0, 0);
            transform: translate3d(0, 0, 0);
  }

  10%, 30%, 50%, 70%, 90% {
    -webkit-transform: translate3d(-10px, 0, 0);
            transform: translate3d(-10px, 0, 0);
  }

  20%, 40%, 60%, 80% {
    -webkit-transform: translate3d(10px, 0, 0);
            transform: translate3d(10px, 0, 0);
  }
}

.shake {
  -webkit-animation-name: shake;
          animation-name: shake;
}

@-webkit-keyframes swing {
  20% {
    -webkit-transform: rotate3d(0, 0, 1, 15deg);
            transform: rotate3d(0, 0, 1, 15deg);
  }

  40% {
    -webkit-transform: rotate3d(0, 0, 1, -10deg);
            transform: rotate3d(0, 0, 1, -10deg);
  }

  60% {
    -webkit-transform: rotate3d(0, 0, 1, 5deg);
            transform: rotate3d(0, 0, 1, 5deg);
  }

  80% {
    -webkit-transform: rotate3d(0, 0, 1, -5deg);
            transform: rotate3d(0, 0, 1, -5deg);
  }

  100% {
    -webkit-transform: rotate3d(0, 0, 1, 0deg);
            transform: rotate3d(0, 0, 1, 0deg);
  }
}

@keyframes swing {
  20% {
    -webkit-transform: rotate3d(0, 0, 1, 15deg);
            transform: rotate3d(0, 0, 1, 15deg);
  }

  40% {
    -webkit-transform: rotate3d(0, 0, 1, -10deg);
            transform: rotate3d(0, 0, 1, -10deg);
  }

  60% {
    -webkit-transform: rotate3d(0, 0, 1, 5deg);
            transform: rotate3d(0, 0, 1, 5deg);
  }

  80% {
    -webkit-transform: rotate3d(0, 0, 1, -5deg);
            transform: rotate3d(0, 0, 1, -5deg);
  }

  100% {
    -webkit-transform: rotate3d(0, 0, 1, 0deg);
            transform: rotate3d(0, 0, 1, 0deg);
  }
}

.swing {
  -webkit-transform-origin: top center;
      -ms-transform-origin: top center;
          transform-origin: top center;
  -webkit-animation-name: swing;
          animation-name: swing;
}

@-webkit-keyframes tada {
  0% {
    -webkit-transform: scale3d(1, 1, 1);
            transform: scale3d(1, 1, 1);
  }

  10%, 20% {
    -webkit-transform: scale3d(.9, .9, .9) rotate3d(0, 0, 1, -3deg);
            transform: scale3d(.9, .9, .9) rotate3d(0, 0, 1, -3deg);
  }

  30%, 50%, 70%, 90% {
    -webkit-transform: scale3d(1.1, 1.1, 1.1) rotate3d(0, 0, 1, 3deg);
            transform: scale3d(1.1, 1.1, 1.1) rotate3d(0, 0, 1, 3deg);
  }

  40%, 60%, 80% {
    -webkit-transform: scale3d(1.1, 1.1, 1.1) rotate3d(0, 0, 1, -3deg);
            transform: scale3d(1.1, 1.1, 1.1) rotate3d(0, 0, 1, -3deg);
  }

  100% {
    -webkit-transform: scale3d(1, 1, 1);
            transform: scale3d(1, 1, 1);
  }
}

@keyframes tada {
  0% {
    -webkit-transform: scale3d(1, 1, 1);
            transform: scale3d(1, 1, 1);
  }

  10%, 20% {
    -webkit-transform: scale3d(.9, .9, .9) rotate3d(0, 0, 1, -3deg);
            transform: scale3d(.9, .9, .9) rotate3d(0, 0, 1, -3deg);
  }

  30%, 50%, 70%, 90% {
    -webkit-transform: scale3d(1.1, 1.1, 1.1) rotate3d(0, 0, 1, 3deg);
            transform: scale3d(1.1, 1.1, 1.1) rotate3d(0, 0, 1, 3deg);
  }

  40%, 60%, 80% {
    -webkit-transform: scale3d(1.1, 1.1, 1.1) rotate3d(0, 0, 1, -3deg);
            transform: scale3d(1.1, 1.1, 1.1) rotate3d(0, 0, 1, -3deg);
  }

  100% {
    -webkit-transform: scale3d(1, 1, 1);
            transform: scale3d(1, 1, 1);
  }
}

.tada {
  -webkit-animation-name: tada;
          animation-name: tada;
}

/* originally authored by Nick Pettit - https://github.com/nickpettit/glide */

@-webkit-keyframes wobble {
  0% {
    -webkit-transform: none;
            transform: none;
  }

  15% {
    -webkit-transform: translate3d(-25%, 0, 0) rotate3d(0, 0, 1, -5deg);
            transform: translate3d(-25%, 0, 0) rotate3d(0, 0, 1, -5deg);
  }

  30% {
    -webkit-transform: translate3d(20%, 0, 0) rotate3d(0, 0, 1, 3deg);
            transform: translate3d(20%, 0, 0) rotate3d(0, 0, 1, 3deg);
  }

  45% {
    -webkit-transform: translate3d(-15%, 0, 0) rotate3d(0, 0, 1, -3deg);
            transform: translate3d(-15%, 0, 0) rotate3d(0, 0, 1, -3deg);
  }

  60% {
    -webkit-transform: translate3d(10%, 0, 0) rotate3d(0, 0, 1, 2deg);
            transform: translate3d(10%, 0, 0) rotate3d(0, 0, 1, 2deg);
  }

  75% {
    -webkit-transform: translate3d(-5%, 0, 0) rotate3d(0, 0, 1, -1deg);
            transform: translate3d(-5%, 0, 0) rotate3d(0, 0, 1, -1deg);
  }

  100% {
    -webkit-transform: none;
            transform: none;
  }
}

@keyframes wobble {
  0% {
    -webkit-transform: none;
            transform: none;
  }

  15% {
    -webkit-transform: translate3d(-25%, 0, 0) rotate3d(0, 0, 1, -5deg);
            transform: translate3d(-25%, 0, 0) rotate3d(0, 0, 1, -5deg);
  }

  30% {
    -webkit-transform: translate3d(20%, 0, 0) rotate3d(0, 0, 1, 3deg);
            transform: translate3d(20%, 0, 0) rotate3d(0, 0, 1, 3deg);
  }

  45% {
    -webkit-transform: translate3d(-15%, 0, 0) rotate3d(0, 0, 1, -3deg);
            transform: translate3d(-15%, 0, 0) rotate3d(0, 0, 1, -3deg);
  }

  60% {
    -webkit-transform: translate3d(10%, 0, 0) rotate3d(0, 0, 1, 2deg);
            transform: translate3d(10%, 0, 0) rotate3d(0, 0, 1, 2deg);
  }

  75% {
    -webkit-transform: translate3d(-5%, 0, 0) rotate3d(0, 0, 1, -1deg);
            transform: translate3d(-5%, 0, 0) rotate3d(0, 0, 1, -1deg);
  }

  100% {
    -webkit-transform: none;
            transform: none;
  }
}

.wobble {
  -webkit-animation-name: wobble;
          animation-name: wobble;
}

@-webkit-keyframes bounceIn {
  0%, 20%, 40%, 60%, 80%, 100% {
    -webkit-transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
            transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
  }

  0% {
    opacity: 0;
    -webkit-transform: scale3d(.3, .3, .3);
            transform: scale3d(.3, .3, .3);
  }

  20% {
    -webkit-transform: scale3d(1.1, 1.1, 1.1);
            transform: scale3d(1.1, 1.1, 1.1);
  }

  40% {
    -webkit-transform: scale3d(.9, .9, .9);
            transform: scale3d(.9, .9, .9);
  }

  60% {
    opacity: 1;
    -webkit-transform: scale3d(1.03, 1.03, 1.03);
            transform: scale3d(1.03, 1.03, 1.03);
  }

  80% {
    -webkit-transform: scale3d(.97, .97, .97);
            transform: scale3d(.97, .97, .97);
  }

  100% {
    opacity: 1;
    -webkit-transform: scale3d(1, 1, 1);
            transform: scale3d(1, 1, 1);
  }
}

@keyframes bounceIn {
  0%, 20%, 40%, 60%, 80%, 100% {
    -webkit-transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
            transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
  }

  0% {
    opacity: 0;
    -webkit-transform: scale3d(.3, .3, .3);
            transform: scale3d(.3, .3, .3);
  }

  20% {
    -webkit-transform: scale3d(1.1, 1.1, 1.1);
            transform: scale3d(1.1, 1.1, 1.1);
  }

  40% {
    -webkit-transform: scale3d(.9, .9, .9);
            transform: scale3d(.9, .9, .9);
  }

  60% {
    opacity: 1;
    -webkit-transform: scale3d(1.03, 1.03, 1.03);
            transform: scale3d(1.03, 1.03, 1.03);
  }

  80% {
    -webkit-transform: scale3d(.97, .97, .97);
            transform: scale3d(.97, .97, .97);
  }

  100% {
    opacity: 1;
    -webkit-transform: scale3d(1, 1, 1);
            transform: scale3d(1, 1, 1);
  }
}

.bounceIn {
  -webkit-animation-name: bounceIn;
          animation-name: bounceIn;
  -webkit-animation-duration: .75s;
          animation-duration: .75s;
}

@-webkit-keyframes bounceInDown {
  0%, 60%, 75%, 90%, 100% {
    -webkit-transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
            transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
  }

  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, -3000px, 0);
            transform: translate3d(0, -3000px, 0);
  }

  60% {
    opacity: 1;
    -webkit-transform: translate3d(0, 25px, 0);
            transform: translate3d(0, 25px, 0);
  }

  75% {
    -webkit-transform: translate3d(0, -10px, 0);
            transform: translate3d(0, -10px, 0);
  }

  90% {
    -webkit-transform: translate3d(0, 5px, 0);
            transform: translate3d(0, 5px, 0);
  }

  100% {
    -webkit-transform: none;
            transform: none;
  }
}

@keyframes bounceInDown {
  0%, 60%, 75%, 90%, 100% {
    -webkit-transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
            transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
  }

  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, -3000px, 0);
            transform: translate3d(0, -3000px, 0);
  }

  60% {
    opacity: 1;
    -webkit-transform: translate3d(0, 25px, 0);
            transform: translate3d(0, 25px, 0);
  }

  75% {
    -webkit-transform: translate3d(0, -10px, 0);
            transform: translate3d(0, -10px, 0);
  }

  90% {
    -webkit-transform: translate3d(0, 5px, 0);
            transform: translate3d(0, 5px, 0);
  }

  100% {
    -webkit-transform: none;
            transform: none;
  }
}

.bounceInDown {
  -webkit-animation-name: bounceInDown;
          animation-name: bounceInDown;
}

@-webkit-keyframes bounceInLeft {
  0%, 60%, 75%, 90%, 100% {
    -webkit-transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
            transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
  }

  0% {
    opacity: 0;
    -webkit-transform: translate3d(-3000px, 0, 0);
            transform: translate3d(-3000px, 0, 0);
  }

  60% {
    opacity: 1;
    -webkit-transform: translate3d(25px, 0, 0);
            transform: translate3d(25px, 0, 0);
  }

  75% {
    -webkit-transform: translate3d(-10px, 0, 0);
            transform: translate3d(-10px, 0, 0);
  }

  90% {
    -webkit-transform: translate3d(5px, 0, 0);
            transform: translate3d(5px, 0, 0);
  }

  100% {
    -webkit-transform: none;
            transform: none;
  }
}

@keyframes bounceInLeft {
  0%, 60%, 75%, 90%, 100% {
    -webkit-transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
            transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
  }

  0% {
    opacity: 0;
    -webkit-transform: translate3d(-3000px, 0, 0);
            transform: translate3d(-3000px, 0, 0);
  }

  60% {
    opacity: 1;
    -webkit-transform: translate3d(25px, 0, 0);
            transform: translate3d(25px, 0, 0);
  }

  75% {
    -webkit-transform: translate3d(-10px, 0, 0);
            transform: translate3d(-10px, 0, 0);
  }

  90% {
    -webkit-transform: translate3d(5px, 0, 0);
            transform: translate3d(5px, 0, 0);
  }

  100% {
    -webkit-transform: none;
            transform: none;
  }
}

.bounceInLeft {
  -webkit-animation-name: bounceInLeft;
          animation-name: bounceInLeft;
}

@-webkit-keyframes bounceInRight {
  0%, 60%, 75%, 90%, 100% {
    -webkit-transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
            transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
  }

  0% {
    opacity: 0;
    -webkit-transform: translate3d(3000px, 0, 0);
            transform: translate3d(3000px, 0, 0);
  }

  60% {
    opacity: 1;
    -webkit-transform: translate3d(-25px, 0, 0);
            transform: translate3d(-25px, 0, 0);
  }

  75% {
    -webkit-transform: translate3d(10px, 0, 0);
            transform: translate3d(10px, 0, 0);
  }

  90% {
    -webkit-transform: translate3d(-5px, 0, 0);
            transform: translate3d(-5px, 0, 0);
  }

  100% {
    -webkit-transform: none;
            transform: none;
  }
}

@keyframes bounceInRight {
  0%, 60%, 75%, 90%, 100% {
    -webkit-transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
            transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
  }

  0% {
    opacity: 0;
    -webkit-transform: translate3d(3000px, 0, 0);
            transform: translate3d(3000px, 0, 0);
  }

  60% {
    opacity: 1;
    -webkit-transform: translate3d(-25px, 0, 0);
            transform: translate3d(-25px, 0, 0);
  }

  75% {
    -webkit-transform: translate3d(10px, 0, 0);
            transform: translate3d(10px, 0, 0);
  }

  90% {
    -webkit-transform: translate3d(-5px, 0, 0);
            transform: translate3d(-5px, 0, 0);
  }

  100% {
    -webkit-transform: none;
            transform: none;
  }
}

.bounceInRight {
  -webkit-animation-name: bounceInRight;
          animation-name: bounceInRight;
}

@-webkit-keyframes bounceInUp {
  0%, 60%, 75%, 90%, 100% {
    -webkit-transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
            transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
  }

  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, 3000px, 0);
            transform: translate3d(0, 3000px, 0);
  }

  60% {
    opacity: 1;
    -webkit-transform: translate3d(0, -20px, 0);
            transform: translate3d(0, -20px, 0);
  }

  75% {
    -webkit-transform: translate3d(0, 10px, 0);
            transform: translate3d(0, 10px, 0);
  }

  90% {
    -webkit-transform: translate3d(0, -5px, 0);
            transform: translate3d(0, -5px, 0);
  }

  100% {
    -webkit-transform: translate3d(0, 0, 0);
            transform: translate3d(0, 0, 0);
  }
}

@keyframes bounceInUp {
  0%, 60%, 75%, 90%, 100% {
    -webkit-transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
            transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
  }

  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, 3000px, 0);
            transform: translate3d(0, 3000px, 0);
  }

  60% {
    opacity: 1;
    -webkit-transform: translate3d(0, -20px, 0);
            transform: translate3d(0, -20px, 0);
  }

  75% {
    -webkit-transform: translate3d(0, 10px, 0);
            transform: translate3d(0, 10px, 0);
  }

  90% {
    -webkit-transform: translate3d(0, -5px, 0);
            transform: translate3d(0, -5px, 0);
  }

  100% {
    -webkit-transform: translate3d(0, 0, 0);
            transform: translate3d(0, 0, 0);
  }
}

.bounceInUp {
  -webkit-animation-name: bounceInUp;
          animation-name: bounceInUp;
}

@-webkit-keyframes bounceOut {
  20% {
    -webkit-transform: scale3d(.9, .9, .9);
            transform: scale3d(.9, .9, .9);
  }

  50%, 55% {
    opacity: 1;
    -webkit-transform: scale3d(1.1, 1.1, 1.1);
            transform: scale3d(1.1, 1.1, 1.1);
  }

  100% {
    opacity: 0;
    -webkit-transform: scale3d(.3, .3, .3);
            transform: scale3d(.3, .3, .3);
  }
}

@keyframes bounceOut {
  20% {
    -webkit-transform: scale3d(.9, .9, .9);
            transform: scale3d(.9, .9, .9);
  }

  50%, 55% {
    opacity: 1;
    -webkit-transform: scale3d(1.1, 1.1, 1.1);
            transform: scale3d(1.1, 1.1, 1.1);
  }

  100% {
    opacity: 0;
    -webkit-transform: scale3d(.3, .3, .3);
            transform: scale3d(.3, .3, .3);
  }
}

.bounceOut {
  -webkit-animation-name: bounceOut;
          animation-name: bounceOut;
  -webkit-animation-duration: .75s;
          animation-duration: .75s;
}

@-webkit-keyframes bounceOutDown {
  20% {
    -webkit-transform: translate3d(0, 10px, 0);
            transform: translate3d(0, 10px, 0);
  }

  40%, 45% {
    opacity: 1;
    -webkit-transform: translate3d(0, -20px, 0);
            transform: translate3d(0, -20px, 0);
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(0, 2000px, 0);
            transform: translate3d(0, 2000px, 0);
  }
}

@keyframes bounceOutDown {
  20% {
    -webkit-transform: translate3d(0, 10px, 0);
            transform: translate3d(0, 10px, 0);
  }

  40%, 45% {
    opacity: 1;
    -webkit-transform: translate3d(0, -20px, 0);
            transform: translate3d(0, -20px, 0);
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(0, 2000px, 0);
            transform: translate3d(0, 2000px, 0);
  }
}

.bounceOutDown {
  -webkit-animation-name: bounceOutDown;
          animation-name: bounceOutDown;
}

@-webkit-keyframes bounceOutLeft {
  20% {
    opacity: 1;
    -webkit-transform: translate3d(20px, 0, 0);
            transform: translate3d(20px, 0, 0);
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(-2000px, 0, 0);
            transform: translate3d(-2000px, 0, 0);
  }
}

@keyframes bounceOutLeft {
  20% {
    opacity: 1;
    -webkit-transform: translate3d(20px, 0, 0);
            transform: translate3d(20px, 0, 0);
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(-2000px, 0, 0);
            transform: translate3d(-2000px, 0, 0);
  }
}

.bounceOutLeft {
  -webkit-animation-name: bounceOutLeft;
          animation-name: bounceOutLeft;
}

@-webkit-keyframes bounceOutRight {
  20% {
    opacity: 1;
    -webkit-transform: translate3d(-20px, 0, 0);
            transform: translate3d(-20px, 0, 0);
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(2000px, 0, 0);
            transform: translate3d(2000px, 0, 0);
  }
}

@keyframes bounceOutRight {
  20% {
    opacity: 1;
    -webkit-transform: translate3d(-20px, 0, 0);
            transform: translate3d(-20px, 0, 0);
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(2000px, 0, 0);
            transform: translate3d(2000px, 0, 0);
  }
}

.bounceOutRight {
  -webkit-animation-name: bounceOutRight;
          animation-name: bounceOutRight;
}

@-webkit-keyframes bounceOutUp {
  20% {
    -webkit-transform: translate3d(0, -10px, 0);
            transform: translate3d(0, -10px, 0);
  }

  40%, 45% {
    opacity: 1;
    -webkit-transform: translate3d(0, 20px, 0);
            transform: translate3d(0, 20px, 0);
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(0, -2000px, 0);
            transform: translate3d(0, -2000px, 0);
  }
}

@keyframes bounceOutUp {
  20% {
    -webkit-transform: translate3d(0, -10px, 0);
            transform: translate3d(0, -10px, 0);
  }

  40%, 45% {
    opacity: 1;
    -webkit-transform: translate3d(0, 20px, 0);
            transform: translate3d(0, 20px, 0);
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(0, -2000px, 0);
            transform: translate3d(0, -2000px, 0);
  }
}

.bounceOutUp {
  -webkit-animation-name: bounceOutUp;
          animation-name: bounceOutUp;
}

@-webkit-keyframes fadeIn {
  0% {opacity: 0;}
  100% {opacity: 1;}
}

@keyframes fadeIn {
  0% {opacity: 0;}
  100% {opacity: 1;}
}

.fadeIn {
  -webkit-animation-name: fadeIn;
          animation-name: fadeIn;
}

@-webkit-keyframes fadeInDown {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, -100%, 0);
            transform: translate3d(0, -100%, 0);
  }

  100% {
    opacity: 1;
    -webkit-transform: none;
            transform: none;
  }
}

@keyframes fadeInDown {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, -100%, 0);
            transform: translate3d(0, -100%, 0);
  }

  100% {
    opacity: 1;
    -webkit-transform: none;
            transform: none;
  }
}

.fadeInDown {
  -webkit-animation-name: fadeInDown;
          animation-name: fadeInDown;
}

@-webkit-keyframes fadeInDownBig {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, -2000px, 0);
            transform: translate3d(0, -2000px, 0);
  }

  100% {
    opacity: 1;
    -webkit-transform: none;
            transform: none;
  }
}

@keyframes fadeInDownBig {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, -2000px, 0);
            transform: translate3d(0, -2000px, 0);
  }

  100% {
    opacity: 1;
    -webkit-transform: none;
            transform: none;
  }
}

.fadeInDownBig {
  -webkit-animation-name: fadeInDownBig;
          animation-name: fadeInDownBig;
}

@-webkit-keyframes fadeInLeft {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(-100%, 0, 0);
            transform: translate3d(-100%, 0, 0);
  }

  100% {
    opacity: 1;
    -webkit-transform: none;
            transform: none;
  }
}

@keyframes fadeInLeft {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(-100%, 0, 0);
            transform: translate3d(-100%, 0, 0);
  }

  100% {
    opacity: 1;
    -webkit-transform: none;
            transform: none;
  }
}

.fadeInLeft {
  -webkit-animation-name: fadeInLeft;
          animation-name: fadeInLeft;
}

@-webkit-keyframes fadeInLeftBig {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(-2000px, 0, 0);
            transform: translate3d(-2000px, 0, 0);
  }

  100% {
    opacity: 1;
    -webkit-transform: none;
            transform: none;
  }
}

@keyframes fadeInLeftBig {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(-2000px, 0, 0);
            transform: translate3d(-2000px, 0, 0);
  }

  100% {
    opacity: 1;
    -webkit-transform: none;
            transform: none;
  }
}

.fadeInLeftBig {
  -webkit-animation-name: fadeInLeftBig;
          animation-name: fadeInLeftBig;
}

@-webkit-keyframes fadeInRight {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(100%, 0, 0);
            transform: translate3d(100%, 0, 0);
  }

  100% {
    opacity: 1;
    -webkit-transform: none;
            transform: none;
  }
}

@keyframes fadeInRight {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(100%, 0, 0);
            transform: translate3d(100%, 0, 0);
  }

  100% {
    opacity: 1;
    -webkit-transform: none;
            transform: none;
  }
}

.fadeInRight {
  -webkit-animation-name: fadeInRight;
          animation-name: fadeInRight;
}

@-webkit-keyframes fadeInRightBig {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(2000px, 0, 0);
            transform: translate3d(2000px, 0, 0);
  }

  100% {
    opacity: 1;
    -webkit-transform: none;
            transform: none;
  }
}

@keyframes fadeInRightBig {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(2000px, 0, 0);
            transform: translate3d(2000px, 0, 0);
  }

  100% {
    opacity: 1;
    -webkit-transform: none;
            transform: none;
  }
}

.fadeInRightBig {
  -webkit-animation-name: fadeInRightBig;
          animation-name: fadeInRightBig;
}

@-webkit-keyframes fadeInUp {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, 100%, 0);
            transform: translate3d(0, 100%, 0);
  }

  100% {
    opacity: 1;
    -webkit-transform: none;
            transform: none;
  }
}

@keyframes fadeInUp {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, 100%, 0);
            transform: translate3d(0, 100%, 0);
  }

  100% {
    opacity: 1;
    -webkit-transform: none;
            transform: none;
  }
}

.fadeInUp {
  -webkit-animation-name: fadeInUp;
          animation-name: fadeInUp;
}

@-webkit-keyframes fadeInUpBig {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, 2000px, 0);
            transform: translate3d(0, 2000px, 0);
  }

  100% {
    opacity: 1;
    -webkit-transform: none;
            transform: none;
  }
}

@keyframes fadeInUpBig {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(0, 2000px, 0);
            transform: translate3d(0, 2000px, 0);
  }

  100% {
    opacity: 1;
    -webkit-transform: none;
            transform: none;
  }
}

.fadeInUpBig {
  -webkit-animation-name: fadeInUpBig;
          animation-name: fadeInUpBig;
}

@-webkit-keyframes fadeOut {
  0% {opacity: 1;}
  100% {opacity: 0;}
}

@keyframes fadeOut {
  0% {opacity: 1;}
  100% {opacity: 0;}
}

.fadeOut {
  -webkit-animation-name: fadeOut;
          animation-name: fadeOut;
}

@-webkit-keyframes fadeOutDown {
  0% {
    opacity: 1;
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(0, 100%, 0);
            transform: translate3d(0, 100%, 0);
  }
}

@keyframes fadeOutDown {
  0% {
    opacity: 1;
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(0, 100%, 0);
            transform: translate3d(0, 100%, 0);
  }
}

.fadeOutDown {
  -webkit-animation-name: fadeOutDown;
          animation-name: fadeOutDown;
}

@-webkit-keyframes fadeOutDownBig {
  0% {
    opacity: 1;
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(0, 2000px, 0);
            transform: translate3d(0, 2000px, 0);
  }
}

@keyframes fadeOutDownBig {
  0% {
    opacity: 1;
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(0, 2000px, 0);
            transform: translate3d(0, 2000px, 0);
  }
}

.fadeOutDownBig {
  -webkit-animation-name: fadeOutDownBig;
          animation-name: fadeOutDownBig;
}

@-webkit-keyframes fadeOutLeft {
  0% {
    opacity: 1;
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(-100%, 0, 0);
            transform: translate3d(-100%, 0, 0);
  }
}

@keyframes fadeOutLeft {
  0% {
    opacity: 1;
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(-100%, 0, 0);
            transform: translate3d(-100%, 0, 0);
  }
}

.fadeOutLeft {
  -webkit-animation-name: fadeOutLeft;
          animation-name: fadeOutLeft;
}

@-webkit-keyframes fadeOutLeftBig {
  0% {
    opacity: 1;
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(-2000px, 0, 0);
            transform: translate3d(-2000px, 0, 0);
  }
}

@keyframes fadeOutLeftBig {
  0% {
    opacity: 1;
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(-2000px, 0, 0);
            transform: translate3d(-2000px, 0, 0);
  }
}

.fadeOutLeftBig {
  -webkit-animation-name: fadeOutLeftBig;
          animation-name: fadeOutLeftBig;
}

@-webkit-keyframes fadeOutRight {
  0% {
    opacity: 1;
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(100%, 0, 0);
            transform: translate3d(100%, 0, 0);
  }
}

@keyframes fadeOutRight {
  0% {
    opacity: 1;
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(100%, 0, 0);
            transform: translate3d(100%, 0, 0);
  }
}

.fadeOutRight {
  -webkit-animation-name: fadeOutRight;
          animation-name: fadeOutRight;
}

@-webkit-keyframes fadeOutRightBig {
  0% {
    opacity: 1;
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(2000px, 0, 0);
            transform: translate3d(2000px, 0, 0);
  }
}

@keyframes fadeOutRightBig {
  0% {
    opacity: 1;
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(2000px, 0, 0);
            transform: translate3d(2000px, 0, 0);
  }
}

.fadeOutRightBig {
  -webkit-animation-name: fadeOutRightBig;
          animation-name: fadeOutRightBig;
}

@-webkit-keyframes fadeOutUp {
  0% {
    opacity: 1;
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(0, -100%, 0);
            transform: translate3d(0, -100%, 0);
  }
}

@keyframes fadeOutUp {
  0% {
    opacity: 1;
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(0, -100%, 0);
            transform: translate3d(0, -100%, 0);
  }
}

.fadeOutUp {
  -webkit-animation-name: fadeOutUp;
          animation-name: fadeOutUp;
}

@-webkit-keyframes fadeOutUpBig {
  0% {
    opacity: 1;
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(0, -2000px, 0);
            transform: translate3d(0, -2000px, 0);
  }
}

@keyframes fadeOutUpBig {
  0% {
    opacity: 1;
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(0, -2000px, 0);
            transform: translate3d(0, -2000px, 0);
  }
}

.fadeOutUpBig {
  -webkit-animation-name: fadeOutUpBig;
          animation-name: fadeOutUpBig;
}

@-webkit-keyframes flip {
  0% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, -360deg);
            transform: perspective(400px) rotate3d(0, 1, 0, -360deg);
    -webkit-animation-timing-function: ease-out;
            animation-timing-function: ease-out;
  }

  40% {
    -webkit-transform: perspective(400px) translate3d(0, 0, 150px) rotate3d(0, 1, 0, -190deg);
            transform: perspective(400px) translate3d(0, 0, 150px) rotate3d(0, 1, 0, -190deg);
    -webkit-animation-timing-function: ease-out;
            animation-timing-function: ease-out;
  }

  50% {
    -webkit-transform: perspective(400px) translate3d(0, 0, 150px) rotate3d(0, 1, 0, -170deg);
            transform: perspective(400px) translate3d(0, 0, 150px) rotate3d(0, 1, 0, -170deg);
    -webkit-animation-timing-function: ease-in;
            animation-timing-function: ease-in;
  }

  80% {
    -webkit-transform: perspective(400px) scale3d(.95, .95, .95);
            transform: perspective(400px) scale3d(.95, .95, .95);
    -webkit-animation-timing-function: ease-in;
            animation-timing-function: ease-in;
  }

  100% {
    -webkit-transform: perspective(400px);
            transform: perspective(400px);
    -webkit-animation-timing-function: ease-in;
            animation-timing-function: ease-in;
  }
}

@keyframes flip {
  0% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, -360deg);
            transform: perspective(400px) rotate3d(0, 1, 0, -360deg);
    -webkit-animation-timing-function: ease-out;
            animation-timing-function: ease-out;
  }

  40% {
    -webkit-transform: perspective(400px) translate3d(0, 0, 150px) rotate3d(0, 1, 0, -190deg);
            transform: perspective(400px) translate3d(0, 0, 150px) rotate3d(0, 1, 0, -190deg);
    -webkit-animation-timing-function: ease-out;
            animation-timing-function: ease-out;
  }

  50% {
    -webkit-transform: perspective(400px) translate3d(0, 0, 150px) rotate3d(0, 1, 0, -170deg);
            transform: perspective(400px) translate3d(0, 0, 150px) rotate3d(0, 1, 0, -170deg);
    -webkit-animation-timing-function: ease-in;
            animation-timing-function: ease-in;
  }

  80% {
    -webkit-transform: perspective(400px) scale3d(.95, .95, .95);
            transform: perspective(400px) scale3d(.95, .95, .95);
    -webkit-animation-timing-function: ease-in;
            animation-timing-function: ease-in;
  }

  100% {
    -webkit-transform: perspective(400px);
            transform: perspective(400px);
    -webkit-animation-timing-function: ease-in;
            animation-timing-function: ease-in;
  }
}

.animated.flip {
  -webkit-backface-visibility: visible;
          backface-visibility: visible;
  -webkit-animation-name: flip;
          animation-name: flip;
}

@-webkit-keyframes flipInX {
  0% {
    -webkit-transform: perspective(400px) rotate3d(1, 0, 0, 90deg);
            transform: perspective(400px) rotate3d(1, 0, 0, 90deg);
    -webkit-transition-timing-function: ease-in;
            transition-timing-function: ease-in;
    opacity: 0;
  }

  40% {
    -webkit-transform: perspective(400px) rotate3d(1, 0, 0, -20deg);
            transform: perspective(400px) rotate3d(1, 0, 0, -20deg);
    -webkit-transition-timing-function: ease-in;
            transition-timing-function: ease-in;
  }

  60% {
    -webkit-transform: perspective(400px) rotate3d(1, 0, 0, 10deg);
            transform: perspective(400px) rotate3d(1, 0, 0, 10deg);
    opacity: 1;
  }

  80% {
    -webkit-transform: perspective(400px) rotate3d(1, 0, 0, -5deg);
            transform: perspective(400px) rotate3d(1, 0, 0, -5deg);
  }

  100% {
    -webkit-transform: perspective(400px);
            transform: perspective(400px);
  }
}

@keyframes flipInX {
  0% {
    -webkit-transform: perspective(400px) rotate3d(1, 0, 0, 90deg);
            transform: perspective(400px) rotate3d(1, 0, 0, 90deg);
    -webkit-transition-timing-function: ease-in;
            transition-timing-function: ease-in;
    opacity: 0;
  }

  40% {
    -webkit-transform: perspective(400px) rotate3d(1, 0, 0, -20deg);
            transform: perspective(400px) rotate3d(1, 0, 0, -20deg);
    -webkit-transition-timing-function: ease-in;
            transition-timing-function: ease-in;
  }

  60% {
    -webkit-transform: perspective(400px) rotate3d(1, 0, 0, 10deg);
            transform: perspective(400px) rotate3d(1, 0, 0, 10deg);
    opacity: 1;
  }

  80% {
    -webkit-transform: perspective(400px) rotate3d(1, 0, 0, -5deg);
            transform: perspective(400px) rotate3d(1, 0, 0, -5deg);
  }

  100% {
    -webkit-transform: perspective(400px);
            transform: perspective(400px);
  }
}

.flipInX {
  -webkit-backface-visibility: visible !important;
          backface-visibility: visible !important;
  -webkit-animation-name: flipInX;
          animation-name: flipInX;
}

@-webkit-keyframes flipInY {
  0% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, 90deg);
            transform: perspective(400px) rotate3d(0, 1, 0, 90deg);
    -webkit-transition-timing-function: ease-in;
            transition-timing-function: ease-in;
    opacity: 0;
  }

  40% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, -20deg);
            transform: perspective(400px) rotate3d(0, 1, 0, -20deg);
    -webkit-transition-timing-function: ease-in;
            transition-timing-function: ease-in;
  }

  60% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, 10deg);
            transform: perspective(400px) rotate3d(0, 1, 0, 10deg);
    opacity: 1;
  }

  80% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, -5deg);
            transform: perspective(400px) rotate3d(0, 1, 0, -5deg);
  }

  100% {
    -webkit-transform: perspective(400px);
            transform: perspective(400px);
  }
}

@keyframes flipInY {
  0% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, 90deg);
            transform: perspective(400px) rotate3d(0, 1, 0, 90deg);
    -webkit-transition-timing-function: ease-in;
            transition-timing-function: ease-in;
    opacity: 0;
  }

  40% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, -20deg);
            transform: perspective(400px) rotate3d(0, 1, 0, -20deg);
    -webkit-transition-timing-function: ease-in;
            transition-timing-function: ease-in;
  }

  60% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, 10deg);
            transform: perspective(400px) rotate3d(0, 1, 0, 10deg);
    opacity: 1;
  }

  80% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, -5deg);
            transform: perspective(400px) rotate3d(0, 1, 0, -5deg);
  }

  100% {
    -webkit-transform: perspective(400px);
            transform: perspective(400px);
  }
}

.flipInY {
  -webkit-backface-visibility: visible !important;
          backface-visibility: visible !important;
  -webkit-animation-name: flipInY;
          animation-name: flipInY;
}

@-webkit-keyframes flipOutX {
  0% {
    -webkit-transform: perspective(400px);
            transform: perspective(400px);
  }

  30% {
    -webkit-transform: perspective(400px) rotate3d(1, 0, 0, -20deg);
            transform: perspective(400px) rotate3d(1, 0, 0, -20deg);
    opacity: 1;
  }

  100% {
    -webkit-transform: perspective(400px) rotate3d(1, 0, 0, 90deg);
            transform: perspective(400px) rotate3d(1, 0, 0, 90deg);
    opacity: 0;
  }
}

@keyframes flipOutX {
  0% {
    -webkit-transform: perspective(400px);
            transform: perspective(400px);
  }

  30% {
    -webkit-transform: perspective(400px) rotate3d(1, 0, 0, -20deg);
            transform: perspective(400px) rotate3d(1, 0, 0, -20deg);
    opacity: 1;
  }

  100% {
    -webkit-transform: perspective(400px) rotate3d(1, 0, 0, 90deg);
            transform: perspective(400px) rotate3d(1, 0, 0, 90deg);
    opacity: 0;
  }
}

.flipOutX {
  -webkit-animation-name: flipOutX;
          animation-name: flipOutX;
  -webkit-animation-duration: .75s;
          animation-duration: .75s;
  -webkit-backface-visibility: visible !important;
          backface-visibility: visible !important;
}

@-webkit-keyframes flipOutY {
  0% {
    -webkit-transform: perspective(400px);
            transform: perspective(400px);
  }

  30% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, -15deg);
            transform: perspective(400px) rotate3d(0, 1, 0, -15deg);
    opacity: 1;
  }

  100% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, 90deg);
            transform: perspective(400px) rotate3d(0, 1, 0, 90deg);
    opacity: 0;
  }
}

@keyframes flipOutY {
  0% {
    -webkit-transform: perspective(400px);
            transform: perspective(400px);
  }

  30% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, -15deg);
            transform: perspective(400px) rotate3d(0, 1, 0, -15deg);
    opacity: 1;
  }

  100% {
    -webkit-transform: perspective(400px) rotate3d(0, 1, 0, 90deg);
            transform: perspective(400px) rotate3d(0, 1, 0, 90deg);
    opacity: 0;
  }
}

.flipOutY {
  -webkit-backface-visibility: visible !important;
          backface-visibility: visible !important;
  -webkit-animation-name: flipOutY;
          animation-name: flipOutY;
  -webkit-animation-duration: .75s;
          animation-duration: .75s;
}

@-webkit-keyframes lightSpeedIn {
  0% {
    -webkit-transform: translate3d(100%, 0, 0) skewX(-30deg);
            transform: translate3d(100%, 0, 0) skewX(-30deg);
    opacity: 0;
  }

  60% {
    -webkit-transform: skewX(20deg);
            transform: skewX(20deg);
    opacity: 1;
  }

  80% {
    -webkit-transform: skewX(-5deg);
            transform: skewX(-5deg);
    opacity: 1;
  }

  100% {
    -webkit-transform: none;
            transform: none;
    opacity: 1;
  }
}

@keyframes lightSpeedIn {
  0% {
    -webkit-transform: translate3d(100%, 0, 0) skewX(-30deg);
            transform: translate3d(100%, 0, 0) skewX(-30deg);
    opacity: 0;
  }

  60% {
    -webkit-transform: skewX(20deg);
            transform: skewX(20deg);
    opacity: 1;
  }

  80% {
    -webkit-transform: skewX(-5deg);
            transform: skewX(-5deg);
    opacity: 1;
  }

  100% {
    -webkit-transform: none;
            transform: none;
    opacity: 1;
  }
}

.lightSpeedIn {
  -webkit-animation-name: lightSpeedIn;
          animation-name: lightSpeedIn;
  -webkit-animation-timing-function: ease-out;
          animation-timing-function: ease-out;
}

@-webkit-keyframes lightSpeedOut {
  0% {
    opacity: 1;
  }

  100% {
    -webkit-transform: translate3d(100%, 0, 0) skewX(30deg);
            transform: translate3d(100%, 0, 0) skewX(30deg);
    opacity: 0;
  }
}

@keyframes lightSpeedOut {
  0% {
    opacity: 1;
  }

  100% {
    -webkit-transform: translate3d(100%, 0, 0) skewX(30deg);
            transform: translate3d(100%, 0, 0) skewX(30deg);
    opacity: 0;
  }
}

.lightSpeedOut {
  -webkit-animation-name: lightSpeedOut;
          animation-name: lightSpeedOut;
  -webkit-animation-timing-function: ease-in;
          animation-timing-function: ease-in;
}

@-webkit-keyframes rotateIn {
  0% {
    -webkit-transform-origin: center;
            transform-origin: center;
    -webkit-transform: rotate3d(0, 0, 1, -200deg);
            transform: rotate3d(0, 0, 1, -200deg);
    opacity: 0;
  }

  100% {
    -webkit-transform-origin: center;
            transform-origin: center;
    -webkit-transform: none;
            transform: none;
    opacity: 1;
  }
}

@keyframes rotateIn {
  0% {
    -webkit-transform-origin: center;
            transform-origin: center;
    -webkit-transform: rotate3d(0, 0, 1, -200deg);
            transform: rotate3d(0, 0, 1, -200deg);
    opacity: 0;
  }

  100% {
    -webkit-transform-origin: center;
            transform-origin: center;
    -webkit-transform: none;
            transform: none;
    opacity: 1;
  }
}

.rotateIn {
  -webkit-animation-name: rotateIn;
          animation-name: rotateIn;
}

@-webkit-keyframes rotateInDownLeft {
  0% {
    -webkit-transform-origin: left bottom;
            transform-origin: left bottom;
    -webkit-transform: rotate3d(0, 0, 1, -45deg);
            transform: rotate3d(0, 0, 1, -45deg);
    opacity: 0;
  }

  100% {
    -webkit-transform-origin: left bottom;
            transform-origin: left bottom;
    -webkit-transform: none;
            transform: none;
    opacity: 1;
  }
}

@keyframes rotateInDownLeft {
  0% {
    -webkit-transform-origin: left bottom;
            transform-origin: left bottom;
    -webkit-transform: rotate3d(0, 0, 1, -45deg);
            transform: rotate3d(0, 0, 1, -45deg);
    opacity: 0;
  }

  100% {
    -webkit-transform-origin: left bottom;
            transform-origin: left bottom;
    -webkit-transform: none;
            transform: none;
    opacity: 1;
  }
}

.rotateInDownLeft {
  -webkit-animation-name: rotateInDownLeft;
          animation-name: rotateInDownLeft;
}

@-webkit-keyframes rotateInDownRight {
  0% {
    -webkit-transform-origin: right bottom;
            transform-origin: right bottom;
    -webkit-transform: rotate3d(0, 0, 1, 45deg);
            transform: rotate3d(0, 0, 1, 45deg);
    opacity: 0;
  }

  100% {
    -webkit-transform-origin: right bottom;
            transform-origin: right bottom;
    -webkit-transform: none;
            transform: none;
    opacity: 1;
  }
}

@keyframes rotateInDownRight {
  0% {
    -webkit-transform-origin: right bottom;
            transform-origin: right bottom;
    -webkit-transform: rotate3d(0, 0, 1, 45deg);
            transform: rotate3d(0, 0, 1, 45deg);
    opacity: 0;
  }

  100% {
    -webkit-transform-origin: right bottom;
            transform-origin: right bottom;
    -webkit-transform: none;
            transform: none;
    opacity: 1;
  }
}

.rotateInDownRight {
  -webkit-animation-name: rotateInDownRight;
          animation-name: rotateInDownRight;
}

@-webkit-keyframes rotateInUpLeft {
  0% {
    -webkit-transform-origin: left bottom;
            transform-origin: left bottom;
    -webkit-transform: rotate3d(0, 0, 1, 45deg);
            transform: rotate3d(0, 0, 1, 45deg);
    opacity: 0;
  }

  100% {
    -webkit-transform-origin: left bottom;
            transform-origin: left bottom;
    -webkit-transform: none;
            transform: none;
    opacity: 1;
  }
}

@keyframes rotateInUpLeft {
  0% {
    -webkit-transform-origin: left bottom;
            transform-origin: left bottom;
    -webkit-transform: rotate3d(0, 0, 1, 45deg);
            transform: rotate3d(0, 0, 1, 45deg);
    opacity: 0;
  }

  100% {
    -webkit-transform-origin: left bottom;
            transform-origin: left bottom;
    -webkit-transform: none;
            transform: none;
    opacity: 1;
  }
}

.rotateInUpLeft {
  -webkit-animation-name: rotateInUpLeft;
          animation-name: rotateInUpLeft;
}

@-webkit-keyframes rotateInUpRight {
  0% {
    -webkit-transform-origin: right bottom;
            transform-origin: right bottom;
    -webkit-transform: rotate3d(0, 0, 1, -90deg);
            transform: rotate3d(0, 0, 1, -90deg);
    opacity: 0;
  }

  100% {
    -webkit-transform-origin: right bottom;
            transform-origin: right bottom;
    -webkit-transform: none;
            transform: none;
    opacity: 1;
  }
}

@keyframes rotateInUpRight {
  0% {
    -webkit-transform-origin: right bottom;
            transform-origin: right bottom;
    -webkit-transform: rotate3d(0, 0, 1, -90deg);
            transform: rotate3d(0, 0, 1, -90deg);
    opacity: 0;
  }

  100% {
    -webkit-transform-origin: right bottom;
            transform-origin: right bottom;
    -webkit-transform: none;
            transform: none;
    opacity: 1;
  }
}

.rotateInUpRight {
  -webkit-animation-name: rotateInUpRight;
          animation-name: rotateInUpRight;
}

@-webkit-keyframes rotateOut {
  0% {
    -webkit-transform-origin: center;
            transform-origin: center;
    opacity: 1;
  }

  100% {
    -webkit-transform-origin: center;
            transform-origin: center;
    -webkit-transform: rotate3d(0, 0, 1, 200deg);
            transform: rotate3d(0, 0, 1, 200deg);
    opacity: 0;
  }
}

@keyframes rotateOut {
  0% {
    -webkit-transform-origin: center;
            transform-origin: center;
    opacity: 1;
  }

  100% {
    -webkit-transform-origin: center;
            transform-origin: center;
    -webkit-transform: rotate3d(0, 0, 1, 200deg);
            transform: rotate3d(0, 0, 1, 200deg);
    opacity: 0;
  }
}

.rotateOut {
  -webkit-animation-name: rotateOut;
          animation-name: rotateOut;
}

@-webkit-keyframes rotateOutDownLeft {
  0% {
    -webkit-transform-origin: left bottom;
            transform-origin: left bottom;
    opacity: 1;
  }

  100% {
    -webkit-transform-origin: left bottom;
            transform-origin: left bottom;
    -webkit-transform: rotate3d(0, 0, 1, 45deg);
            transform: rotate3d(0, 0, 1, 45deg);
    opacity: 0;
  }
}

@keyframes rotateOutDownLeft {
  0% {
    -webkit-transform-origin: left bottom;
            transform-origin: left bottom;
    opacity: 1;
  }

  100% {
    -webkit-transform-origin: left bottom;
            transform-origin: left bottom;
    -webkit-transform: rotate3d(0, 0, 1, 45deg);
            transform: rotate3d(0, 0, 1, 45deg);
    opacity: 0;
  }
}

.rotateOutDownLeft {
  -webkit-animation-name: rotateOutDownLeft;
          animation-name: rotateOutDownLeft;
}

@-webkit-keyframes rotateOutDownRight {
  0% {
    -webkit-transform-origin: right bottom;
            transform-origin: right bottom;
    opacity: 1;
  }

  100% {
    -webkit-transform-origin: right bottom;
            transform-origin: right bottom;
    -webkit-transform: rotate3d(0, 0, 1, -45deg);
            transform: rotate3d(0, 0, 1, -45deg);
    opacity: 0;
  }
}

@keyframes rotateOutDownRight {
  0% {
    -webkit-transform-origin: right bottom;
            transform-origin: right bottom;
    opacity: 1;
  }

  100% {
    -webkit-transform-origin: right bottom;
            transform-origin: right bottom;
    -webkit-transform: rotate3d(0, 0, 1, -45deg);
            transform: rotate3d(0, 0, 1, -45deg);
    opacity: 0;
  }
}

.rotateOutDownRight {
  -webkit-animation-name: rotateOutDownRight;
          animation-name: rotateOutDownRight;
}

@-webkit-keyframes rotateOutUpLeft {
  0% {
    -webkit-transform-origin: left bottom;
            transform-origin: left bottom;
    opacity: 1;
  }

  100% {
    -webkit-transform-origin: left bottom;
            transform-origin: left bottom;
    -webkit-transform: rotate3d(0, 0, 1, -45deg);
            transform: rotate3d(0, 0, 1, -45deg);
    opacity: 0;
  }
}

@keyframes rotateOutUpLeft {
  0% {
    -webkit-transform-origin: left bottom;
            transform-origin: left bottom;
    opacity: 1;
  }

  100% {
    -webkit-transform-origin: left bottom;
            transform-origin: left bottom;
    -webkit-transform: rotate3d(0, 0, 1, -45deg);
            transform: rotate3d(0, 0, 1, -45deg);
    opacity: 0;
  }
}

.rotateOutUpLeft {
  -webkit-animation-name: rotateOutUpLeft;
          animation-name: rotateOutUpLeft;
}

@-webkit-keyframes rotateOutUpRight {
  0% {
    -webkit-transform-origin: right bottom;
            transform-origin: right bottom;
    opacity: 1;
  }

  100% {
    -webkit-transform-origin: right bottom;
            transform-origin: right bottom;
    -webkit-transform: rotate3d(0, 0, 1, 90deg);
            transform: rotate3d(0, 0, 1, 90deg);
    opacity: 0;
  }
}

@keyframes rotateOutUpRight {
  0% {
    -webkit-transform-origin: right bottom;
            transform-origin: right bottom;
    opacity: 1;
  }

  100% {
    -webkit-transform-origin: right bottom;
            transform-origin: right bottom;
    -webkit-transform: rotate3d(0, 0, 1, 90deg);
            transform: rotate3d(0, 0, 1, 90deg);
    opacity: 0;
  }
}

.rotateOutUpRight {
  -webkit-animation-name: rotateOutUpRight;
          animation-name: rotateOutUpRight;
}

@-webkit-keyframes hinge {
  0% {
    -webkit-transform-origin: top left;
            transform-origin: top left;
    -webkit-animation-timing-function: ease-in-out;
            animation-timing-function: ease-in-out;
  }

  20%, 60% {
    -webkit-transform: rotate3d(0, 0, 1, 80deg);
            transform: rotate3d(0, 0, 1, 80deg);
    -webkit-transform-origin: top left;
            transform-origin: top left;
    -webkit-animation-timing-function: ease-in-out;
            animation-timing-function: ease-in-out;
  }

  40%, 80% {
    -webkit-transform: rotate3d(0, 0, 1, 60deg);
            transform: rotate3d(0, 0, 1, 60deg);
    -webkit-transform-origin: top left;
            transform-origin: top left;
    -webkit-animation-timing-function: ease-in-out;
            animation-timing-function: ease-in-out;
    opacity: 1;
  }

  100% {
    -webkit-transform: translate3d(0, 700px, 0);
            transform: translate3d(0, 700px, 0);
    opacity: 0;
  }
}

@keyframes hinge {
  0% {
    -webkit-transform-origin: top left;
            transform-origin: top left;
    -webkit-animation-timing-function: ease-in-out;
            animation-timing-function: ease-in-out;
  }

  20%, 60% {
    -webkit-transform: rotate3d(0, 0, 1, 80deg);
            transform: rotate3d(0, 0, 1, 80deg);
    -webkit-transform-origin: top left;
            transform-origin: top left;
    -webkit-animation-timing-function: ease-in-out;
            animation-timing-function: ease-in-out;
  }

  40%, 80% {
    -webkit-transform: rotate3d(0, 0, 1, 60deg);
            transform: rotate3d(0, 0, 1, 60deg);
    -webkit-transform-origin: top left;
            transform-origin: top left;
    -webkit-animation-timing-function: ease-in-out;
            animation-timing-function: ease-in-out;
    opacity: 1;
  }

  100% {
    -webkit-transform: translate3d(0, 700px, 0);
            transform: translate3d(0, 700px, 0);
    opacity: 0;
  }
}

.hinge {
  -webkit-animation-name: hinge;
          animation-name: hinge;
}

/* originally authored by Nick Pettit - https://github.com/nickpettit/glide */

@-webkit-keyframes rollIn {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(-100%, 0, 0) rotate3d(0, 0, 1, -120deg);
            transform: translate3d(-100%, 0, 0) rotate3d(0, 0, 1, -120deg);
  }

  100% {
    opacity: 1;
    -webkit-transform: none;
            transform: none;
  }
}

@keyframes rollIn {
  0% {
    opacity: 0;
    -webkit-transform: translate3d(-100%, 0, 0) rotate3d(0, 0, 1, -120deg);
            transform: translate3d(-100%, 0, 0) rotate3d(0, 0, 1, -120deg);
  }

  100% {
    opacity: 1;
    -webkit-transform: none;
            transform: none;
  }
}

.rollIn {
  -webkit-animation-name: rollIn;
          animation-name: rollIn;
}

/* originally authored by Nick Pettit - https://github.com/nickpettit/glide */

@-webkit-keyframes rollOut {
  0% {
    opacity: 1;
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(100%, 0, 0) rotate3d(0, 0, 1, 120deg);
            transform: translate3d(100%, 0, 0) rotate3d(0, 0, 1, 120deg);
  }
}

@keyframes rollOut {
  0% {
    opacity: 1;
  }

  100% {
    opacity: 0;
    -webkit-transform: translate3d(100%, 0, 0) rotate3d(0, 0, 1, 120deg);
            transform: translate3d(100%, 0, 0) rotate3d(0, 0, 1, 120deg);
  }
}

.rollOut {
  -webkit-animation-name: rollOut;
          animation-name: rollOut;
}

@-webkit-keyframes zoomIn {
  0% {
    opacity: 0;
    -webkit-transform: scale3d(.3, .3, .3);
            transform: scale3d(.3, .3, .3);
  }

  50% {
    opacity: 1;
  }
}

@keyframes zoomIn {
  0% {
    opacity: 0;
    -webkit-transform: scale3d(.3, .3, .3);
            transform: scale3d(.3, .3, .3);
  }

  50% {
    opacity: 1;
  }
}

.zoomIn {
  -webkit-animation-name: zoomIn;
          animation-name: zoomIn;
}

@-webkit-keyframes zoomInDown {
  0% {
    opacity: 0;
    -webkit-transform: scale3d(.1, .1, .1) translate3d(0, -1000px, 0);
            transform: scale3d(.1, .1, .1) translate3d(0, -1000px, 0);
    -webkit-animation-timing-function: cubic-bezier(0.550, 0.055, 0.675, 0.190);
            animation-timing-function: cubic-bezier(0.550, 0.055, 0.675, 0.190);
  }

  60% {
    opacity: 1;
    -webkit-transform: scale3d(.475, .475, .475) translate3d(0, 60px, 0);
            transform: scale3d(.475, .475, .475) translate3d(0, 60px, 0);
    -webkit-animation-timing-function: cubic-bezier(0.175, 0.885, 0.320, 1);
            animation-timing-function: cubic-bezier(0.175, 0.885, 0.320, 1);
  }
}

@keyframes zoomInDown {
  0% {
    opacity: 0;
    -webkit-transform: scale3d(.1, .1, .1) translate3d(0, -1000px, 0);
            transform: scale3d(.1, .1, .1) translate3d(0, -1000px, 0);
    -webkit-animation-timing-function: cubic-bezier(0.550, 0.055, 0.675, 0.190);
            animation-timing-function: cubic-bezier(0.550, 0.055, 0.675, 0.190);
  }

  60% {
    opacity: 1;
    -webkit-transform: scale3d(.475, .475, .475) translate3d(0, 60px, 0);
            transform: scale3d(.475, .475, .475) translate3d(0, 60px, 0);
    -webkit-animation-timing-function: cubic-bezier(0.175, 0.885, 0.320, 1);
            animation-timing-function: cubic-bezier(0.175, 0.885, 0.320, 1);
  }
}

.zoomInDown {
  -webkit-animation-name: zoomInDown;
          animation-name: zoomInDown;
}

@-webkit-keyframes zoomInLeft {
  0% {
    opacity: 0;
    -webkit-transform: scale3d(.1, .1, .1) translate3d(-1000px, 0, 0);
            transform: scale3d(.1, .1, .1) translate3d(-1000px, 0, 0);
    -webkit-animation-timing-function: cubic-bezier(0.550, 0.055, 0.675, 0.190);
            animation-timing-function: cubic-bezier(0.550, 0.055, 0.675, 0.190);
  }

  60% {
    opacity: 1;
    -webkit-transform: scale3d(.475, .475, .475) translate3d(10px, 0, 0);
            transform: scale3d(.475, .475, .475) translate3d(10px, 0, 0);
    -webkit-animation-timing-function: cubic-bezier(0.175, 0.885, 0.320, 1);
            animation-timing-function: cubic-bezier(0.175, 0.885, 0.320, 1);
  }
}

@keyframes zoomInLeft {
  0% {
    opacity: 0;
    -webkit-transform: scale3d(.1, .1, .1) translate3d(-1000px, 0, 0);
            transform: scale3d(.1, .1, .1) translate3d(-1000px, 0, 0);
    -webkit-animation-timing-function: cubic-bezier(0.550, 0.055, 0.675, 0.190);
            animation-timing-function: cubic-bezier(0.550, 0.055, 0.675, 0.190);
  }

  60% {
    opacity: 1;
    -webkit-transform: scale3d(.475, .475, .475) translate3d(10px, 0, 0);
            transform: scale3d(.475, .475, .475) translate3d(10px, 0, 0);
    -webkit-animation-timing-function: cubic-bezier(0.175, 0.885, 0.320, 1);
            animation-timing-function: cubic-bezier(0.175, 0.885, 0.320, 1);
  }
}

.zoomInLeft {
  -webkit-animation-name: zoomInLeft;
          animation-name: zoomInLeft;
}

@-webkit-keyframes zoomInRight {
  0% {
    opacity: 0;
    -webkit-transform: scale3d(.1, .1, .1) translate3d(1000px, 0, 0);
            transform: scale3d(.1, .1, .1) translate3d(1000px, 0, 0);
    -webkit-animation-timing-function: cubic-bezier(0.550, 0.055, 0.675, 0.190);
            animation-timing-function: cubic-bezier(0.550, 0.055, 0.675, 0.190);
  }

  60% {
    opacity: 1;
    -webkit-transform: scale3d(.475, .475, .475) translate3d(-10px, 0, 0);
            transform: scale3d(.475, .475, .475) translate3d(-10px, 0, 0);
    -webkit-animation-timing-function: cubic-bezier(0.175, 0.885, 0.320, 1);
            animation-timing-function: cubic-bezier(0.175, 0.885, 0.320, 1);
  }
}

@keyframes zoomInRight {
  0% {
    opacity: 0;
    -webkit-transform: scale3d(.1, .1, .1) translate3d(1000px, 0, 0);
            transform: scale3d(.1, .1, .1) translate3d(1000px, 0, 0);
    -webkit-animation-timing-function: cubic-bezier(0.550, 0.055, 0.675, 0.190);
            animation-timing-function: cubic-bezier(0.550, 0.055, 0.675, 0.190);
  }

  60% {
    opacity: 1;
    -webkit-transform: scale3d(.475, .475, .475) translate3d(-10px, 0, 0);
            transform: scale3d(.475, .475, .475) translate3d(-10px, 0, 0);
    -webkit-animation-timing-function: cubic-bezier(0.175, 0.885, 0.320, 1);
            animation-timing-function: cubic-bezier(0.175, 0.885, 0.320, 1);
  }
}

.zoomInRight {
  -webkit-animation-name: zoomInRight;
          animation-name: zoomInRight;
}

@-webkit-keyframes zoomInUp {
  0% {
    opacity: 0;
    -webkit-transform: scale3d(.1, .1, .1) translate3d(0, 1000px, 0);
            transform: scale3d(.1, .1, .1) translate3d(0, 1000px, 0);
    -webkit-animation-timing-function: cubic-bezier(0.550, 0.055, 0.675, 0.190);
            animation-timing-function: cubic-bezier(0.550, 0.055, 0.675, 0.190);
  }

  60% {
    opacity: 1;
    -webkit-transform: scale3d(.475, .475, .475) translate3d(0, -60px, 0);
            transform: scale3d(.475, .475, .475) translate3d(0, -60px, 0);
    -webkit-animation-timing-function: cubic-bezier(0.175, 0.885, 0.320, 1);
            animation-timing-function: cubic-bezier(0.175, 0.885, 0.320, 1);
  }
}

@keyframes zoomInUp {
  0% {
    opacity: 0;
    -webkit-transform: scale3d(.1, .1, .1) translate3d(0, 1000px, 0);
            transform: scale3d(.1, .1, .1) translate3d(0, 1000px, 0);
    -webkit-animation-timing-function: cubic-bezier(0.550, 0.055, 0.675, 0.190);
            animation-timing-function: cubic-bezier(0.550, 0.055, 0.675, 0.190);
  }

  60% {
    opacity: 1;
    -webkit-transform: scale3d(.475, .475, .475) translate3d(0, -60px, 0);
            transform: scale3d(.475, .475, .475) translate3d(0, -60px, 0);
    -webkit-animation-timing-function: cubic-bezier(0.175, 0.885, 0.320, 1);
            animation-timing-function: cubic-bezier(0.175, 0.885, 0.320, 1);
  }
}

.zoomInUp {
  -webkit-animation-name: zoomInUp;
          animation-name: zoomInUp;
}

@-webkit-keyframes zoomOut {
  0% {
    opacity: 1;
  }

  50% {
    opacity: 0;
    -webkit-transform: scale3d(.3, .3, .3);
            transform: scale3d(.3, .3, .3);
  }

  100% {
    opacity: 0;
  }
}

@keyframes zoomOut {
  0% {
    opacity: 1;
  }

  50% {
    opacity: 0;
    -webkit-transform: scale3d(.3, .3, .3);
            transform: scale3d(.3, .3, .3);
  }

  100% {
    opacity: 0;
  }
}

.zoomOut {
  -webkit-animation-name: zoomOut;
          animation-name: zoomOut;
}

@-webkit-keyframes zoomOutDown {
  40% {
    opacity: 1;
    -webkit-transform: scale3d(.475, .475, .475) translate3d(0, -60px, 0);
            transform: scale3d(.475, .475, .475) translate3d(0, -60px, 0);
    -webkit-animation-timing-function: cubic-bezier(0.550, 0.055, 0.675, 0.190);
            animation-timing-function: cubic-bezier(0.550, 0.055, 0.675, 0.190);
  }

  100% {
    opacity: 0;
    -webkit-transform: scale3d(.1, .1, .1) translate3d(0, 2000px, 0);
            transform: scale3d(.1, .1, .1) translate3d(0, 2000px, 0);
    -webkit-transform-origin: center bottom;
            transform-origin: center bottom;
    -webkit-animation-timing-function: cubic-bezier(0.175, 0.885, 0.320, 1);
            animation-timing-function: cubic-bezier(0.175, 0.885, 0.320, 1);
  }
}

@keyframes zoomOutDown {
  40% {
    opacity: 1;
    -webkit-transform: scale3d(.475, .475, .475) translate3d(0, -60px, 0);
            transform: scale3d(.475, .475, .475) translate3d(0, -60px, 0);
    -webkit-animation-timing-function: cubic-bezier(0.550, 0.055, 0.675, 0.190);
            animation-timing-function: cubic-bezier(0.550, 0.055, 0.675, 0.190);
  }

  100% {
    opacity: 0;
    -webkit-transform: scale3d(.1, .1, .1) translate3d(0, 2000px, 0);
            transform: scale3d(.1, .1, .1) translate3d(0, 2000px, 0);
    -webkit-transform-origin: center bottom;
            transform-origin: center bottom;
    -webkit-animation-timing-function: cubic-bezier(0.175, 0.885, 0.320, 1);
            animation-timing-function: cubic-bezier(0.175, 0.885, 0.320, 1);
  }
}

.zoomOutDown {
  -webkit-animation-name: zoomOutDown;
          animation-name: zoomOutDown;
}

@-webkit-keyframes zoomOutLeft {
  40% {
    opacity: 1;
    -webkit-transform: scale3d(.475, .475, .475) translate3d(42px, 0, 0);
            transform: scale3d(.475, .475, .475) translate3d(42px, 0, 0);
  }

  100% {
    opacity: 0;
    -webkit-transform: scale(.1) translate3d(-2000px, 0, 0);
            transform: scale(.1) translate3d(-2000px, 0, 0);
    -webkit-transform-origin: left center;
            transform-origin: left center;
  }
}

@keyframes zoomOutLeft {
  40% {
    opacity: 1;
    -webkit-transform: scale3d(.475, .475, .475) translate3d(42px, 0, 0);
            transform: scale3d(.475, .475, .475) translate3d(42px, 0, 0);
  }

  100% {
    opacity: 0;
    -webkit-transform: scale(.1) translate3d(-2000px, 0, 0);
            transform: scale(.1) translate3d(-2000px, 0, 0);
    -webkit-transform-origin: left center;
            transform-origin: left center;
  }
}

.zoomOutLeft {
  -webkit-animation-name: zoomOutLeft;
          animation-name: zoomOutLeft;
}

@-webkit-keyframes zoomOutRight {
  40% {
    opacity: 1;
    -webkit-transform: scale3d(.475, .475, .475) translate3d(-42px, 0, 0);
            transform: scale3d(.475, .475, .475) translate3d(-42px, 0, 0);
  }

  100% {
    opacity: 0;
    -webkit-transform: scale(.1) translate3d(2000px, 0, 0);
            transform: scale(.1) translate3d(2000px, 0, 0);
    -webkit-transform-origin: right center;
            transform-origin: right center;
  }
}

@keyframes zoomOutRight {
  40% {
    opacity: 1;
    -webkit-transform: scale3d(.475, .475, .475) translate3d(-42px, 0, 0);
            transform: scale3d(.475, .475, .475) translate3d(-42px, 0, 0);
  }

  100% {
    opacity: 0;
    -webkit-transform: scale(.1) translate3d(2000px, 0, 0);
            transform: scale(.1) translate3d(2000px, 0, 0);
    -webkit-transform-origin: right center;
            transform-origin: right center;
  }
}

.zoomOutRight {
  -webkit-animation-name: zoomOutRight;
          animation-name: zoomOutRight;
}

@-webkit-keyframes zoomOutUp {
  40% {
    opacity: 1;
    -webkit-transform: scale3d(.475, .475, .475) translate3d(0, 60px, 0);
            transform: scale3d(.475, .475, .475) translate3d(0, 60px, 0);
    -webkit-animation-timing-function: cubic-bezier(0.550, 0.055, 0.675, 0.190);
            animation-timing-function: cubic-bezier(0.550, 0.055, 0.675, 0.190);
  }

  100% {
    opacity: 0;
    -webkit-transform: scale3d(.1, .1, .1) translate3d(0, -2000px, 0);
            transform: scale3d(.1, .1, .1) translate3d(0, -2000px, 0);
    -webkit-transform-origin: center bottom;
            transform-origin: center bottom;
    -webkit-animation-timing-function: cubic-bezier(0.175, 0.885, 0.320, 1);
            animation-timing-function: cubic-bezier(0.175, 0.885, 0.320, 1);
  }
}

@keyframes zoomOutUp {
  40% {
    opacity: 1;
    -webkit-transform: scale3d(.475, .475, .475) translate3d(0, 60px, 0);
            transform: scale3d(.475, .475, .475) translate3d(0, 60px, 0);
    -webkit-animation-timing-function: cubic-bezier(0.550, 0.055, 0.675, 0.190);
            animation-timing-function: cubic-bezier(0.550, 0.055, 0.675, 0.190);
  }

  100% {
    opacity: 0;
    -webkit-transform: scale3d(.1, .1, .1) translate3d(0, -2000px, 0);
            transform: scale3d(.1, .1, .1) translate3d(0, -2000px, 0);
    -webkit-transform-origin: center bottom;
            transform-origin: center bottom;
    -webkit-animation-timing-function: cubic-bezier(0.175, 0.885, 0.320, 1);
            animation-timing-function: cubic-bezier(0.175, 0.885, 0.320, 1);
  }
}

.zoomOutUp {
  -webkit-animation-name: zoomOutUp;
          animation-name: zoomOutUp;
}

@-webkit-keyframes slideInDown {
  0% {
    -webkit-transform: translateY(-100%);
            transform: translateY(-100%);
    visibility: visible;
  }

  100% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
  }
}

@keyframes slideInDown {
  0% {
    -webkit-transform: translateY(-100%);
            transform: translateY(-100%);
    visibility: visible;
  }

  100% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
  }
}

.slideInDown {
  -webkit-animation-name: slideInDown;
          animation-name: slideInDown;
}

@-webkit-keyframes slideInLeft {
  0% {
    -webkit-transform: translateX(-100%);
            transform: translateX(-100%);
    visibility: visible;
  }

  100% {
    -webkit-transform: translateX(0);
            transform: translateX(0);
  }
}

@keyframes slideInLeft {
  0% {
    -webkit-transform: translateX(-100%);
            transform: translateX(-100%);
    visibility: visible;
  }

  100% {
    -webkit-transform: translateX(0);
            transform: translateX(0);
  }
}

.slideInLeft {
  -webkit-animation-name: slideInLeft;
          animation-name: slideInLeft;
}

@-webkit-keyframes slideInRight {
  0% {
    -webkit-transform: translateX(100%);
            transform: translateX(100%);
    visibility: visible;
  }

  100% {
    -webkit-transform: translateX(0);
            transform: translateX(0);
  }
}

@keyframes slideInRight {
  0% {
    -webkit-transform: translateX(100%);
            transform: translateX(100%);
    visibility: visible;
  }

  100% {
    -webkit-transform: translateX(0);
            transform: translateX(0);
  }
}

.slideInRight {
  -webkit-animation-name: slideInRight;
          animation-name: slideInRight;
}

@-webkit-keyframes slideInUp {
  0% {
    -webkit-transform: translateY(100%);
            transform: translateY(100%);
    visibility: visible;
  }

  100% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
  }
}

@keyframes slideInUp {
  0% {
    -webkit-transform: translateY(100%);
            transform: translateY(100%);
    visibility: visible;
  }

  100% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
  }
}

.slideInUp {
  -webkit-animation-name: slideInUp;
          animation-name: slideInUp;
}

@-webkit-keyframes slideOutDown {
  0% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
  }

  100% {
    visibility: hidden;
    -webkit-transform: translateY(100%);
            transform: translateY(100%);
  }
}

@keyframes slideOutDown {
  0% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
  }

  100% {
    visibility: hidden;
    -webkit-transform: translateY(100%);
            transform: translateY(100%);
  }
}

.slideOutDown {
  -webkit-animation-name: slideOutDown;
          animation-name: slideOutDown;
}

@-webkit-keyframes slideOutLeft {
  0% {
    -webkit-transform: translateX(0);
            transform: translateX(0);
  }

  100% {
    visibility: hidden;
    -webkit-transform: translateX(-100%);
            transform: translateX(-100%);
  }
}

@keyframes slideOutLeft {
  0% {
    -webkit-transform: translateX(0);
            transform: translateX(0);
  }

  100% {
    visibility: hidden;
    -webkit-transform: translateX(-100%);
            transform: translateX(-100%);
  }
}

.slideOutLeft {
  -webkit-animation-name: slideOutLeft;
          animation-name: slideOutLeft;
}

@-webkit-keyframes slideOutRight {
  0% {
    -webkit-transform: translateX(0);
            transform: translateX(0);
  }

  100% {
    visibility: hidden;
    -webkit-transform: translateX(100%);
            transform: translateX(100%);
  }
}

@keyframes slideOutRight {
  0% {
    -webkit-transform: translateX(0);
            transform: translateX(0);
  }

  100% {
    visibility: hidden;
    -webkit-transform: translateX(100%);
            transform: translateX(100%);
  }
}

.slideOutRight {
  -webkit-animation-name: slideOutRight;
          animation-name: slideOutRight;
}

@-webkit-keyframes slideOutUp {
  0% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
  }

  100% {
    visibility: hidden;
    -webkit-transform: translateY(-100%);
            transform: translateY(-100%);
  }
}

@keyframes slideOutUp {
  0% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
  }

  100% {
    visibility: hidden;
    -webkit-transform: translateY(-100%);
            transform: translateY(-100%);
  }
}

.slideOutUp {
  -webkit-animation-name: slideOutUp;
          animation-name: slideOutUp;
}
/*!
 *  Font Awesome 4.3.0 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */@font-face{font-family:'FontAwesome';src:url('../fonts/fontawesome-webfont.eot?v=4.3.0');src:url('../fonts/fontawesome-webfont.eot?#iefix&v=4.3.0') format('embedded-opentype'),url('../fonts/fontawesome-webfont.woff2?v=4.3.0') format('woff2'),url('../fonts/fontawesome-webfont.woff?v=4.3.0') format('woff'),url('../fonts/fontawesome-webfont.ttf?v=4.3.0') format('truetype'),url('../fonts/fontawesome-webfont.svg?v=4.3.0#fontawesomeregular') format('svg');font-weight:normal;font-style:normal}.fa{display:inline-block;font:normal normal normal 14px/1 FontAwesome;font-size:inherit;text-rendering:auto;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale;transform:translate(0, 0)}.fa-lg{font-size:1.33333333em;line-height:.75em;vertical-align:-15%}.fa-2x{font-size:2em}.fa-3x{font-size:3em}.fa-4x{font-size:4em}.fa-5x{font-size:5em}.fa-fw{width:1.28571429em;text-align:center}.fa-ul{padding-left:0;margin-left:2.14285714em;list-style-type:none}.fa-ul>li{position:relative}.fa-li{position:absolute;left:-2.14285714em;width:2.14285714em;top:.14285714em;text-align:center}.fa-li.fa-lg{left:-1.85714286em}.fa-border{padding:.2em .25em .15em;border:solid .08em #eee;border-radius:.1em}.pull-right{float:right}.pull-left{float:left}.fa.pull-left{margin-right:.3em}.fa.pull-right{margin-left:.3em}.fa-spin{-webkit-animation:fa-spin 2s infinite linear;animation:fa-spin 2s infinite linear}.fa-pulse{-webkit-animation:fa-spin 1s infinite steps(8);animation:fa-spin 1s infinite steps(8)}@-webkit-keyframes fa-spin{0%{-webkit-transform:rotate(0deg);transform:rotate(0deg)}100%{-webkit-transform:rotate(359deg);transform:rotate(359deg)}}@keyframes fa-spin{0%{-webkit-transform:rotate(0deg);transform:rotate(0deg)}100%{-webkit-transform:rotate(359deg);transform:rotate(359deg)}}.fa-rotate-90{filter:progid:DXImageTransform.Microsoft.BasicImage(rotation=1);-webkit-transform:rotate(90deg);-ms-transform:rotate(90deg);transform:rotate(90deg)}.fa-rotate-180{filter:progid:DXImageTransform.Microsoft.BasicImage(rotation=2);-webkit-transform:rotate(180deg);-ms-transform:rotate(180deg);transform:rotate(180deg)}.fa-rotate-270{filter:progid:DXImageTransform.Microsoft.BasicImage(rotation=3);-webkit-transform:rotate(270deg);-ms-transform:rotate(270deg);transform:rotate(270deg)}.fa-flip-horizontal{filter:progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1);-webkit-transform:scale(-1, 1);-ms-transform:scale(-1, 1);transform:scale(-1, 1)}.fa-flip-vertical{filter:progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1);-webkit-transform:scale(1, -1);-ms-transform:scale(1, -1);transform:scale(1, -1)}:root .fa-rotate-90,:root .fa-rotate-180,:root .fa-rotate-270,:root .fa-flip-horizontal,:root .fa-flip-vertical{filter:none}.fa-stack{position:relative;display:inline-block;width:2em;height:2em;line-height:2em;vertical-align:middle}.fa-stack-1x,.fa-stack-2x{position:absolute;left:0;width:100%;text-align:center}.fa-stack-1x{line-height:inherit}.fa-stack-2x{font-size:2em}.fa-inverse{color:#fff}.fa-glass:before{content:"\f000"}.fa-music:before{content:"\f001"}.fa-search:before{content:"\f002"}.fa-envelope-o:before{content:"\f003"}.fa-heart:before{content:"\f004"}.fa-star:before{content:"\f005"}.fa-star-o:before{content:"\f006"}.fa-user:before{content:"\f007"}.fa-film:before{content:"\f008"}.fa-th-large:before{content:"\f009"}.fa-th:before{content:"\f00a"}.fa-th-list:before{content:"\f00b"}.fa-check:before{content:"\f00c"}.fa-remove:before,.fa-close:before,.fa-times:before{content:"\f00d"}.fa-search-plus:before{content:"\f00e"}.fa-search-minus:before{content:"\f010"}.fa-power-off:before{content:"\f011"}.fa-signal:before{content:"\f012"}.fa-gear:before,.fa-cog:before{content:"\f013"}.fa-trash-o:before{content:"\f014"}.fa-home:before{content:"\f015"}.fa-file-o:before{content:"\f016"}.fa-clock-o:before{content:"\f017"}.fa-road:before{content:"\f018"}.fa-download:before{content:"\f019"}.fa-arrow-circle-o-down:before{content:"\f01a"}.fa-arrow-circle-o-up:before{content:"\f01b"}.fa-inbox:before{content:"\f01c"}.fa-play-circle-o:before{content:"\f01d"}.fa-rotate-right:before,.fa-repeat:before{content:"\f01e"}.fa-refresh:before{content:"\f021"}.fa-list-alt:before{content:"\f022"}.fa-lock:before{content:"\f023"}.fa-flag:before{content:"\f024"}.fa-headphones:before{content:"\f025"}.fa-volume-off:before{content:"\f026"}.fa-volume-down:before{content:"\f027"}.fa-volume-up:before{content:"\f028"}.fa-qrcode:before{content:"\f029"}.fa-barcode:before{content:"\f02a"}.fa-tag:before{content:"\f02b"}.fa-tags:before{content:"\f02c"}.fa-book:before{content:"\f02d"}.fa-bookmark:before{content:"\f02e"}.fa-print:before{content:"\f02f"}.fa-camera:before{content:"\f030"}.fa-font:before{content:"\f031"}.fa-bold:before{content:"\f032"}.fa-italic:before{content:"\f033"}.fa-text-height:before{content:"\f034"}.fa-text-width:before{content:"\f035"}.fa-align-left:before{content:"\f036"}.fa-align-center:before{content:"\f037"}.fa-align-right:before{content:"\f038"}.fa-align-justify:before{content:"\f039"}.fa-list:before{content:"\f03a"}.fa-dedent:before,.fa-outdent:before{content:"\f03b"}.fa-indent:before{content:"\f03c"}.fa-video-camera:before{content:"\f03d"}.fa-photo:before,.fa-image:before,.fa-picture-o:before{content:"\f03e"}.fa-pencil:before{content:"\f040"}.fa-map-marker:before{content:"\f041"}.fa-adjust:before{content:"\f042"}.fa-tint:before{content:"\f043"}.fa-edit:before,.fa-pencil-square-o:before{content:"\f044"}.fa-share-square-o:before{content:"\f045"}.fa-check-square-o:before{content:"\f046"}.fa-arrows:before{content:"\f047"}.fa-step-backward:before{content:"\f048"}.fa-fast-backward:before{content:"\f049"}.fa-backward:before{content:"\f04a"}.fa-play:before{content:"\f04b"}.fa-pause:before{content:"\f04c"}.fa-stop:before{content:"\f04d"}.fa-forward:before{content:"\f04e"}.fa-fast-forward:before{content:"\f050"}.fa-step-forward:before{content:"\f051"}.fa-eject:before{content:"\f052"}.fa-chevron-left:before{content:"\f053"}.fa-chevron-right:before{content:"\f054"}.fa-plus-circle:before{content:"\f055"}.fa-minus-circle:before{content:"\f056"}.fa-times-circle:before{content:"\f057"}.fa-check-circle:before{content:"\f058"}.fa-question-circle:before{content:"\f059"}.fa-info-circle:before{content:"\f05a"}.fa-crosshairs:before{content:"\f05b"}.fa-times-circle-o:before{content:"\f05c"}.fa-check-circle-o:before{content:"\f05d"}.fa-ban:before{content:"\f05e"}.fa-arrow-left:before{content:"\f060"}.fa-arrow-right:before{content:"\f061"}.fa-arrow-up:before{content:"\f062"}.fa-arrow-down:before{content:"\f063"}.fa-mail-forward:before,.fa-share:before{content:"\f064"}.fa-expand:before{content:"\f065"}.fa-compress:before{content:"\f066"}.fa-plus:before{content:"\f067"}.fa-minus:before{content:"\f068"}.fa-asterisk:before{content:"\f069"}.fa-exclamation-circle:before{content:"\f06a"}.fa-gift:before{content:"\f06b"}.fa-leaf:before{content:"\f06c"}.fa-fire:before{content:"\f06d"}.fa-eye:before{content:"\f06e"}.fa-eye-slash:before{content:"\f070"}.fa-warning:before,.fa-exclamation-triangle:before{content:"\f071"}.fa-plane:before{content:"\f072"}.fa-calendar:before{content:"\f073"}.fa-random:before{content:"\f074"}.fa-comment:before{content:"\f075"}.fa-magnet:before{content:"\f076"}.fa-chevron-up:before{content:"\f077"}.fa-chevron-down:before{content:"\f078"}.fa-retweet:before{content:"\f079"}.fa-shopping-cart:before{content:"\f07a"}.fa-folder:before{content:"\f07b"}.fa-folder-open:before{content:"\f07c"}.fa-arrows-v:before{content:"\f07d"}.fa-arrows-h:before{content:"\f07e"}.fa-bar-chart-o:before,.fa-bar-chart:before{content:"\f080"}.fa-twitter-square:before{content:"\f081"}.fa-facebook-square:before{content:"\f082"}.fa-camera-retro:before{content:"\f083"}.fa-key:before{content:"\f084"}.fa-gears:before,.fa-cogs:before{content:"\f085"}.fa-comments:before{content:"\f086"}.fa-thumbs-o-up:before{content:"\f087"}.fa-thumbs-o-down:before{content:"\f088"}.fa-star-half:before{content:"\f089"}.fa-heart-o:before{content:"\f08a"}.fa-sign-out:before{content:"\f08b"}.fa-linkedin-square:before{content:"\f08c"}.fa-thumb-tack:before{content:"\f08d"}.fa-external-link:before{content:"\f08e"}.fa-sign-in:before{content:"\f090"}.fa-trophy:before{content:"\f091"}.fa-github-square:before{content:"\f092"}.fa-upload:before{content:"\f093"}.fa-lemon-o:before{content:"\f094"}.fa-phone:before{content:"\f095"}.fa-square-o:before{content:"\f096"}.fa-bookmark-o:before{content:"\f097"}.fa-phone-square:before{content:"\f098"}.fa-twitter:before{content:"\f099"}.fa-facebook-f:before,.fa-facebook:before{content:"\f09a"}.fa-github:before{content:"\f09b"}.fa-unlock:before{content:"\f09c"}.fa-credit-card:before{content:"\f09d"}.fa-rss:before{content:"\f09e"}.fa-hdd-o:before{content:"\f0a0"}.fa-bullhorn:before{content:"\f0a1"}.fa-bell:before{content:"\f0f3"}.fa-certificate:before{content:"\f0a3"}.fa-hand-o-right:before{content:"\f0a4"}.fa-hand-o-left:before{content:"\f0a5"}.fa-hand-o-up:before{content:"\f0a6"}.fa-hand-o-down:before{content:"\f0a7"}.fa-arrow-circle-left:before{content:"\f0a8"}.fa-arrow-circle-right:before{content:"\f0a9"}.fa-arrow-circle-up:before{content:"\f0aa"}.fa-arrow-circle-down:before{content:"\f0ab"}.fa-globe:before{content:"\f0ac"}.fa-wrench:before{content:"\f0ad"}.fa-tasks:before{content:"\f0ae"}.fa-filter:before{content:"\f0b0"}.fa-briefcase:before{content:"\f0b1"}.fa-arrows-alt:before{content:"\f0b2"}.fa-group:before,.fa-users:before{content:"\f0c0"}.fa-chain:before,.fa-link:before{content:"\f0c1"}.fa-cloud:before{content:"\f0c2"}.fa-flask:before{content:"\f0c3"}.fa-cut:before,.fa-scissors:before{content:"\f0c4"}.fa-copy:before,.fa-files-o:before{content:"\f0c5"}.fa-paperclip:before{content:"\f0c6"}.fa-save:before,.fa-floppy-o:before{content:"\f0c7"}.fa-square:before{content:"\f0c8"}.fa-navicon:before,.fa-reorder:before,.fa-bars:before{content:"\f0c9"}.fa-list-ul:before{content:"\f0ca"}.fa-list-ol:before{content:"\f0cb"}.fa-strikethrough:before{content:"\f0cc"}.fa-underline:before{content:"\f0cd"}.fa-table:before{content:"\f0ce"}.fa-magic:before{content:"\f0d0"}.fa-truck:before{content:"\f0d1"}.fa-pinterest:before{content:"\f0d2"}.fa-pinterest-square:before{content:"\f0d3"}.fa-google-plus-square:before{content:"\f0d4"}.fa-google-plus:before{content:"\f0d5"}.fa-money:before{content:"\f0d6"}.fa-caret-down:before{content:"\f0d7"}.fa-caret-up:before{content:"\f0d8"}.fa-caret-left:before{content:"\f0d9"}.fa-caret-right:before{content:"\f0da"}.fa-columns:before{content:"\f0db"}.fa-unsorted:before,.fa-sort:before{content:"\f0dc"}.fa-sort-down:before,.fa-sort-desc:before{content:"\f0dd"}.fa-sort-up:before,.fa-sort-asc:before{content:"\f0de"}.fa-envelope:before{content:"\f0e0"}.fa-linkedin:before{content:"\f0e1"}.fa-rotate-left:before,.fa-undo:before{content:"\f0e2"}.fa-legal:before,.fa-gavel:before{content:"\f0e3"}.fa-dashboard:before,.fa-tachometer:before{content:"\f0e4"}.fa-comment-o:before{content:"\f0e5"}.fa-comments-o:before{content:"\f0e6"}.fa-flash:before,.fa-bolt:before{content:"\f0e7"}.fa-sitemap:before{content:"\f0e8"}.fa-umbrella:before{content:"\f0e9"}.fa-paste:before,.fa-clipboard:before{content:"\f0ea"}.fa-lightbulb-o:before{content:"\f0eb"}.fa-exchange:before{content:"\f0ec"}.fa-cloud-download:before{content:"\f0ed"}.fa-cloud-upload:before{content:"\f0ee"}.fa-user-md:before{content:"\f0f0"}.fa-stethoscope:before{content:"\f0f1"}.fa-suitcase:before{content:"\f0f2"}.fa-bell-o:before{content:"\f0a2"}.fa-coffee:before{content:"\f0f4"}.fa-cutlery:before{content:"\f0f5"}.fa-file-text-o:before{content:"\f0f6"}.fa-building-o:before{content:"\f0f7"}.fa-hospital-o:before{content:"\f0f8"}.fa-ambulance:before{content:"\f0f9"}.fa-medkit:before{content:"\f0fa"}.fa-fighter-jet:before{content:"\f0fb"}.fa-beer:before{content:"\f0fc"}.fa-h-square:before{content:"\f0fd"}.fa-plus-square:before{content:"\f0fe"}.fa-angle-double-left:before{content:"\f100"}.fa-angle-double-right:before{content:"\f101"}.fa-angle-double-up:before{content:"\f102"}.fa-angle-double-down:before{content:"\f103"}.fa-angle-left:before{content:"\f104"}.fa-angle-right:before{content:"\f105"}.fa-angle-up:before{content:"\f106"}.fa-angle-down:before{content:"\f107"}.fa-desktop:before{content:"\f108"}.fa-laptop:before{content:"\f109"}.fa-tablet:before{content:"\f10a"}.fa-mobile-phone:before,.fa-mobile:before{content:"\f10b"}.fa-circle-o:before{content:"\f10c"}.fa-quote-left:before{content:"\f10d"}.fa-quote-right:before{content:"\f10e"}.fa-spinner:before{content:"\f110"}.fa-circle:before{content:"\f111"}.fa-mail-reply:before,.fa-reply:before{content:"\f112"}.fa-github-alt:before{content:"\f113"}.fa-folder-o:before{content:"\f114"}.fa-folder-open-o:before{content:"\f115"}.fa-smile-o:before{content:"\f118"}.fa-frown-o:before{content:"\f119"}.fa-meh-o:before{content:"\f11a"}.fa-gamepad:before{content:"\f11b"}.fa-keyboard-o:before{content:"\f11c"}.fa-flag-o:before{content:"\f11d"}.fa-flag-checkered:before{content:"\f11e"}.fa-terminal:before{content:"\f120"}.fa-code:before{content:"\f121"}.fa-mail-reply-all:before,.fa-reply-all:before{content:"\f122"}.fa-star-half-empty:before,.fa-star-half-full:before,.fa-star-half-o:before{content:"\f123"}.fa-location-arrow:before{content:"\f124"}.fa-crop:before{content:"\f125"}.fa-code-fork:before{content:"\f126"}.fa-unlink:before,.fa-chain-broken:before{content:"\f127"}.fa-question:before{content:"\f128"}.fa-info:before{content:"\f129"}.fa-exclamation:before{content:"\f12a"}.fa-superscript:before{content:"\f12b"}.fa-subscript:before{content:"\f12c"}.fa-eraser:before{content:"\f12d"}.fa-puzzle-piece:before{content:"\f12e"}.fa-microphone:before{content:"\f130"}.fa-microphone-slash:before{content:"\f131"}.fa-shield:before{content:"\f132"}.fa-calendar-o:before{content:"\f133"}.fa-fire-extinguisher:before{content:"\f134"}.fa-rocket:before{content:"\f135"}.fa-maxcdn:before{content:"\f136"}.fa-chevron-circle-left:before{content:"\f137"}.fa-chevron-circle-right:before{content:"\f138"}.fa-chevron-circle-up:before{content:"\f139"}.fa-chevron-circle-down:before{content:"\f13a"}.fa-html5:before{content:"\f13b"}.fa-css3:before{content:"\f13c"}.fa-anchor:before{content:"\f13d"}.fa-unlock-alt:before{content:"\f13e"}.fa-bullseye:before{content:"\f140"}.fa-ellipsis-h:before{content:"\f141"}.fa-ellipsis-v:before{content:"\f142"}.fa-rss-square:before{content:"\f143"}.fa-play-circle:before{content:"\f144"}.fa-ticket:before{content:"\f145"}.fa-minus-square:before{content:"\f146"}.fa-minus-square-o:before{content:"\f147"}.fa-level-up:before{content:"\f148"}.fa-level-down:before{content:"\f149"}.fa-check-square:before{content:"\f14a"}.fa-pencil-square:before{content:"\f14b"}.fa-external-link-square:before{content:"\f14c"}.fa-share-square:before{content:"\f14d"}.fa-compass:before{content:"\f14e"}.fa-toggle-down:before,.fa-caret-square-o-down:before{content:"\f150"}.fa-toggle-up:before,.fa-caret-square-o-up:before{content:"\f151"}.fa-toggle-right:before,.fa-caret-square-o-right:before{content:"\f152"}.fa-euro:before,.fa-eur:before{content:"\f153"}.fa-gbp:before{content:"\f154"}.fa-dollar:before,.fa-usd:before{content:"\f155"}.fa-rupee:before,.fa-inr:before{content:"\f156"}.fa-cny:before,.fa-rmb:before,.fa-yen:before,.fa-jpy:before{content:"\f157"}.fa-ruble:before,.fa-rouble:before,.fa-rub:before{content:"\f158"}.fa-won:before,.fa-krw:before{content:"\f159"}.fa-bitcoin:before,.fa-btc:before{content:"\f15a"}.fa-file:before{content:"\f15b"}.fa-file-text:before{content:"\f15c"}.fa-sort-alpha-asc:before{content:"\f15d"}.fa-sort-alpha-desc:before{content:"\f15e"}.fa-sort-amount-asc:before{content:"\f160"}.fa-sort-amount-desc:before{content:"\f161"}.fa-sort-numeric-asc:before{content:"\f162"}.fa-sort-numeric-desc:before{content:"\f163"}.fa-thumbs-up:before{content:"\f164"}.fa-thumbs-down:before{content:"\f165"}.fa-youtube-square:before{content:"\f166"}.fa-youtube:before{content:"\f167"}.fa-xing:before{content:"\f168"}.fa-xing-square:before{content:"\f169"}.fa-youtube-play:before{content:"\f16a"}.fa-dropbox:before{content:"\f16b"}.fa-stack-overflow:before{content:"\f16c"}.fa-instagram:before{content:"\f16d"}.fa-flickr:before{content:"\f16e"}.fa-adn:before{content:"\f170"}.fa-bitbucket:before{content:"\f171"}.fa-bitbucket-square:before{content:"\f172"}.fa-tumblr:before{content:"\f173"}.fa-tumblr-square:before{content:"\f174"}.fa-long-arrow-down:before{content:"\f175"}.fa-long-arrow-up:before{content:"\f176"}.fa-long-arrow-left:before{content:"\f177"}.fa-long-arrow-right:before{content:"\f178"}.fa-apple:before{content:"\f179"}.fa-windows:before{content:"\f17a"}.fa-android:before{content:"\f17b"}.fa-linux:before{content:"\f17c"}.fa-dribbble:before{content:"\f17d"}.fa-skype:before{content:"\f17e"}.fa-foursquare:before{content:"\f180"}.fa-trello:before{content:"\f181"}.fa-female:before{content:"\f182"}.fa-male:before{content:"\f183"}.fa-gittip:before,.fa-gratipay:before{content:"\f184"}.fa-sun-o:before{content:"\f185"}.fa-moon-o:before{content:"\f186"}.fa-archive:before{content:"\f187"}.fa-bug:before{content:"\f188"}.fa-vk:before{content:"\f189"}.fa-weibo:before{content:"\f18a"}.fa-renren:before{content:"\f18b"}.fa-pagelines:before{content:"\f18c"}.fa-stack-exchange:before{content:"\f18d"}.fa-arrow-circle-o-right:before{content:"\f18e"}.fa-arrow-circle-o-left:before{content:"\f190"}.fa-toggle-left:before,.fa-caret-square-o-left:before{content:"\f191"}.fa-dot-circle-o:before{content:"\f192"}.fa-wheelchair:before{content:"\f193"}.fa-vimeo-square:before{content:"\f194"}.fa-turkish-lira:before,.fa-try:before{content:"\f195"}.fa-plus-square-o:before{content:"\f196"}.fa-space-shuttle:before{content:"\f197"}.fa-slack:before{content:"\f198"}.fa-envelope-square:before{content:"\f199"}.fa-wordpress:before{content:"\f19a"}.fa-openid:before{content:"\f19b"}.fa-institution:before,.fa-bank:before,.fa-university:before{content:"\f19c"}.fa-mortar-board:before,.fa-graduation-cap:before{content:"\f19d"}.fa-yahoo:before{content:"\f19e"}.fa-google:before{content:"\f1a0"}.fa-reddit:before{content:"\f1a1"}.fa-reddit-square:before{content:"\f1a2"}.fa-stumbleupon-circle:before{content:"\f1a3"}.fa-stumbleupon:before{content:"\f1a4"}.fa-delicious:before{content:"\f1a5"}.fa-digg:before{content:"\f1a6"}.fa-pied-piper:before{content:"\f1a7"}.fa-pied-piper-alt:before{content:"\f1a8"}.fa-drupal:before{content:"\f1a9"}.fa-joomla:before{content:"\f1aa"}.fa-language:before{content:"\f1ab"}.fa-fax:before{content:"\f1ac"}.fa-building:before{content:"\f1ad"}.fa-child:before{content:"\f1ae"}.fa-paw:before{content:"\f1b0"}.fa-spoon:before{content:"\f1b1"}.fa-cube:before{content:"\f1b2"}.fa-cubes:before{content:"\f1b3"}.fa-behance:before{content:"\f1b4"}.fa-behance-square:before{content:"\f1b5"}.fa-steam:before{content:"\f1b6"}.fa-steam-square:before{content:"\f1b7"}.fa-recycle:before{content:"\f1b8"}.fa-automobile:before,.fa-car:before{content:"\f1b9"}.fa-cab:before,.fa-taxi:before{content:"\f1ba"}.fa-tree:before{content:"\f1bb"}.fa-spotify:before{content:"\f1bc"}.fa-deviantart:before{content:"\f1bd"}.fa-soundcloud:before{content:"\f1be"}.fa-database:before{content:"\f1c0"}.fa-file-pdf-o:before{content:"\f1c1"}.fa-file-word-o:before{content:"\f1c2"}.fa-file-excel-o:before{content:"\f1c3"}.fa-file-powerpoint-o:before{content:"\f1c4"}.fa-file-photo-o:before,.fa-file-picture-o:before,.fa-file-image-o:before{content:"\f1c5"}.fa-file-zip-o:before,.fa-file-archive-o:before{content:"\f1c6"}.fa-file-sound-o:before,.fa-file-audio-o:before{content:"\f1c7"}.fa-file-movie-o:before,.fa-file-video-o:before{content:"\f1c8"}.fa-file-code-o:before{content:"\f1c9"}.fa-vine:before{content:"\f1ca"}.fa-codepen:before{content:"\f1cb"}.fa-jsfiddle:before{content:"\f1cc"}.fa-life-bouy:before,.fa-life-buoy:before,.fa-life-saver:before,.fa-support:before,.fa-life-ring:before{content:"\f1cd"}.fa-circle-o-notch:before{content:"\f1ce"}.fa-ra:before,.fa-rebel:before{content:"\f1d0"}.fa-ge:before,.fa-empire:before{content:"\f1d1"}.fa-git-square:before{content:"\f1d2"}.fa-git:before{content:"\f1d3"}.fa-hacker-news:before{content:"\f1d4"}.fa-tencent-weibo:before{content:"\f1d5"}.fa-qq:before{content:"\f1d6"}.fa-wechat:before,.fa-weixin:before{content:"\f1d7"}.fa-send:before,.fa-paper-plane:before{content:"\f1d8"}.fa-send-o:before,.fa-paper-plane-o:before{content:"\f1d9"}.fa-history:before{content:"\f1da"}.fa-genderless:before,.fa-circle-thin:before{content:"\f1db"}.fa-header:before{content:"\f1dc"}.fa-paragraph:before{content:"\f1dd"}.fa-sliders:before{content:"\f1de"}.fa-share-alt:before{content:"\f1e0"}.fa-share-alt-square:before{content:"\f1e1"}.fa-bomb:before{content:"\f1e2"}.fa-soccer-ball-o:before,.fa-futbol-o:before{content:"\f1e3"}.fa-tty:before{content:"\f1e4"}.fa-binoculars:before{content:"\f1e5"}.fa-plug:before{content:"\f1e6"}.fa-slideshare:before{content:"\f1e7"}.fa-twitch:before{content:"\f1e8"}.fa-yelp:before{content:"\f1e9"}.fa-newspaper-o:before{content:"\f1ea"}.fa-wifi:before{content:"\f1eb"}.fa-calculator:before{content:"\f1ec"}.fa-paypal:before{content:"\f1ed"}.fa-google-wallet:before{content:"\f1ee"}.fa-cc-visa:before{content:"\f1f0"}.fa-cc-mastercard:before{content:"\f1f1"}.fa-cc-discover:before{content:"\f1f2"}.fa-cc-amex:before{content:"\f1f3"}.fa-cc-paypal:before{content:"\f1f4"}.fa-cc-stripe:before{content:"\f1f5"}.fa-bell-slash:before{content:"\f1f6"}.fa-bell-slash-o:before{content:"\f1f7"}.fa-trash:before{content:"\f1f8"}.fa-copyright:before{content:"\f1f9"}.fa-at:before{content:"\f1fa"}.fa-eyedropper:before{content:"\f1fb"}.fa-paint-brush:before{content:"\f1fc"}.fa-birthday-cake:before{content:"\f1fd"}.fa-area-chart:before{content:"\f1fe"}.fa-pie-chart:before{content:"\f200"}.fa-line-chart:before{content:"\f201"}.fa-lastfm:before{content:"\f202"}.fa-lastfm-square:before{content:"\f203"}.fa-toggle-off:before{content:"\f204"}.fa-toggle-on:before{content:"\f205"}.fa-bicycle:before{content:"\f206"}.fa-bus:before{content:"\f207"}.fa-ioxhost:before{content:"\f208"}.fa-angellist:before{content:"\f209"}.fa-cc:before{content:"\f20a"}.fa-shekel:before,.fa-sheqel:before,.fa-ils:before{content:"\f20b"}.fa-meanpath:before{content:"\f20c"}.fa-buysellads:before{content:"\f20d"}.fa-connectdevelop:before{content:"\f20e"}.fa-dashcube:before{content:"\f210"}.fa-forumbee:before{content:"\f211"}.fa-leanpub:before{content:"\f212"}.fa-sellsy:before{content:"\f213"}.fa-shirtsinbulk:before{content:"\f214"}.fa-simplybuilt:before{content:"\f215"}.fa-skyatlas:before{content:"\f216"}.fa-cart-plus:before{content:"\f217"}.fa-cart-arrow-down:before{content:"\f218"}.fa-diamond:before{content:"\f219"}.fa-ship:before{content:"\f21a"}.fa-user-secret:before{content:"\f21b"}.fa-motorcycle:before{content:"\f21c"}.fa-street-view:before{content:"\f21d"}.fa-heartbeat:before{content:"\f21e"}.fa-venus:before{content:"\f221"}.fa-mars:before{content:"\f222"}.fa-mercury:before{content:"\f223"}.fa-transgender:before{content:"\f224"}.fa-transgender-alt:before{content:"\f225"}.fa-venus-double:before{content:"\f226"}.fa-mars-double:before{content:"\f227"}.fa-venus-mars:before{content:"\f228"}.fa-mars-stroke:before{content:"\f229"}.fa-mars-stroke-v:before{content:"\f22a"}.fa-mars-stroke-h:before{content:"\f22b"}.fa-neuter:before{content:"\f22c"}.fa-facebook-official:before{content:"\f230"}.fa-pinterest-p:before{content:"\f231"}.fa-whatsapp:before{content:"\f232"}.fa-server:before{content:"\f233"}.fa-user-plus:before{content:"\f234"}.fa-user-times:before{content:"\f235"}.fa-hotel:before,.fa-bed:before{content:"\f236"}.fa-viacoin:before{content:"\f237"}.fa-train:before{content:"\f238"}.fa-subway:before{content:"\f239"}.fa-medium:before{content:"\f23a"}
/**
 * Owl Carousel v2.3.4
 * Copyright 2013-2018 David Deutsch
 * Licensed under: SEE LICENSE IN https://github.com/OwlCarousel2/OwlCarousel2/blob/master/LICENSE
 */
/*
 *  Owl Carousel - Core
 */
.owl-carousel {
  display: none;
  width: 100%;
  -webkit-tap-highlight-color: transparent;
  /* position relative and z-index fix webkit rendering fonts issue */
  position: relative;
  z-index: 1; }
  .owl-carousel .owl-stage {
    position: relative;
    -ms-touch-action: pan-Y;
    touch-action: manipulation;
    -moz-backface-visibility: hidden;
    /* fix firefox animation glitch */ }
  .owl-carousel .owl-stage:after {
    content: ".";
    display: block;
    clear: both;
    visibility: hidden;
    line-height: 0;
    height: 0; }
  .owl-carousel .owl-stage-outer {
    position: relative;
    overflow: hidden;
    /* fix for flashing background */
    -webkit-transform: translate3d(0px, 0px, 0px); }
  .owl-carousel .owl-wrapper,
  .owl-carousel .owl-item {
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    -ms-backface-visibility: hidden;
    -webkit-transform: translate3d(0, 0, 0);
    -moz-transform: translate3d(0, 0, 0);
    -ms-transform: translate3d(0, 0, 0); }
  .owl-carousel .owl-item {
    position: relative;
    min-height: 1px;
    float: left;
    -webkit-backface-visibility: hidden;
    -webkit-tap-highlight-color: transparent;
    -webkit-touch-callout: none; }
  .owl-carousel .owl-item img {
    display: block;
    width: 100%; }
  .owl-carousel .owl-nav.disabled,
  .owl-carousel .owl-dots.disabled {
    display: none; }
  .owl-carousel .owl-nav .owl-prev,
  .owl-carousel .owl-nav .owl-next,
  .owl-carousel .owl-dot {
    cursor: pointer;
    -webkit-user-select: none;
    -khtml-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none; }
  .owl-carousel .owl-nav button.owl-prev,
  .owl-carousel .owl-nav button.owl-next,
  .owl-carousel button.owl-dot {
    background: none;
    color: inherit;
    border: none;
    padding: 0 !important;
    font: inherit; }
  .owl-carousel.owl-loaded {
    display: block; }
  .owl-carousel.owl-loading {
    opacity: 0;
    display: block; }
  .owl-carousel.owl-hidden {
    opacity: 0; }
  .owl-carousel.owl-refresh .owl-item {
    visibility: hidden; }
  .owl-carousel.owl-drag .owl-item {
    -ms-touch-action: pan-y;
        touch-action: pan-y;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none; }
  .owl-carousel.owl-grab {
    cursor: move;
    cursor: grab; }
  .owl-carousel.owl-rtl {
    direction: rtl; }
  .owl-carousel.owl-rtl .owl-item {
    float: right; }

/* No Js */
.no-js .owl-carousel {
  display: block; }

/*
 *  Owl Carousel - Animate Plugin
 */
.owl-carousel .animated {
  animation-duration: 1000ms;
  animation-fill-mode: both; }

.owl-carousel .owl-animated-in {
  z-index: 0; }

.owl-carousel .owl-animated-out {
  z-index: 1; }

.owl-carousel .fadeOut {
  animation-name: fadeOut; }

@keyframes fadeOut {
  0% {
    opacity: 1; }
  100% {
    opacity: 0; } }

/*
 * 	Owl Carousel - Auto Height Plugin
 */
.owl-height {
  transition: height 500ms ease-in-out; }

/*
 * 	Owl Carousel - Lazy Load Plugin
 */
.owl-carousel .owl-item {
  /**
			This is introduced due to a bug in IE11 where lazy loading combined with autoheight plugin causes a wrong
			calculation of the height of the owl-item that breaks page layouts
		 */ }
  .owl-carousel .owl-item .owl-lazy {
    opacity: 0;
    transition: opacity 400ms ease; }
  .owl-carousel .owl-item .owl-lazy[src^=""], .owl-carousel .owl-item .owl-lazy:not([src]) {
    max-height: 0; }
  .owl-carousel .owl-item img.owl-lazy {
    transform-style: preserve-3d; }

/*
 * 	Owl Carousel - Video Plugin
 */
.owl-carousel .owl-video-wrapper {
  position: relative;
  height: 100%;
  background: #000; }

.owl-carousel .owl-video-play-icon {
  position: absolute;
  height: 80px;
  width: 80px;
  left: 50%;
  top: 50%;
  margin-left: -40px;
  margin-top: -40px;
  background: url("owl.video.play.png") no-repeat;
  cursor: pointer;
  z-index: 1;
  -webkit-backface-visibility: hidden;
  transition: transform 100ms ease; }

.owl-carousel .owl-video-play-icon:hover {
  -ms-transform: scale(1.3, 1.3);
      transform: scale(1.3, 1.3); }

.owl-carousel .owl-video-playing .owl-video-tn,
.owl-carousel .owl-video-playing .owl-video-play-icon {
  display: none; }

.owl-carousel .owl-video-tn {
  opacity: 0;
  height: 100%;
  background-position: center center;
  background-repeat: no-repeat;
  background-size: contain;
  transition: opacity 400ms ease; }

.owl-carousel .owl-video-frame {
  position: relative;
  z-index: 1;
  height: 100%;
  width: 100%; }
/*

TemplateMo 568 DigiMedia

https://templatemo.com/tm-568-digimedia

*/

/* ---------------------------------------------
Table of contents
------------------------------------------------
01. font & reset css
02. reset
03. global styles
04. header
05. banner
06. features
07. testimonials
08. contact
09. footer
10. preloader
11. search
12. portfolio

--------------------------------------------- */
/* 
---------------------------------------------
font & reset css
--------------------------------------------- 
*/
/* 
---------------------------------------------
reset
--------------------------------------------- 
*/
html, body, div, span, applet, object, iframe, h1, h2, h3, h4, h5, h6, p, blockquote, div
pre, a, abbr, acronym, address, big, cite, code, del, dfn, em, font, img, ins, kbd, q,
s, samp, small, strike, strong, sub, sup, tt, var, b, u, i, center, dl, dt, dd, ol, ul, li,
figure, header, nav, section, article, aside, footer, figcaption {
  margin: 0;
  padding: 0;
  border: 0;
  outline: 0;
}

/* clear fix */
.grid:after {
  content: '';
  display: block;
  clear: both;
}

/* ---- .grid-item ---- */

.grid-sizer,
.grid-item {
  width: 50%;
}

.grid-item {
  float: left;
}

.grid-item img {
  display: block;
  max-width: 100%;
}

.clearfix:after {
  content: ".";
  display: block;
  clear: both;
  visibility: hidden;
  line-height: 0;
  height: 0;
}

.clearfix {
  display: inline-block;
}

html[xmlns] .clearfix {
  display: block;
}

* html .clearfix {
  height: 1%;
}

ul, li {
  padding: 0;
  margin: 0;
  list-style: none;
}

header, nav, section, article, aside, footer, hgroup {
  display: block;
}

* {
  box-sizing: border-box;
}

html, body {
  font-family: 'Poppins', sans-serif;
  font-weight: 400;
  background-color: #fff;
  -ms-text-size-adjust: 100%;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

a {
  text-decoration: none !important;
}

h1, h2, h3, h4, h5, h6 {
  margin-top: 0px;
  margin-bottom: 0px;
}

ul {
  margin-bottom: 0px;
}

p {
  font-size: 15px;
  line-height: 30px;
  font-weight: 300;
  color: #afafaf;
}

img {
  width: 100%;
  overflow: hidden;
}

/* 
---------------------------------------------
global styles
--------------------------------------------- 
*/
html,
body {
  background: #fff;
  font-family: 'Poppins', sans-serif;
}

::selection {
  background: #fa65b1;
  color: #fff !important;
}

::-moz-selection {
  background: #fa65b1;
  color: #fff !important;
}

@media (max-width: 991px) {
  html, body {
    overflow-x: hidden;
  }
  .mobile-top-fix {
    margin-top: 30px;
    margin-bottom: 0px;
  }
  .mobile-bottom-fix {
    margin-bottom: 30px;
  }
  .mobile-bottom-fix-big {
    margin-bottom: 60px;
  }
}

.page-section {
  margin-top: 120px;
}

.section-heading {
  position: relative;
  z-index: 2;
}

.section-heading h6 {
  font-size: 15px;
  font-weight: 700;
  color: #726ae3;
  text-transform: uppercase;
  margin-bottom: 15px;
}

.section-heading h4 {
  color: #2a2a2a;
  font-size: 35px;
  font-weight: 700;
  text-transform: capitalize;
  margin-bottom: 25px;
}

.section-heading h4 em {
  font-style: normal;
  color: #726ae3;
}

.section-heading .line-dec {
  width: 50px;
  height: 2px;
  background-color: #726ae3;
}

.border-first-button a {
  display: inline-block !important;
  padding: 10px 20px !important;
  color: #fa65b1 !important;
  border: 1px solid #fa65b1 !important;
  border-radius: 23px;
  font-weight: 500 !important;
  letter-spacing: 0.3px !important;
  transition: all .5s;
}

.border-first-button a:hover {
  background-color: #fa65b1;
  color: #fff !important;
}


/* 
---------------------------------------------
intro
--------------------------------------------- 
*/


.intro-banner {
  text-align: center;
  padding-top: 200px;margin-bottom: 100px;
  position: relative;
}

.intro-banner:after {
  content: '';
  background-image: url(../images/slider-left-dec.jpg);
  background-repeat: no-repeat;
  position: absolute;
  left: 0;
  top: 0px;
  width: 262px;
  height: 625px;
  z-index: 1;
}
/*
.intro-banner:before {
  content: '';
  background-image: url(../images/slider-right-dec.jpg);
  background-repeat: no-repeat;
  position: absolute;
  right: 0;
  top: 0px;
  width: 1159px;
  height: 797px;
  z-index: 2;
}
*/

.intro-banner img {
  max-width: 152px;
  margin-bottom: 30px;
}

.intro-banner h1 {
  font-size: 36px;
  font-weight: 600;
  text-transform: uppercase;
  margin-bottom: 30px;
  position: relative; 
  z-index: 2;
}

.intro-banner h4 {
  font-size: 20px;
  text-transform: capitalize;
  font-weight: 400;
  margin-bottom: 20px;
  position: relative; 
  z-index: 2;
}

.intro-banner a {
  display: inline-block !important;
  padding: 10px 20px !important;
  color: #fa65b1 !important;
  border: 1px solid #fa65b1 !important;
  border-radius: 23px;
  font-weight: 500 !important;
  letter-spacing: 0.3px !important;
  transition: all .5s;
  position: relative; 
  z-index: 2;
}

.intro-banner a:hover {
  background-color: #fa65b1;
  color: #fff !important;
}

.demos {
  padding-top: 60px;
}

.demo-item {
  position: relative;
  z-index: 2;
}

.demos img {
  transition: all .5s;
  border-radius: 23px;
}

.demos img:hover {
  opacity: 1;
  box-shadow: 0px 0px 15px rgba(0,0,0,0.25);
}

.demos h4 {
  text-align: center;
  font-size: 20px;
  margin-top: 30px;
  font-weight: 700;
  text-transform: uppercase;
}


/* 
---------------------------------------------
header
--------------------------------------------- 
*/

.pre-header {
  background-color: #efefef;
  height: 60px;
  padding: 15px 0px;
}

.pre-header ul li {
  display: inline-block;
}

.pre-header ul.info li {
  margin-right: 45px;
}

.pre-header ul.info li a {
  color: #afafaf;
  font-size: 14px;
  transition: all .3s;
}

.pre-header ul.info li a:hover {
  color: #fa65b1;
}

.pre-header ul.info li a i {
  font-size: 18px;
  margin-right: 8px;
}

.pre-header ul.social-media {
  text-align: right;
}

.pre-header ul.social-media li {
  margin-left: 5px;
}

.pre-header ul.social-media li a {
  background-color: #afafaf;
  color: #fff;
  display: inline-block;
  width: 30px;
  height: 30px;
  line-height: 30px;
  text-align: center;
  border-radius: 50%;
  font-size: 14px;
  transition: all .3s;
}

.pre-header ul.social-media li a:hover {
  background-color: #fa65b1;
}

.background-header {
  background-color: #fff!important;
  height: 80px!important;
  position: fixed!important;
  top: 0px;
  left: 0px;
  right: 0px;
  box-shadow: 0px 5px 8px rgba(0,0,0,0.03);
}

.background-header .logo,
.background-header .main-nav .nav li a {
  color: #fff;
}

.background-header .main-nav .nav li:hover a {
  color: #fa65b1;
}

.background-header .nav li a.active {
  position: relative;
  color: #fff;
}

.background-header .nav li a.active:after {
  position: absolute;
  width: 100%;
  height: 1px;
  background-color: #fa65b1;
  content: '';
  left: 50%;
  bottom: -20px;
  transform: translateX(-50%);
}

.background-header .nav li:last-child a.active:after {
  background-color: transparent;
}

.header-area {
  background-color: #fff;
  box-shadow: 0px 5px 8px rgba(0,0,0,0.03);
  position: absolute;
  left: 0px;
  right: 0px;
  z-index: 100;
  height: 100px;
  -webkit-transition: all .5s ease 0s;
  -moz-transition: all .5s ease 0s;
  -o-transition: all .5s ease 0s;
  transition: all .5s ease 0s;
}

.header-area .main-nav {
  min-height: 80px;
  background: transparent;
}

.header-area .main-nav .logo {
  float: left;
  -webkit-transition: all 0.3s ease 0s;
  -moz-transition: all 0.3s ease 0s;
  -o-transition: all 0.3s ease 0s;
  transition: all 0.3s ease 0s;
}

.header-area .main-nav .logo {
    line-height: 100px;
    float: left;
    -webkit-transition: all 0.3s ease 0s;
    -moz-transition: all 0.3s ease 0s;
    -o-transition: all 0.3s ease 0s;
    transition: all 0.3s ease 0s;
}

.background-header .main-nav .logo {
  line-height: 80px;
}

.background-header .main-nav .nav {
  margin-top: 20px !important;
}

.header-area .main-nav .nav {
  float: right;
  margin-top: 30px;
  margin-right: 0px;
  background-color: transparent;
  -webkit-transition: all 0.3s ease 0s;
  -moz-transition: all 0.3s ease 0s;
  -o-transition: all 0.3s ease 0s;
  transition: all 0.3s ease 0s;
  position: relative;
  z-index: 999;
}

.header-area .main-nav .nav li {
  padding-left: 20px;
  padding-right: 20px;
}

.header-area .main-nav .nav li:last-child {
  padding-right: 0px;
  padding-left: 40px;
}

.header-area .main-nav .nav li:last-child a ,
.background-header .main-nav .nav li:last-child a {
  padding: 0px 20px !important;
  font-weight: 400;
}

.header-area .main-nav .nav li:last-child a:hover ,
.background-header .main-nav .nav li:last-child a:hover {
  color: #fff !important;
}

.header-area .main-nav .nav li a {
  display: block;
  font-weight: 500;
  font-size: 15px;
  color: #2a2a2a;
  text-transform: capitalize;
  -webkit-transition: all 0.3s ease 0s;
  -moz-transition: all 0.3s ease 0s;
  -o-transition: all 0.3s ease 0s;
  transition: all 0.3s ease 0s;
  height: 40px;
  line-height: 40px;
  border: transparent;
  letter-spacing: 1px;
}

.header-area .main-nav .nav li:hover a,
.header-area .main-nav .nav li a.active {
  color: #fa65b1!important;
}

.background-header .main-nav .nav li:hover a,
.background-header .main-nav .nav li a.active {
  color: #fa65b1!important;
  opacity: 1;
}

.header-area .main-nav .nav li.submenu {
  position: relative;
  padding-right: 30px;
}

.header-area .main-nav .nav li.submenu:after {
  font-family: FontAwesome;
  content: "\f107";
  font-size: 12px;
  color: #2a2a2a;
  position: absolute;
  right: 18px;
  top: 12px;
}

.background-header .main-nav .nav li.submenu:after {
  color: #2a2a2a;
}

.header-area .main-nav .nav li.submenu ul {
  position: absolute;
  width: 200px;
  box-shadow: 0 2px 28px 0 rgba(0, 0, 0, 0.06);
  overflow: hidden;
  top: 50px;
  opacity: 0;
  transform: translateY(+2em);
  visibility: hidden;
  z-index: -1;
  transition: all 0.3s ease-in-out 0s, visibility 0s linear 0.3s, z-index 0s linear 0.01s;
}

.header-area .main-nav .nav li.submenu ul li {
  margin-left: 0px;
  padding-left: 0px;
  padding-right: 0px;
}

.header-area .main-nav .nav li.submenu ul li a {
  opacity: 1;
  display: block;
  background: #f7f7f7;
  color: #2a2a2a!important;
  padding-left: 20px;
  height: 40px;
  line-height: 40px;
  -webkit-transition: all 0.3s ease 0s;
  -moz-transition: all 0.3s ease 0s;
  -o-transition: all 0.3s ease 0s;
  transition: all 0.3s ease 0s;
  position: relative;
  font-size: 13px;
  font-weight: 400;
  border-bottom: 1px solid #eee;
}

.header-area .main-nav .nav li.submenu ul li a:hover {
  background: #fff;
  color: #fa65b1!important;
  padding-left: 25px;
}

.header-area .main-nav .nav li.submenu ul li a:hover:before {
  width: 3px;
}

.header-area .main-nav .nav li.submenu:hover ul {
  visibility: visible;
  opacity: 1;
  z-index: 1;
  transform: translateY(0%);
  transition-delay: 0s, 0s, 0.3s;
}

.header-area .main-nav .menu-trigger {
  cursor: pointer;
  display: block;
  position: absolute;
  top: 33px;
  width: 32px;
  height: 40px;
  text-indent: -9999em;
  z-index: 99;
  right: 40px;
  display: none;
}

.background-header .main-nav .menu-trigger {
  top: 23px;
}

.header-area .main-nav .menu-trigger span,
.header-area .main-nav .menu-trigger span:before,
.header-area .main-nav .menu-trigger span:after {
  -moz-transition: all 0.4s;
  -o-transition: all 0.4s;
  -webkit-transition: all 0.4s;
  transition: all 0.4s;
  background-color: #2a2a2a;
  display: block;
  position: absolute;
  width: 30px;
  height: 2px;
  left: 0;
}

.background-header .main-nav .menu-trigger span,
.background-header .main-nav .menu-trigger span:before,
.background-header .main-nav .menu-trigger span:after {
  background-color: #2a2a2a;
}

.header-area .main-nav .menu-trigger span:before,
.header-area .main-nav .menu-trigger span:after {
  -moz-transition: all 0.4s;
  -o-transition: all 0.4s;
  -webkit-transition: all 0.4s;
  transition: all 0.4s;
  background-color: #2a2a2a;
  display: block;
  position: absolute;
  width: 30px;
  height: 2px;
  left: 0;
  width: 75%;
}

.background-header .main-nav .menu-trigger span:before,
.background-header .main-nav .menu-trigger span:after {
  background-color: #2a2a2a;
}

.header-area .main-nav .menu-trigger span:before,
.header-area .main-nav .menu-trigger span:after {
  content: "";
}

.header-area .main-nav .menu-trigger span {
  top: 16px;
}

.header-area .main-nav .menu-trigger span:before {
  -moz-transform-origin: 33% 100%;
  -ms-transform-origin: 33% 100%;
  -webkit-transform-origin: 33% 100%;
  transform-origin: 33% 100%;
  top: -10px;
  z-index: 10;
}

.header-area .main-nav .menu-trigger span:after {
  -moz-transform-origin: 33% 0;
  -ms-transform-origin: 33% 0;
  -webkit-transform-origin: 33% 0;
  transform-origin: 33% 0;
  top: 10px;
}

.header-area .main-nav .menu-trigger.active span,
.header-area .main-nav .menu-trigger.active span:before,
.header-area .main-nav .menu-trigger.active span:after {
  background-color: transparent;
  width: 100%;
}

.header-area .main-nav .menu-trigger.active span:before {
  -moz-transform: translateY(6px) translateX(1px) rotate(45deg);
  -ms-transform: translateY(6px) translateX(1px) rotate(45deg);
  -webkit-transform: translateY(6px) translateX(1px) rotate(45deg);
  transform: translateY(6px) translateX(1px) rotate(45deg);
  background-color: #2a2a2a;
}

.background-header .main-nav .menu-trigger.active span:before {
  background-color: #2a2a2a;
}

.header-area .main-nav .menu-trigger.active span:after {
  -moz-transform: translateY(-6px) translateX(1px) rotate(-45deg);
  -ms-transform: translateY(-6px) translateX(1px) rotate(-45deg);
  -webkit-transform: translateY(-6px) translateX(1px) rotate(-45deg);
  transform: translateY(-6px) translateX(1px) rotate(-45deg);
  background-color: #2a2a2a;
}

.background-header .main-nav .menu-trigger.active span:after {
  background-color: #2a2a2a;
}

.header-area.header-sticky {
  min-height: 80px;
}

.header-area .nav {
  margin-top: 30px;
}

.header-area.header-sticky .nav li a.active {
  color: #fa65b1;
}

@media (max-width: 1200px) {
  .header-area .main-nav .nav li {
    padding-left: 12px;
    padding-right: 12px;
  }
  .header-area .main-nav:before {
    display: none;
  }
}

@media (max-width: 992px) {
  .header-area .main-nav .nav li:last-child  ,
  .background-header .main-nav .nav li:last-child {
    display: none;
  }
  .header-area .main-nav .nav li:nth-child(6),
  .background-header .main-nav .nav li:nth-child(6) {
    padding-right: 0px;
  }
  .background-header .nav li a.active:after {
    display: none;
  }
}

@media (max-width: 767px) {
  .pre-header ul.info li:last-child {
    display: none;
  }
  .background-header .main-nav .nav {
    margin-top: 80px !important;
  }
  .header-area .main-nav .logo {
    color: #1e1e1e;
  }
  .header-area.header-sticky .nav li a:hover,
  .header-area.header-sticky .nav li a.active {
    color: #fa65b1!important;
    opacity: 1;
  }
  .header-area.header-sticky .nav li.search-icon a {
    width: 100%;
  }
  .header-area {
    background-color: #fff;
    padding: 0px 15px;
    height: 100px;
    box-shadow: none;
    text-align: center;
    box-shadow: 0px 5px 8px rgba(0,0,0,0.03);
  }
  .header-area .container {
    padding: 0px;
  }
  .header-area .logo {
    margin-left: 30px;
  }
  .header-area .menu-trigger {
    display: block !important;
  }
  .header-area .main-nav {
    overflow: hidden;
  }
  .header-area .main-nav .nav {
    float: none;
    width: 100%;
    display: none;
    -webkit-transition: all 0s ease 0s;
    -moz-transition: all 0s ease 0s;
    -o-transition: all 0s ease 0s;
    transition: all 0s ease 0s;
    margin-left: 0px;
  }
  .background-header .nav {
    margin-top: 80px;
  }
  .header-area .main-nav .nav li:first-child {
    border-top: 1px solid #eee;
  }
  .header-area.header-sticky .nav {
    margin-top: 100px;
  }
  .header-area .main-nav .nav li {
    width: 100%;
    background: #fff;
    border-bottom: 1px solid #e7e7e7;
    padding-left: 0px !important;
    padding-right: 0px !important;
  }
  .header-area .main-nav .nav li a {
    height: 50px !important;
    line-height: 50px !important;
    padding: 0px !important;
    border: none !important;
    background: #f7f7f7 !important;
    color: #191a20 !important;
  }
  .header-area .main-nav .nav li a:hover {
    background: #eee !important;
    color: #fa65b1!important;
  }
  .header-area .main-nav .nav li.submenu ul {
    position: relative;
    visibility: inherit;
    opacity: 1;
    z-index: 1;
    transform: translateY(0%);
    transition-delay: 0s, 0s, 0.3s;
    top: 0px;
    width: 100%;
    box-shadow: none;
    height: 0px;
  }
  .header-area .main-nav .nav li.submenu ul li a {
    font-size: 12px;
    font-weight: 400;
  }
  .header-area .main-nav .nav li.submenu ul li a:hover:before {
    width: 0px;
  }
  .header-area .main-nav .nav li.submenu ul.active {
    height: auto !important;
  }
  .header-area .main-nav .nav li.submenu:after {
    color: #3B566E;
    right: 25px;
    font-size: 14px;
    top: 15px;
  }
  .header-area .main-nav .nav li.submenu:hover ul, .header-area .main-nav .nav li.submenu:focus ul {
    height: 0px;
  }
}

@media (min-width: 767px) {
  .header-area .main-nav .nav {
    display: flex !important;
  }
}

/* 
---------------------------------------------
preloader
--------------------------------------------- 
*/

.js-preloader {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-color: #fff;
    display: -webkit-box;
    display: flex;
    -webkit-box-align: center;
    align-items: center;
    -webkit-box-pack: center;
    justify-content: center;
    opacity: 1;
    visibility: visible;
    z-index: 9999;
    -webkit-transition: opacity 0.25s ease;
    transition: opacity 0.25s ease;
}

.js-preloader.loaded {
    opacity: 0;
    visibility: hidden;
    pointer-events: none;
}

@-webkit-keyframes dot {
    50% {
        -webkit-transform: translateX(96px);
        transform: translateX(96px);
    }
}

@keyframes dot {
    50% {
        -webkit-transform: translateX(96px);
        transform: translateX(96px);
    }
}

@-webkit-keyframes dots {
    50% {
        -webkit-transform: translateX(-31px);
        transform: translateX(-31px);
    }
}

@keyframes dots {
    50% {
        -webkit-transform: translateX(-31px);
        transform: translateX(-31px);
    }
}

.preloader-inner {
    position: relative;
    width: 142px;
    height: 40px;
    background: #fff;
}

.preloader-inner .dot {
    position: absolute;
    width: 16px;
    height: 16px;
    top: 12px;
    left: 15px;
    background: #fa65b1;
    border-radius: 50%;
    -webkit-transform: translateX(0);
    transform: translateX(0);
    -webkit-animation: dot 2.8s infinite;
    animation: dot 2.8s infinite;
}

.preloader-inner .dots {
    -webkit-transform: translateX(0);
    transform: translateX(0);
    margin-top: 12px;
    margin-left: 31px;
    -webkit-animation: dots 2.8s infinite;
    animation: dots 2.8s infinite;
}

.preloader-inner .dots span {
    display: block;
    float: left;
    width: 16px;
    height: 16px;
    margin-left: 16px;
    background: #fa65b1;
    border-radius: 50%;
}



/* 
---------------------------------------------
Banner Style
--------------------------------------------- 
*/

.main-banner {
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  padding: 226px 0px 120px 0px;
  position: relative;
  overflow: hidden;
}

.main-banner:after {
  content: '';
  background-image: url(../images/slider-left-dec.jpg);
  background-repeat: no-repeat;
  position: absolute;
  left: 0;
  top: 60px;
  width: 262px;
  height: 625px;
  z-index: 1;
}

.main-banner:before {
  content: '';
  background-image: url(../images/slider-right-dec.jpg);
  background-repeat: no-repeat;
  position: absolute;
  right: 0;
  top: 60px;
  width: 1159px;
  height: 797px;
  z-index: -1;
}

.main-banner .left-content {
  margin-right: 15px;
}

.main-banner .left-content h6 {
  text-transform: capitalize;
  font-size: 20px;
  font-weight: 700;
  color: #fa65b1;
  margin-bottom: 15px;
  text-transform: uppercase;
}

.main-banner .left-content h2 {
  z-index: 2;
  position: relative;
  font-weight: 700;
  font-size: 50px;
  color: #2a2a2a;
  margin-bottom: 20px;
}

.main-banner .left-content p {
  margin-bottom: 30px;
  margin-right: 45px;
}

.main-banner .right-image {
  text-align: right;
  position: relative;
  z-index: 20;
}

.main-banner .right-image img {
  max-width: 593px;
}



/* 
---------------------------------------------
About Style
--------------------------------------------- 
*/

#about {
  padding-top: 130px;
}

.about-left-image img {
  margin-right: 45px;
}

.about-right-content p {
  margin-top: 30px;
  margin-bottom: 45px;
}

.skills-content {
  position: relative;
  z-index: 1;
  margin-top: -50px;
  background-color: #f5f5f5;
  border-bottom-right-radius: 50px;
  border-bottom-left-radius: 50px;
  padding: 110px 0px 50px 0px;
}

.skill-item {
  text-align: center;
}

.progress {
  width: 150px;
  height: 150px;
  line-height: 150px;
  background: none;
  margin: 0 auto;
  box-shadow: none;
  position: relative;
}
.progress:after {
  content: "";
  width: 100%;
  height: 100%;
  border-radius: 50%;
  border: 5px solid #fff;
  position: absolute;
  top: 0;
  left: 0;
}
.progress > span {
  width: 50%;
  height: 100%;
  overflow: hidden;
  position: absolute;
  top: 0;
  z-index: 1;
}
.progress .progress-left {
  left: 0;
}
.progress .progress-bar {
  width: 100%;
  height: 100%;
  background: none;
  border-width: 5px;
  border-style: solid;
  position: absolute;
  top: 0;
  border-color: #fd6a54;
}

.first-skill-item .progress .progress-bar {
  border-color: #fa65b1;
}

.second-skill-item .progress .progress-bar {
  border-color: #726ae3;
}

.third-skill-item .progress .progress-bar {
  border-color: #f58b56;
}

.progress .progress-left .progress-bar {
  left: 100%;
  border-top-right-radius: 75px;
  border-bottom-right-radius: 75px;
  border-left: 0;
  -webkit-transform-origin: center left;
  transform-origin: center left;
}
.progress .progress-right {
  right: 0;
}
.progress .progress-right .progress-bar {
  left: -100%;
  border-top-left-radius: 75px;
  border-bottom-left-radius: 75px;
  border-right: 0;
  -webkit-transform-origin: center right;
  transform-origin: center right;
}
.progress .progress-value {
  text-align: center;
  color: #2a2a2a;
  display: flex;
  width: 100%;
  border-radius: 50%;
  font-size: 35px;
  text-align: center;
  line-height: 25px;
  align-items: center;
  justify-content: center;
  height: 100%;
  font-weight: 700;
}
.progress .progress-value div {
  margin-top: 10px;
}
.progress .progress-value span {
  font-size: 18px;
  text-transform: none;
  color: #afafaf;
  font-weight: 300;
}

/* This for loop creates the  necessary css animation names 
Due to the split circle of progress-left and progress right, we must use the animations on each side. 
*/
.progress[data-percentage="10"] .progress-right .progress-bar {
  animation: loading-1 1.5s linear forwards;
}
.progress[data-percentage="10"] .progress-left .progress-bar {
  animation: 0;
}

.progress[data-percentage="20"] .progress-right .progress-bar {
  animation: loading-2 1.5s linear forwards;
}
.progress[data-percentage="20"] .progress-left .progress-bar {
  animation: 0;
}

.progress[data-percentage="30"] .progress-right .progress-bar {
  animation: loading-3 1.5s linear forwards;
}
.progress[data-percentage="30"] .progress-left .progress-bar {
  animation: 0;
}

.progress[data-percentage="40"] .progress-right .progress-bar {
  animation: loading-4 1.5s linear forwards;
}
.progress[data-percentage="40"] .progress-left .progress-bar {
  animation: 0;
}

.progress[data-percentage="50"] .progress-right .progress-bar {
  animation: loading-5 1.5s linear forwards;
}
.progress[data-percentage="50"] .progress-left .progress-bar {
  animation: 0;
}

.progress[data-percentage="60"] .progress-right .progress-bar {
  animation: loading-5 1.5s linear forwards;
}
.progress[data-percentage="60"] .progress-left .progress-bar {
  animation: loading-1 1.5s linear forwards 1.5s;
}

.progress[data-percentage="70"] .progress-right .progress-bar {
  animation: loading-5 1.5s linear forwards;
}
.progress[data-percentage="70"] .progress-left .progress-bar {
  animation: loading-2 1.5s linear forwards 1.5s;
}

.progress[data-percentage="80"] .progress-right .progress-bar {
  animation: loading-5 1.5s linear forwards;
}
.progress[data-percentage="80"] .progress-left .progress-bar {
  animation: loading-3 1.5s linear forwards 1.5s;
}

.progress[data-percentage="90"] .progress-right .progress-bar {
  animation: loading-5 1.5s linear forwards;
}
.progress[data-percentage="90"] .progress-left .progress-bar {
  animation: loading-4 1.5s linear forwards 1.5s;
}

.progress[data-percentage="100"] .progress-right .progress-bar {
  animation: loading-5 1.5s linear forwards;
}
.progress[data-percentage="100"] .progress-left .progress-bar {
  animation: loading-5 1.5s linear forwards 1.5s;
}

@keyframes loading-1 {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(36);
    transform: rotate(36deg);
  }
}
@keyframes loading-2 {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(72);
    transform: rotate(72deg);
  }
}
@keyframes loading-3 {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(108);
    transform: rotate(108deg);
  }
}
@keyframes loading-4 {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(144);
    transform: rotate(144deg);
  }
}
@keyframes loading-5 {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(180);
    transform: rotate(180deg);
  }
}
.progress {
  margin-bottom: 1em;
}

/* 
---------------------------------------------
Services Style
--------------------------------------------- 
*/

.services {
  padding-top: 130px;
  position: relative;
}

.services:after {
  content: '';
  background-image: url(../images/services-left-dec.jpg);
  background-repeat: no-repeat;
  position: absolute;
  left: 0;
  top: 0px;
  width: 786px;
  height: 1217px;
  z-index: 0;
}

.services:before {
  content: '';
  background-image: url(../images/services-right-dec.jpg);
  background-repeat: no-repeat;
  position: absolute;
  right: 0;
  top: 400px;
  width: 161px;
  height: 413px;
  z-index: 0;
}

.services .section-heading {
  text-align: center;
  margin-bottom: 80px;
}

.services .section-heading .line-dec {
  margin: 0 auto;
}

.services .naccs {
  position: relative;
  z-index: 1;
}

.services .icon {
  display: block;
  text-align: center;
  margin: 0 auto;
}

.services .naccs .menu div h4 {
  color: #fff;
  font-size: 15px;
  font-weight: 400;
  width: 100%;
}

.services .icon img {
  margin-bottom: 10px;
  max-width: 60px;
  min-width: 60px;
}

.services .naccs .menu {
  text-align: center;
  margin-bottom: 30px;
}

.services .naccs .menu div {
  color: #2a2a2a;
  margin: 0px;
  width: 15%;
  font-size: 20px;
  font-weight: 700;
  display: inline-block;
  text-align: center;
  cursor: pointer;
  position: relative;
  border-radius: 15px;
  transition: 1s all cubic-bezier(0.075, 0.82, 0.165, 1);
}

.services .naccs .menu div .thumb {
  display: inline-block;
  width: 100%;
  padding: 30px 0px;
  background-color: #fff;
}

.services .naccs .menu div.active {
  box-shadow: 0px 0px 15px rgba(0,0,0,0.1);
}

.services ul.nacc {
  height: 100% !important;
  position: relative;
  min-height: 100%;
  list-style: none;
  margin: 0;
  padding: 0;
  transition: 0.5s all cubic-bezier(0.075, 0.82, 0.165, 1);
}

.services ul.nacc li {
  opacity: 0;
  transform: translateX(-50px);
  position: absolute;
  list-style: none;
  transition: 1s all cubic-bezier(0.075, 0.82, 0.165, 1);
}

.services ul.nacc li.active {
  transition-delay: 0.3s;
  position: relative;
  z-index: 2;
  opacity: 1;
  transform: translateX(0px);
  box-shadow: 0px 0px 15px rgba(0,0,0,0.1);
  background-color: #fff;
  border-radius: 15px;
  padding: 80px 120px 50px 120px;
}

.services ul.nacc li {
  width: 100%;
}

.services ul.nacc li .right-image img {
  max-width: 420px;
  float: right;
}

.services .nacc .thumb h4 {
  color: #2a2a2a;
  font-size: 20px;
  font-weight: 700;
  line-height: 35px;
  margin-bottom: 25px;
}

.services .nacc .thumb .main-white-button {
  text-align: right;
  margin-top: 40px;
}

.services .nacc .thumb .main-white-button a {
  background-color: #8d99af;
  color: #fff;
}

.services .nacc .thumb .main-white-button a i {
  background-color: #fff;
  color: #8d99af;
}

.services .left-text h4 {
  font-size: 20px;
  font-weight: 700;
  color: #fa65b1 !important;
}

.services .left-text p {
  margin-bottom: 30px;
}

.nacc .ticks-list span {
  display: inline-block;
  opacity: 1;
  margin-right: 45px;
  margin-bottom: 20px;
  font-size: 15px;
  font-weight: 400;
}



/* 
---------------------------------------------
Free Quote
--------------------------------------------- 
*/

.free-quote {
  background-image: url(../images/quote-bg.jpg);
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  padding: 120px 0px;
  text-align: center;
  position: relative;
  z-index: 2;
  margin-top: 130px;
}

.free-quote .section-heading {
  margin-bottom: 60px;
}

.free-quote .section-heading h6,
.free-quote .section-heading h4 {
  color: #fff;
}

.free-quote .section-heading .line-dec {
  margin: 0 auto;
  background-color: #fff;
}

.free-quote form {
  background-color: #fff;
  display: inline-block;
  width: 100%;
  min-height: 80px;
  border-radius: 40px;
  position: relative;
  z-index: 1;
}

.free-quote form input {
  width: 100%;
  margin-top: 20px;
  margin-left: 30px;
  color: #afafaf;
  font-weight: 400;
  font-size: 15px;
  height: 40px;
  background-color: transparent;
  border-bottom: 1px solid #eee;
  border-top: none;
  border-left: none;
  border-right: none;
  position: relative;
  z-index: 2;
  outline: none;
}

.free-quote form button {
  width: 100%;
  height: 80px;
  border-top-right-radius: 40px;
  border-bottom-right-radius: 40px;
  outline: none;
  border: none;
  margin-left: 30px;
  background-color: #726ae3;
  font-size: 15px;
  color: #fff;
}


/* 
---------------------------------------------
Portfolio
--------------------------------------------- 
*/

.our-portfolio {
  padding-top: 130px;
  overflow: hidden;
  position: relative;
}

.our-portfolio:before {
  content: '';
  background-image: url(../images/portfolio-right-dec.jpg);
  background-repeat: no-repeat;
  position: absolute;
  right: 0;
  top: 0px;
  width: 414px;
  height: 861px;
  z-index: 1;
}

.our-portfolio:after {
  content: '';
  background-image: url(../images/portfolio-left-dec.jpg);
  background-repeat: no-repeat;
  position: absolute;
  left: 0;
  top: 0px;
  width: 677px;
  height: 759px;
  z-index: 1;
}

.our-portfolio .section-heading {
  margin-bottom: 80px;
}

.our-portfolio .container-fluid {
  padding-right: 15px;
  padding-left: 15px;
  position: relative;
  z-index: 2;
}

.our-portfolio .item {
  position: relative;
  z-index: 222;
}

.portfolio-item {
  border-radius: 25px;
  box-shadow: 0px 0px 15px rgba(0,0,0,0.1);
  margin: 15px;
}

.portfolio-item .thumb {
  position: relative;
  border-radius: 50px;
}

.portfolio-item:hover .down-content h4,
.portfolio-item:hover .down-content span {
  color: #fa65b1;
}

.portfolio-item .thumb img {
  border-top-right-radius: 23px;
  border-top-left-radius: 23px;
  overflow: hidden;
}

.portfolio-item .down-content {
  background-color: #fff;
  text-align: center;
  padding: 18px 0px;
  border-bottom-right-radius: 23px;
  border-bottom-left-radius: 23px;
}

.portfolio-item .down-content h4 {
  font-size: 20px;
  font-weight: 700;
  color: #2a2a2a;
  margin-bottom: 8px;
  transition: all .3s;
}

.portfolio-item .down-content span {
  font-size: 15px;
  color: #afafaf;
  transition: all .3s;
}

.our-portfolio .owl-nav {
  display: inline-block!important;
  position: absolute;
  top: -125px;
  right: 15%;
  max-width: 1320px;
}

.our-portfolio .owl-nav .owl-next {
  margin-left: 10px;
}

.our-portfolio .owl-nav span {
  width: 46px;
  height: 46px;
  display: inline-block;
  text-align: center;
  line-height: 46px;
  font-size: 30px;
  background-color: #eee;
  border-radius: 50%;
  color: #fff;
  transition: all 0.5s;
}

.our-portfolio .owl-nav span:hover {
  color: #fff;
  background-color: #fa65b1;
}


/* 
---------------------------------------------
Blog
--------------------------------------------- 
*/

.blog:before {
  content: '';
  background-image: url(../images/blog-left-dec.jpg);
  background-repeat: no-repeat;
  position: absolute;
  left: 0;
  top: 0px;
  width: 961px;
  height: 1020px;
  z-index: 0;
}

.blog {
  position: relative;
  padding-top: 130px;
}

.blog .section-heading {
  text-align: center;
  margin-bottom: 80px;
}

.blog .section-heading .line-dec {
  margin: 0 auto;
}

.show-up {
  position: relative;
  z-index: 200;
}

.blog-post {
  box-shadow: 0px 0px 15px rgba(0,0,0,0.1);
  border-radius: 25px;
}

.blog-post .thumb img {
  border-top-right-radius: 23px;
  border-top-left-radius: 23px;
}

.blog-post .down-content {
  border-bottom-right-radius: 23px;
  border-bottom-left-radius: 23px;
  background-color: #fff;
  padding: 30px;
}

.blog-post .down-content span.category {
  font-size: 15px;
  color: #fff;
  padding: 8px 12px;
  background-color: #726ae3;
  border-radius: 18px;
  display: inline-block;
}

.blog-post .down-content span.date {
  font-size: 15px;
  color: #afafaf;
  text-align: right;
  float: right;
  margin-top: 4px;
}

.blog-post .down-content h4 {
  font-size: 20px;
  font-weight: 700;
  color: #2a2a2a;
  margin-top: 20px;
  margin-bottom: 20px;
  line-height: 30px;
}

.blog-post .down-content p {
  margin-bottom: 30px;
}

.blog-post .down-content span.author {
  font-size: 15px;
  color: #2a2a2a;
}

.blog-post .down-content span.author img {
  max-width: 56px;
  border-radius: 50%;
  margin-right: 15px;
}

.blog-post .down-content .border-first-button {
  display: inline-block;
  float: right;
}

.blog-posts {
  margin-left: 30px;
}

.post-item {
  margin-bottom: 62px;
}

.last-post-item {
  margin-bottom: 0px;
}

.post-item .thumb {
  display: inline-block;
  float: left;
  margin-right: 30px;
}

.post-item .thumb img {
  border-radius: 23px;
  display: inline-block;
}

.post-item .right-content {
  padding-top: 20px;
}

.post-item .right-content span.category {
  font-size: 15px;
  color: #fff;
  padding: 8px 12px;
  background-color: #726ae3;
  border-radius: 18px;
  display: inline-block;
}

.post-item .right-content span.date {
  font-size: 15px;
  color: #afafaf;
  text-align: right;
  float: right;
  margin-top: 4px;
}

.post-item .right-content h4 {
  font-size: 20px;
  font-weight: 700;
  color: #2a2a2a;
  margin-top: 20px;
  margin-bottom: 20px;
  line-height: 30px;
}


/* 
---------------------------------------------
contact
--------------------------------------------- 
*/

.contact-us {
  padding-top: 130px;
}

.contact-us .section-heading .line-dec {
  margin: 0 auto;
}

.contact-us .section-heading {
  text-align: center;
  margin-bottom: 80px;
}


form#contact:before {
  background-image: url(../images/contact-top-right.png);
  position: absolute;
  right: 0;
  top: 0;
  width: 726px;
  height: 78px;
  background-repeat: no-repeat;
  content: '';
  z-index: 1;
}

.contact-dec img {
  max-width: 224px;
  position: absolute;
  right: 25px;
  top: -242px;
}

form#contact:after {
  background-image: url(../images/contact-bottom-right.png);
  position: absolute;
  right: 0;
  bottom: 0;
  width: 532px;
  height: 106px;
  background-repeat: no-repeat;
  content: '';
  z-index: 1;
}

form#contact {
  box-shadow: 0px 0px 15px rgba(0,0,0,0.1);
  position: relative;
  background-color: #fff;
  border-radius: 23px;
  text-align: center;
}

form#contact #map iframe {
  border-top-left-radius: 23px;
  border-bottom-left-radius: 23px;
  margin-bottom: -7px;
  position: relative;
  z-index: 2;
}

.fill-form {
  padding: 80px 60px 80px 30px;
}

.fill-form .info-post {
  margin-bottom: 20px;
}

.fill-form .icon {
  text-align: center;
  box-shadow: 0px 0px 15px rgba(0,0,0,0.1);
  border-radius: 23px;
  padding: 25px 15px;
}

.fill-form .icon img {
  max-width: 60px;
  display: block;
  margin: 0 auto;
}

.fill-form .icon a {
  margin-top: 15px;
  display: inline-block;
  font-size: 15px;
  font-weight: 500;
  color: #2a2a2a;
  transition: all .3s;
}

.fill-form .icon:hover a {
  color: #fa65b1;
}

form#contact input {
  width: 100%;
  height: 46px;
  background-color: transparent;
  border: 1px solid #eee;
  outline: none;
  font-size: 15px;
  font-weight: 300;
  color: #2a2a2a;
  padding: 0px 20px;
  border-radius: 23px;
  margin-top: 30px;
}

form#contact input::placeholder {
  color: #aaa;
}

form#contact textarea {
  width: 100%;
  min-width: 100%;
  max-width: 100%;
  max-height: 200px;
  min-height: 200px;
  height: 200px;
  border-radius: 23px;
  background-color: transparent;
  border: 1px solid #eee;
  outline: none;
  font-size: 15px;
  font-weight: 300;
  color: #2a2a2a;
  padding: 15px 20px;
  margin-top: 30px;
}

form#contact textarea::placeholder {
  color: #aaa;
}

form#contact button {
  display: inline-block;
  background-color: #fff;
  font-size: 15px;
  font-weight: 400;
  color: #fa65b1;
  margin-top: 30px;
  width: 100%;
  text-transform: capitalize;
  padding: 12px 25px;
  border-radius: 23px;
  letter-spacing: 0.25px;
  border: 1px solid #fa65b1;
  transition: all .3s;
  outline: none;
}

form#contact button:hover {
  background-color: #fa65b1!important;
  color: #fff!important;
}

/* 
---------------------------------------------
Footer Style
--------------------------------------------- 
*/

footer {
  background-image: url(../images/footer-bg.jpg);
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
  margin-top: 130px;
}

footer p {
  text-align: center;
  margin: 20px 0px;
  color: #fff;
}

footer p a {
  color: #fff;
  transition: all .5s;
}

/* 
---------------------------------------------
responsive
--------------------------------------------- 
*/

@media (max-width: 1200px) {
  .header-area .main-nav .logo h4 {
    font-size: 24px;
  }
  .header-area .main-nav .logo h4 img {
    max-width: 25px;
    margin-left: 0px;
  }
  .header-area .main-nav .nav li:last-child {
    padding-left: 20px;
  }
}

@media (max-width: 992px) {
  .intro-banner:before {
    display: none;
  } 
  form#contact {
    overflow: hidden;
  }
  .header-area .main-nav .logo h4 {
    font-size: 20px;
  }
  .main-banner .left-content {
    margin-right: 0px;
  }
  .main-banner {
    text-align: center;
    padding: 226px 0px 30px 0px;
  }
  .main-banner:before {
    display: none;
  }
  .main-banner .right-image {
    margin: 30px auto 0px auto;
    text-align: center;
  }
  .features-item {
    margin-bottom: 45px;
  }
  .last-features-item,
  .last-skill-item {
    margin-bottom: 0px !important;
  }
  .skill-item {
    margin-bottom: 30px;
  }
  .about-left-image img {
    margin-right: 0px;
    margin-bottom: 45px;;
  }
  .services .naccs .menu div {
    font-size: 15px;
    font-weight: 500;
  }
  .service-item {
    text-align: center;
  }
  .service-item .icon {
    margin-top: 0px;
    margin-bottom: 30px;
  }
  .about-us .left-image {
    margin-right: 30px;
    margin-left: 30px;
    margin-bottom: 45px;
  }
  .blog-posts {
    margin-left: 0px;
    margin-top: 30px;
  }
  .post-item {
    margin-bottom: 70px;
  }
  .our-portfolio .owl-nav {
    display: none !important;
  }
  .contact-info {
    margin-top: 60px;
  }
  form#contact {
    padding: 45px;
  }
}

@media (max-width: 767px) {
  .header-area .main-nav .logo h4 {
    font-size: 30px;
  }
  .header-area .main-nav .logo h4 img {
    max-width: 30px;
    margin-left: 5px;
  }
  .main-banner .info-stat {
    margin-bottom: 15px;
  }
  .service-item {
    text-align: center;
    padding: 30px;
  }
  .service-item .icon {
    float: none;
    margin-right: 0px;
    margin-bottom: 15px;
  }
  .service-item .right-content {
    display: inline-block;
  }
  .services .naccs .menu div .thumb {
    padding: 5px;
  }
  .services .icon img {
    margin: 0px;
  }
  .services ul.nacc li.active {
    padding: 45px;
  }
  .services .naccs .menu div  {
    font-size: 0px;
  }
  .services ul.nacc li .right-image img {
    float: none;
  }
  .our-portfolio .section-heading,
  .about-us .section-heading,
  .about-us .about-item,
  .about-us p,
  .about-us .main-green-button {
    text-align: center;
  }
  .our-portfolio .section-heading .line-dec {
    margin: 0 auto;
  }
  .our-services .section-heading {
    margin-left: 15px;
    margin-right: 15px;
  }
  .free-quote form input {
    margin-left: 0px;
    padding: 0px 30px;
  }
  .free-quote form button {
    margin-left: 0px;
    border-bottom-left-radius: 40px;
    border-top-right-radius: 0px;
  }
  .blog-posts {
    margin-left: 0px;
    margin-top: 30px;
  }
  .post-item {
    margin-bottom: 30px;
  }
  .post-item .thumb img {
    max-width: 140px;
  }
  .post-item .right-content p {
    display: none;
  }
  .about-us .about-item {
    margin-top: 15px;
  }
  form#contact {
    padding: 30px;
  }
}
/*

TemplateMo 568 DigiMedia

https://templatemo.com/tm-568-digimedia

*/

/* ---------------------------------------------
Table of contents
------------------------------------------------
01. font & reset css
02. reset
03. global styles
04. header
05. banner
06. features
07. testimonials
08. contact
09. footer
10. preloader
11. search
12. portfolio

--------------------------------------------- */
/* 
---------------------------------------------
font & reset css
--------------------------------------------- 
*/
/* 
---------------------------------------------
reset
--------------------------------------------- 
*/
html, body, div, span, applet, object, iframe, h1, h2, h3, h4, h5, h6, p, blockquote, div
pre, a, abbr, acronym, address, big, cite, code, del, dfn, em, font, img, ins, kbd, q,
s, samp, small, strike, strong, sub, sup, tt, var, b, u, i, center, dl, dt, dd, ol, ul, li,
figure, header, nav, section, article, aside, footer, figcaption {
  margin: 0;
  padding: 0;
  border: 0;
  outline: 0;
}

/* clear fix */
.grid:after {
  content: '';
  display: block;
  clear: both;
}

/* ---- .grid-item ---- */

.grid-sizer,
.grid-item {
  width: 50%;
}

.grid-item {
  float: left;
}

.grid-item img {
  display: block;
  max-width: 100%;
}

.clearfix:after {
  content: ".";
  display: block;
  clear: both;
  visibility: hidden;
  line-height: 0;
  height: 0;
}

.clearfix {
  display: inline-block;
}

html[xmlns] .clearfix {
  display: block;
}

* html .clearfix {
  height: 1%;
}

ul, li {
  padding: 0;
  margin: 0;
  list-style: none;
}

header, nav, section, article, aside, footer, hgroup {
  display: block;
}

* {
  box-sizing: border-box;
}

html, body {
  font-family: 'Poppins', sans-serif;
  font-weight: 400;
  background-color: #fff;
  -ms-text-size-adjust: 100%;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

a {
  text-decoration: none !important;
}

h1, h2, h3, h4, h5, h6 {
  margin-top: 0px;
  margin-bottom: 0px;
}

ul {
  margin-bottom: 0px;
}

p {
  font-size: 15px;
  line-height: 30px;
  font-weight: 300;
  color: #afafaf;
}

img {
  width: 100%;
  overflow: hidden;
}

/* 
---------------------------------------------
global styles
--------------------------------------------- 
*/
html,
body {
  background: #fff;
  font-family: 'Poppins', sans-serif;
}

::selection {
  background: #fe664e;
  color: #fff !important;
}

::-moz-selection {
  background: #fe664e;
  color: #fff !important;
}

@media (max-width: 991px) {
  html, body {
    overflow-x: hidden;
  }
  .mobile-top-fix {
    margin-top: 30px;
    margin-bottom: 0px;
  }
  .mobile-bottom-fix {
    margin-bottom: 30px;
  }
  .mobile-bottom-fix-big {
    margin-bottom: 60px;
  }
}

.page-section {
  margin-top: 120px;
}

.section-heading {
  position: relative;
  z-index: 2;
}


.section-heading h6 {
  font-size: 15px;
  font-weight: 700;
  color: #fe664e;
  text-transform: uppercase;
  margin-bottom: 15px;
}

.section-heading h4 {
  color: #2a2a2a;
  font-size: 35px;
  font-weight: 700;
  text-transform: capitalize;
  margin-bottom: 25px;
}

.section-heading h4 em {
  font-style: normal;
  color: #fe664e;
}

.section-heading .line-dec {
  width: 50px;
  height: 2px;
  background-color: #fe664e;
}

.border-first-button a {
  display: inline-block !important;
  padding: 10px 20px !important;
  color: #fe664e !important;
  border: 1px solid #fe664e !important;
  border-radius: 23px;
  font-weight: 500 !important;
  letter-spacing: 0.3px !important;
  transition: all .5s;
}

.border-first-button a:hover {
  background-color: #fe664e;
  color: #fff !important;
}



/* 
---------------------------------------------
header
--------------------------------------------- 
*/

.pre-header {
  background-color: #efefef;
  height: 60px;
  padding: 15px 0px;
}

.pre-header ul li {
  display: inline-block;
}

.pre-header ul.info li {
  margin-right: 45px;
}

.pre-header ul.info li a {
  color: #afafaf;
  font-size: 14px;
  transition: all .3s;
}

.pre-header ul.info li a:hover {
  color: #fe664e;
}

.pre-header ul.info li a i {
  font-size: 18px;
  margin-right: 8px;
}

.pre-header ul.social-media {
  text-align: right;
}

.pre-header ul.social-media li {
  margin-left: 5px;
}

.pre-header ul.social-media li a {
  background-color: #afafaf;
  color: #fff;
  display: inline-block;
  width: 30px;
  height: 30px;
  line-height: 30px;
  text-align: center;
  border-radius: 50%;
  font-size: 14px;
  transition: all .3s;
}

.pre-header ul.social-media li a:hover {
  background-color: #fe664e;
}

.background-header {
  background-color: #fff!important;
  height: 80px!important;
  position: fixed!important;
  top: 0px;
  left: 0px;
  right: 0px;
  box-shadow: 0px 5px 8px rgba(0,0,0,0.03);
}

.background-header .logo,
.background-header .main-nav .nav li a {
  color: #fff;
}

.background-header .main-nav .nav li:hover a {
  color: #fe664e;
}

.background-header .nav li a.active {
  position: relative;
  color: #fff;
}

.background-header .nav li a.active:after {
  position: absolute;
  width: 100%;
  height: 1px;
  background-color: #fe664e;
  content: '';
  left: 50%;
  bottom: -20px;
  transform: translateX(-50%);
}

.background-header .nav li:last-child a.active:after {
  background-color: transparent;
}

.header-area {
  background-color: #fff;
  box-shadow: 0px 5px 8px rgba(0,0,0,0.03);
  position: absolute;
  left: 0px;
  right: 0px;
  z-index: 100;
  height: 100px;
  -webkit-transition: all .5s ease 0s;
  -moz-transition: all .5s ease 0s;
  -o-transition: all .5s ease 0s;
  transition: all .5s ease 0s;
}

.header-area .main-nav {
  min-height: 80px;
  background: transparent;
}

.header-area .main-nav .logo {
  float: left;
  -webkit-transition: all 0.3s ease 0s;
  -moz-transition: all 0.3s ease 0s;
  -o-transition: all 0.3s ease 0s;
  transition: all 0.3s ease 0s;
}

.header-area .main-nav .logo {
    line-height: 100px;
    float: left;
    -webkit-transition: all 0.3s ease 0s;
    -moz-transition: all 0.3s ease 0s;
    -o-transition: all 0.3s ease 0s;
    transition: all 0.3s ease 0s;
}

.background-header .main-nav .logo {
  line-height: 80px;
}

.background-header .main-nav .nav {
  margin-top: 20px !important;
}

.header-area .main-nav .nav {
  float: right;
  margin-top: 30px;
  margin-right: 0px;
  background-color: transparent;
  -webkit-transition: all 0.3s ease 0s;
  -moz-transition: all 0.3s ease 0s;
  -o-transition: all 0.3s ease 0s;
  transition: all 0.3s ease 0s;
  position: relative;
  z-index: 999;
}

.header-area .main-nav .nav li {
  padding-left: 20px;
  padding-right: 20px;
}

.header-area .main-nav .nav li:last-child {
  padding-right: 0px;
  padding-left: 40px;
}

.header-area .main-nav .nav li:last-child a ,
.background-header .main-nav .nav li:last-child a {
  padding: 0px 20px !important;
  font-weight: 400;
}

.header-area .main-nav .nav li:last-child a:hover ,
.background-header .main-nav .nav li:last-child a:hover {
  color: #fff !important;
}

.header-area .main-nav .nav li a {
  display: block;
  font-weight: 500;
  font-size: 15px;
  color: #2a2a2a;
  text-transform: capitalize;
  -webkit-transition: all 0.3s ease 0s;
  -moz-transition: all 0.3s ease 0s;
  -o-transition: all 0.3s ease 0s;
  transition: all 0.3s ease 0s;
  height: 40px;
  line-height: 40px;
  border: transparent;
  letter-spacing: 1px;
}

.header-area .main-nav .nav li:hover a,
.header-area .main-nav .nav li a.active {
  color: #fe664e!important;
}

.background-header .main-nav .nav li:hover a,
.background-header .main-nav .nav li a.active {
  color: #fe664e!important;
  opacity: 1;
}

.header-area .main-nav .nav li.submenu {
  position: relative;
  padding-right: 30px;
}

.header-area .main-nav .nav li.submenu:after {
  font-family: FontAwesome;
  content: "\f107";
  font-size: 12px;
  color: #2a2a2a;
  position: absolute;
  right: 18px;
  top: 12px;
}

.background-header .main-nav .nav li.submenu:after {
  color: #2a2a2a;
}

.header-area .main-nav .nav li.submenu ul {
  position: absolute;
  width: 200px;
  box-shadow: 0 2px 28px 0 rgba(0, 0, 0, 0.06);
  overflow: hidden;
  top: 50px;
  opacity: 0;
  transform: translateY(+2em);
  visibility: hidden;
  z-index: -1;
  transition: all 0.3s ease-in-out 0s, visibility 0s linear 0.3s, z-index 0s linear 0.01s;
}

.header-area .main-nav .nav li.submenu ul li {
  margin-left: 0px;
  padding-left: 0px;
  padding-right: 0px;
}

.header-area .main-nav .nav li.submenu ul li a {
  opacity: 1;
  display: block;
  background: #f7f7f7;
  color: #2a2a2a!important;
  padding-left: 20px;
  height: 40px;
  line-height: 40px;
  -webkit-transition: all 0.3s ease 0s;
  -moz-transition: all 0.3s ease 0s;
  -o-transition: all 0.3s ease 0s;
  transition: all 0.3s ease 0s;
  position: relative;
  font-size: 13px;
  font-weight: 400;
  border-bottom: 1px solid #eee;
}

.header-area .main-nav .nav li.submenu ul li a:hover {
  background: #fff;
  color: #fe664e!important;
  padding-left: 25px;
}

.header-area .main-nav .nav li.submenu ul li a:hover:before {
  width: 3px;
}

.header-area .main-nav .nav li.submenu:hover ul {
  visibility: visible;
  opacity: 1;
  z-index: 1;
  transform: translateY(0%);
  transition-delay: 0s, 0s, 0.3s;
}

.header-area .main-nav .menu-trigger {
  cursor: pointer;
  display: block;
  position: absolute;
  top: 33px;
  width: 32px;
  height: 40px;
  text-indent: -9999em;
  z-index: 99;
  right: 40px;
  display: none;
}

.background-header .main-nav .menu-trigger {
  top: 23px;
}

.header-area .main-nav .menu-trigger span,
.header-area .main-nav .menu-trigger span:before,
.header-area .main-nav .menu-trigger span:after {
  -moz-transition: all 0.4s;
  -o-transition: all 0.4s;
  -webkit-transition: all 0.4s;
  transition: all 0.4s;
  background-color: #2a2a2a;
  display: block;
  position: absolute;
  width: 30px;
  height: 2px;
  left: 0;
}

.background-header .main-nav .menu-trigger span,
.background-header .main-nav .menu-trigger span:before,
.background-header .main-nav .menu-trigger span:after {
  background-color: #2a2a2a;
}

.header-area .main-nav .menu-trigger span:before,
.header-area .main-nav .menu-trigger span:after {
  -moz-transition: all 0.4s;
  -o-transition: all 0.4s;
  -webkit-transition: all 0.4s;
  transition: all 0.4s;
  background-color: #2a2a2a;
  display: block;
  position: absolute;
  width: 30px;
  height: 2px;
  left: 0;
  width: 75%;
}

.background-header .main-nav .menu-trigger span:before,
.background-header .main-nav .menu-trigger span:after {
  background-color: #2a2a2a;
}

.header-area .main-nav .menu-trigger span:before,
.header-area .main-nav .menu-trigger span:after {
  content: "";
}

.header-area .main-nav .menu-trigger span {
  top: 16px;
}

.header-area .main-nav .menu-trigger span:before {
  -moz-transform-origin: 33% 100%;
  -ms-transform-origin: 33% 100%;
  -webkit-transform-origin: 33% 100%;
  transform-origin: 33% 100%;
  top: -10px;
  z-index: 10;
}

.header-area .main-nav .menu-trigger span:after {
  -moz-transform-origin: 33% 0;
  -ms-transform-origin: 33% 0;
  -webkit-transform-origin: 33% 0;
  transform-origin: 33% 0;
  top: 10px;
}

.header-area .main-nav .menu-trigger.active span,
.header-area .main-nav .menu-trigger.active span:before,
.header-area .main-nav .menu-trigger.active span:after {
  background-color: transparent;
  width: 100%;
}

.header-area .main-nav .menu-trigger.active span:before {
  -moz-transform: translateY(6px) translateX(1px) rotate(45deg);
  -ms-transform: translateY(6px) translateX(1px) rotate(45deg);
  -webkit-transform: translateY(6px) translateX(1px) rotate(45deg);
  transform: translateY(6px) translateX(1px) rotate(45deg);
  background-color: #2a2a2a;
}

.background-header .main-nav .menu-trigger.active span:before {
  background-color: #2a2a2a;
}

.header-area .main-nav .menu-trigger.active span:after {
  -moz-transform: translateY(-6px) translateX(1px) rotate(-45deg);
  -ms-transform: translateY(-6px) translateX(1px) rotate(-45deg);
  -webkit-transform: translateY(-6px) translateX(1px) rotate(-45deg);
  transform: translateY(-6px) translateX(1px) rotate(-45deg);
  background-color: #2a2a2a;
}

.background-header .main-nav .menu-trigger.active span:after {
  background-color: #2a2a2a;
}

.header-area.header-sticky {
  min-height: 80px;
}

.header-area .nav {
  margin-top: 30px;
}

.header-area.header-sticky .nav li a.active {
  color: #fe664e;
}

@media (max-width: 1200px) {
  .header-area .main-nav .nav li {
    padding-left: 12px;
    padding-right: 12px;
  }
  .header-area .main-nav:before {
    display: none;
  }
}

@media (max-width: 992px) {
  .header-area .main-nav .nav li:last-child  ,
  .background-header .main-nav .nav li:last-child {
    display: none;
  }
  .header-area .main-nav .nav li:nth-child(6),
  .background-header .main-nav .nav li:nth-child(6) {
    padding-right: 0px;
  }
  .background-header .nav li a.active:after {
    display: none;
  }
}

@media (max-width: 767px) {
  .pre-header ul.info li:last-child {
    display: none;
  }
  .background-header .main-nav .nav {
    margin-top: 80px !important;
  }
  .header-area .main-nav .logo {
    color: #1e1e1e;
  }
  .header-area.header-sticky .nav li a:hover,
  .header-area.header-sticky .nav li a.active {
    color: #fe664e!important;
    opacity: 1;
  }
  .header-area.header-sticky .nav li.search-icon a {
    width: 100%;
  }
  .header-area {
    background-color: #fff;
    padding: 0px 15px;
    height: 100px;
    box-shadow: none;
    text-align: center;
    box-shadow: 0px 5px 8px rgba(0,0,0,0.03);
  }
  .header-area .container {
    padding: 0px;
  }
  .header-area .logo {
    margin-left: 30px;
  }
  .header-area .menu-trigger {
    display: block !important;
  }
  .header-area .main-nav {
    overflow: hidden;
  }
  .header-area .main-nav .nav {
    float: none;
    width: 100%;
    display: none;
    -webkit-transition: all 0s ease 0s;
    -moz-transition: all 0s ease 0s;
    -o-transition: all 0s ease 0s;
    transition: all 0s ease 0s;
    margin-left: 0px;
  }
  .background-header .nav {
    margin-top: 80px;
  }
  .header-area .main-nav .nav li:first-child {
    border-top: 1px solid #eee;
  }
  .header-area.header-sticky .nav {
    margin-top: 100px;
  }
  .header-area .main-nav .nav li {
    width: 100%;
    background: #fff;
    border-bottom: 1px solid #e7e7e7;
    padding-left: 0px !important;
    padding-right: 0px !important;
  }
  .header-area .main-nav .nav li a {
    height: 50px !important;
    line-height: 50px !important;
    padding: 0px !important;
    border: none !important;
    background: #f7f7f7 !important;
    color: #191a20 !important;
  }
  .header-area .main-nav .nav li a:hover {
    background: #eee !important;
    color: #fe664e!important;
  }
  .header-area .main-nav .nav li.submenu ul {
    position: relative;
    visibility: inherit;
    opacity: 1;
    z-index: 1;
    transform: translateY(0%);
    transition-delay: 0s, 0s, 0.3s;
    top: 0px;
    width: 100%;
    box-shadow: none;
    height: 0px;
  }
  .header-area .main-nav .nav li.submenu ul li a {
    font-size: 12px;
    font-weight: 400;
  }
  .header-area .main-nav .nav li.submenu ul li a:hover:before {
    width: 0px;
  }
  .header-area .main-nav .nav li.submenu ul.active {
    height: auto !important;
  }
  .header-area .main-nav .nav li.submenu:after {
    color: #3B566E;
    right: 25px;
    font-size: 14px;
    top: 15px;
  }
  .header-area .main-nav .nav li.submenu:hover ul, .header-area .main-nav .nav li.submenu:focus ul {
    height: 0px;
  }
}

@media (min-width: 767px) {
  .header-area .main-nav .nav {
    display: flex !important;
  }
}

/* 
---------------------------------------------
preloader
--------------------------------------------- 
*/

.js-preloader {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-color: #fff;
    display: -webkit-box;
    display: flex;
    -webkit-box-align: center;
    align-items: center;
    -webkit-box-pack: center;
    justify-content: center;
    opacity: 1;
    visibility: visible;
    z-index: 9999;
    -webkit-transition: opacity 0.25s ease;
    transition: opacity 0.25s ease;
}

.js-preloader.loaded {
    opacity: 0;
    visibility: hidden;
    pointer-events: none;
}

@-webkit-keyframes dot {
    50% {
        -webkit-transform: translateX(96px);
        transform: translateX(96px);
    }
}

@keyframes dot {
    50% {
        -webkit-transform: translateX(96px);
        transform: translateX(96px);
    }
}

@-webkit-keyframes dots {
    50% {
        -webkit-transform: translateX(-31px);
        transform: translateX(-31px);
    }
}

@keyframes dots {
    50% {
        -webkit-transform: translateX(-31px);
        transform: translateX(-31px);
    }
}

.preloader-inner {
    position: relative;
    width: 142px;
    height: 40px;
    background: #fff;
}

.preloader-inner .dot {
    position: absolute;
    width: 16px;
    height: 16px;
    top: 12px;
    left: 15px;
    background: #fe664e;
    border-radius: 50%;
    -webkit-transform: translateX(0);
    transform: translateX(0);
    -webkit-animation: dot 2.8s infinite;
    animation: dot 2.8s infinite;
}

.preloader-inner .dots {
    -webkit-transform: translateX(0);
    transform: translateX(0);
    margin-top: 12px;
    margin-left: 31px;
    -webkit-animation: dots 2.8s infinite;
    animation: dots 2.8s infinite;
}

.preloader-inner .dots span {
    display: block;
    float: left;
    width: 16px;
    height: 16px;
    margin-left: 16px;
    background: #fe664e;
    border-radius: 50%;
}



/* 
---------------------------------------------
Banner Style
--------------------------------------------- 
*/

.main-banner {
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  padding: 226px 0px 120px 0px;
  position: relative;
  overflow: hidden;
}

.main-banner:after {
  content: '';
  background-image: url(../images/slider-left-dec.jpg);
  background-repeat: no-repeat;
  position: absolute;
  left: 0;
  top: 60px;
  width: 262px;
  height: 625px;
  z-index: 1;
}

.main-banner:before {
  content: '';
  background-image: url(../images/slider-right-dec.jpg);
  background-repeat: no-repeat;
  position: absolute;
  right: 0;
  top: 60px;
  width: 1159px;
  height: 797px;
  z-index: -1;
}

.main-banner .left-content {
  margin-right: 15px;
}

.main-banner .left-content h6 {
  text-transform: capitalize;
  font-size: 20px;
  font-weight: 700;
  color: #fe664e;
  margin-bottom: 15px;
  text-transform: uppercase;
}

.main-banner .left-content h2 {
  z-index: 2;
  position: relative;
  font-weight: 700;
  font-size: 50px;
  color: #2a2a2a;
  margin-bottom: 20px;
}

.main-banner .left-content p {
  margin-bottom: 30px;
  margin-right: 45px;
}

.main-banner .right-image {
  text-align: right;
  position: relative;
  z-index: 20;
}

.main-banner .right-image img {
  max-width: 593px;
}



/* 
---------------------------------------------
About Style
--------------------------------------------- 
*/

#about {
  padding-top: 130px;
}

.about-left-image img {
  margin-right: 45px;
}

.about-right-content p {
  margin-top: 30px;
  margin-bottom: 45px;
}

.skills-content {
  position: relative;
  z-index: 1;
  margin-top: -50px;
  background-color: #f5f5f5;
  border-bottom-right-radius: 50px;
  border-bottom-left-radius: 50px;
  padding: 110px 0px 50px 0px;
}

.skill-item {
  text-align: center;
}

.progress {
  width: 150px;
  height: 150px;
  line-height: 150px;
  background: none;
  margin: 0 auto;
  box-shadow: none;
  position: relative;
}
.progress:after {
  content: "";
  width: 100%;
  height: 100%;
  border-radius: 50%;
  border: 5px solid #fff;
  position: absolute;
  top: 0;
  left: 0;
}
.progress > span {
  width: 50%;
  height: 100%;
  overflow: hidden;
  position: absolute;
  top: 0;
  z-index: 1;
}
.progress .progress-left {
  left: 0;
}
.progress .progress-bar {
  width: 100%;
  height: 100%;
  background: none;
  border-width: 5px;
  border-style: solid;
  position: absolute;
  top: 0;
  border-color: #fd6a54;
}

.first-skill-item .progress .progress-bar {
  border-color: #fe664e;
}

.second-skill-item .progress .progress-bar {
  border-color: #726ae3;
}

.third-skill-item .progress .progress-bar {
  border-color: #f58b56;
}

.progress .progress-left .progress-bar {
  left: 100%;
  border-top-right-radius: 75px;
  border-bottom-right-radius: 75px;
  border-left: 0;
  -webkit-transform-origin: center left;
  transform-origin: center left;
}
.progress .progress-right {
  right: 0;
}
.progress .progress-right .progress-bar {
  left: -100%;
  border-top-left-radius: 75px;
  border-bottom-left-radius: 75px;
  border-right: 0;
  -webkit-transform-origin: center right;
  transform-origin: center right;
}
.progress .progress-value {
  text-align: center;
  color: #2a2a2a;
  display: flex;
  width: 100%;
  border-radius: 50%;
  font-size: 35px;
  text-align: center;
  line-height: 25px;
  align-items: center;
  justify-content: center;
  height: 100%;
  font-weight: 700;
}
.progress .progress-value div {
  margin-top: 10px;
}
.progress .progress-value span {
  font-size: 18px;
  text-transform: none;
  color: #afafaf;
  font-weight: 300;
}

/* This for loop creates the  necessary css animation names 
Due to the split circle of progress-left and progress right, we must use the animations on each side. 
*/
.progress[data-percentage="10"] .progress-right .progress-bar {
  animation: loading-1 1.5s linear forwards;
}
.progress[data-percentage="10"] .progress-left .progress-bar {
  animation: 0;
}

.progress[data-percentage="20"] .progress-right .progress-bar {
  animation: loading-2 1.5s linear forwards;
}
.progress[data-percentage="20"] .progress-left .progress-bar {
  animation: 0;
}

.progress[data-percentage="30"] .progress-right .progress-bar {
  animation: loading-3 1.5s linear forwards;
}
.progress[data-percentage="30"] .progress-left .progress-bar {
  animation: 0;
}

.progress[data-percentage="40"] .progress-right .progress-bar {
  animation: loading-4 1.5s linear forwards;
}
.progress[data-percentage="40"] .progress-left .progress-bar {
  animation: 0;
}

.progress[data-percentage="50"] .progress-right .progress-bar {
  animation: loading-5 1.5s linear forwards;
}
.progress[data-percentage="50"] .progress-left .progress-bar {
  animation: 0;
}

.progress[data-percentage="60"] .progress-right .progress-bar {
  animation: loading-5 1.5s linear forwards;
}
.progress[data-percentage="60"] .progress-left .progress-bar {
  animation: loading-1 1.5s linear forwards 1.5s;
}

.progress[data-percentage="70"] .progress-right .progress-bar {
  animation: loading-5 1.5s linear forwards;
}
.progress[data-percentage="70"] .progress-left .progress-bar {
  animation: loading-2 1.5s linear forwards 1.5s;
}

.progress[data-percentage="80"] .progress-right .progress-bar {
  animation: loading-5 1.5s linear forwards;
}
.progress[data-percentage="80"] .progress-left .progress-bar {
  animation: loading-3 1.5s linear forwards 1.5s;
}

.progress[data-percentage="90"] .progress-right .progress-bar {
  animation: loading-5 1.5s linear forwards;
}
.progress[data-percentage="90"] .progress-left .progress-bar {
  animation: loading-4 1.5s linear forwards 1.5s;
}

.progress[data-percentage="100"] .progress-right .progress-bar {
  animation: loading-5 1.5s linear forwards;
}
.progress[data-percentage="100"] .progress-left .progress-bar {
  animation: loading-5 1.5s linear forwards 1.5s;
}

@keyframes loading-1 {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(36);
    transform: rotate(36deg);
  }
}
@keyframes loading-2 {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(72);
    transform: rotate(72deg);
  }
}
@keyframes loading-3 {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(108);
    transform: rotate(108deg);
  }
}
@keyframes loading-4 {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(144);
    transform: rotate(144deg);
  }
}
@keyframes loading-5 {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(180);
    transform: rotate(180deg);
  }
}
.progress {
  margin-bottom: 1em;
}

/* 
---------------------------------------------
Services Style
--------------------------------------------- 
*/

.services {
  padding-top: 130px;
  position: relative;
}

.services:after {
  content: '';
  background-image: url(../images/services-left-dec.jpg);
  background-repeat: no-repeat;
  position: absolute;
  left: 0;
  top: 0px;
  width: 786px;
  height: 1217px;
  z-index: 0;
}

.services:before {
  content: '';
  background-image: url(../images/services-right-dec.jpg);
  background-repeat: no-repeat;
  position: absolute;
  right: 0;
  top: 400px;
  width: 161px;
  height: 413px;
  z-index: 0;
}

.services .section-heading {
  text-align: center;
  margin-bottom: 80px;
}

.services .section-heading .line-dec {
  margin: 0 auto;
}

.services .naccs {
  position: relative;
  z-index: 1;
}

.services .icon {
  display: block;
  text-align: center;
  margin: 0 auto;
}

.services .naccs .menu div h4 {
  color: #fff;
  font-size: 15px;
  font-weight: 400;
  width: 100%;
}

.services .icon img {
  margin-bottom: 10px;
  max-width: 60px;
  min-width: 60px;
}

.services .naccs .menu {
  text-align: center;
  margin-bottom: 30px;
}

.services .naccs .menu div {
  color: #2a2a2a;
  margin: 0px;
  width: 15%;
  font-size: 20px;
  font-weight: 700;
  display: inline-block;
  text-align: center;
  cursor: pointer;
  position: relative;
  border-radius: 15px;
  transition: 1s all cubic-bezier(0.075, 0.82, 0.165, 1);
}

.services .naccs .menu div .thumb {
  display: inline-block;
  width: 100%;
  padding: 30px 0px;
  background-color: #fff;
}

.services .naccs .menu div.active {
  box-shadow: 0px 0px 15px rgba(0,0,0,0.1);
}

.services ul.nacc {
  height: 100% !important;
  position: relative;
  min-height: 100%;
  list-style: none;
  margin: 0;
  padding: 0;
  transition: 0.5s all cubic-bezier(0.075, 0.82, 0.165, 1);
}

.services ul.nacc li {
  opacity: 0;
  transform: translateX(-50px);
  position: absolute;
  list-style: none;
  transition: 1s all cubic-bezier(0.075, 0.82, 0.165, 1);
}

.services ul.nacc li.active {
  transition-delay: 0.3s;
  position: relative;
  z-index: 2;
  opacity: 1;
  transform: translateX(0px);
  box-shadow: 0px 0px 15px rgba(0,0,0,0.1);
  background-color: #fff;
  border-radius: 15px;
  padding: 80px 120px 50px 120px;
}

.services ul.nacc li {
  width: 100%;
}

.services ul.nacc li .right-image img {
  max-width: 420px;
  float: right;
}

.services .nacc .thumb h4 {
  color: #2a2a2a;
  font-size: 20px;
  font-weight: 700;
  line-height: 35px;
  margin-bottom: 25px;
}

.services .nacc .thumb .main-white-button {
  text-align: right;
  margin-top: 40px;
}

.services .nacc .thumb .main-white-button a {
  background-color: #8d99af;
  color: #fff;
}

.services .nacc .thumb .main-white-button a i {
  background-color: #fff;
  color: #8d99af;
}

.services .left-text h4 {
  font-size: 20px;
  font-weight: 700;
  color: #fe664e !important;
}

.services .left-text p {
  margin-bottom: 30px;
}

.nacc .ticks-list span {
  display: inline-block;
  opacity: 1;
  margin-right: 45px;
  margin-bottom: 20px;
  font-size: 15px;
  font-weight: 400;
}



/* 
---------------------------------------------
Free Quote
--------------------------------------------- 
*/

.free-quote {
  background-image: url(../images/quote-bg-v2.jpg);
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  padding: 120px 0px;
  text-align: center;
  position: relative;
  z-index: 2;
  margin-top: 130px;
}

.free-quote .section-heading {
  margin-bottom: 60px;
}

.free-quote .section-heading h6,
.free-quote .section-heading h4 {
  color: #fff;
}

.free-quote .section-heading .line-dec {
  margin: 0 auto;
  background-color: #fff;
}

.free-quote form {
  background-color: #fff;
  display: inline-block;
  width: 100%;
  min-height: 80px;
  border-radius: 40px;
  position: relative;
  z-index: 1;
}

.free-quote form input {
  width: 100%;
  margin-top: 20px;
  margin-left: 30px;
  color: #afafaf;
  font-weight: 400;
  font-size: 15px;
  height: 40px;
  background-color: transparent;
  border-bottom: 1px solid #eee;
  border-top: none;
  border-left: none;
  border-right: none;
  position: relative;
  z-index: 2;
  outline: none;
}

.free-quote form button {
  width: 100%;
  height: 80px;
  border-top-right-radius: 40px;
  border-bottom-right-radius: 40px;
  outline: none;
  border: none;
  margin-left: 30px;
  background-color: #fe664e;
  font-size: 15px;
  color: #fff;
}


/* 
---------------------------------------------
Portfolio
--------------------------------------------- 
*/

.our-portfolio {
  padding-top: 130px;
  overflow: hidden;
  position: relative;
}

.our-portfolio:before {
  content: '';
  background-image: url(../images/portfolio-right-dec.jpg);
  background-repeat: no-repeat;
  position: absolute;
  right: 0;
  top: 0px;
  width: 414px;
  height: 861px;
  z-index: 1;
}

.our-portfolio:after {
  content: '';
  background-image: url(../images/portfolio-left-dec.jpg);
  background-repeat: no-repeat;
  position: absolute;
  left: 0;
  top: 0px;
  width: 677px;
  height: 759px;
  z-index: 1;
}

.our-portfolio .section-heading {
  margin-bottom: 80px;
}

.our-portfolio .container-fluid {
  padding-right: 15px;
  padding-left: 15px;
  position: relative;
  z-index: 2;
}

.our-portfolio .item {
  position: relative;
  z-index: 222;
}

.portfolio-item {
  border-radius: 25px;
  box-shadow: 0px 0px 15px rgba(0,0,0,0.1);
  margin: 15px;
}

.portfolio-item .thumb {
  position: relative;
  border-radius: 50px;
}

.portfolio-item:hover .down-content h4,
.portfolio-item:hover .down-content span {
  color: #fe664e;
}

.portfolio-item .thumb img {
  border-top-right-radius: 23px;
  border-top-left-radius: 23px;
  overflow: hidden;
}

.portfolio-item .down-content {
  background-color: #fff;
  text-align: center;
  padding: 18px 0px;
  border-bottom-right-radius: 23px;
  border-bottom-left-radius: 23px;
}

.portfolio-item .down-content h4 {
  font-size: 20px;
  font-weight: 700;
  color: #2a2a2a;
  margin-bottom: 8px;
  transition: all .3s;
}

.portfolio-item .down-content span {
  font-size: 15px;
  color: #afafaf;
  transition: all .3s;
}

.our-portfolio .owl-nav {
  display: inline-block!important;
  position: absolute;
  top: -125px;
  right: 15%;
  max-width: 1320px;
}

.our-portfolio .owl-nav .owl-next {
  margin-left: 10px;
}

.our-portfolio .owl-nav span {
  width: 46px;
  height: 46px;
  display: inline-block;
  text-align: center;
  line-height: 46px;
  font-size: 30px;
  background-color: #eee;
  border-radius: 50%;
  color: #fff;
  transition: all 0.5s;
}

.our-portfolio .owl-nav span:hover {
  color: #fff;
  background-color: #fe664e;
}


/* 
---------------------------------------------
Blog
--------------------------------------------- 
*/

.blog:before {
  content: '';
  background-image: url(../images/blog-left-dec.jpg);
  background-repeat: no-repeat;
  position: absolute;
  left: 0;
  top: 0px;
  width: 961px;
  height: 1020px;
  z-index: 0;
}

.blog {
  position: relative;
  padding-top: 130px;
}

.blog .section-heading {
  text-align: center;
  margin-bottom: 80px;
}

.blog .section-heading .line-dec {
  margin: 0 auto;
}

.blog-post {
  box-shadow: 0px 0px 15px rgba(0,0,0,0.1);
  border-radius: 25px;
}

.show-up {
  position: relative;
  z-index: 200;
}

.blog-post .thumb img {
  border-top-right-radius: 23px;
  border-top-left-radius: 23px;
}

.blog-post .down-content {
  border-bottom-right-radius: 23px;
  border-bottom-left-radius: 23px;
  background-color: #fff;
  padding: 30px;
}

.blog-post .down-content span.category {
  font-size: 15px;
  color: #fff;
  padding: 8px 12px;
  background-color: #fe664e;
  border-radius: 18px;
  display: inline-block;
}

.blog-post .down-content span.date {
  font-size: 15px;
  color: #afafaf;
  text-align: right;
  float: right;
  margin-top: 4px;
}

.blog-post .down-content h4 {
  font-size: 20px;
  font-weight: 700;
  color: #2a2a2a;
  margin-top: 20px;
  margin-bottom: 20px;
  line-height: 30px;
}

.blog-post .down-content p {
  margin-bottom: 30px;
}

.blog-post .down-content span.author {
  font-size: 15px;
  color: #2a2a2a;
}

.blog-post .down-content span.author img {
  max-width: 56px;
  border-radius: 50%;
  margin-right: 15px;
}

.blog-post .down-content .border-first-button {
  display: inline-block;
  float: right;
}

.blog-posts {
  margin-left: 30px;
}

.post-item {
  margin-bottom: 62px;
}

.last-post-item {
  margin-bottom: 0px;
}

.post-item .thumb {
  display: inline-block;
  float: left;
  margin-right: 30px;
}

.post-item .thumb img {
  border-radius: 23px;
  display: inline-block;
}

.post-item .right-content {
  padding-top: 20px;
}

.post-item .right-content span.category {
  font-size: 15px;
  color: #fff;
  padding: 8px 12px;
  background-color: #fe664e;
  border-radius: 18px;
  display: inline-block;
}

.post-item .right-content span.date {
  font-size: 15px;
  color: #afafaf;
  text-align: right;
  float: right;
  margin-top: 4px;
}

.post-item .right-content h4 {
  font-size: 20px;
  font-weight: 700;
  color: #2a2a2a;
  margin-top: 20px;
  margin-bottom: 20px;
  line-height: 30px;
}


/* 
---------------------------------------------
contact
--------------------------------------------- 
*/

.contact-us {
  padding-top: 130px;
}

.contact-us .section-heading .line-dec {
  margin: 0 auto;
}

.contact-us .section-heading {
  text-align: center;
  margin-bottom: 80px;
}


form#contact:before {
  background-image: url(../images/contact-top-right-v2.png);
  position: absolute;
  right: 0;
  top: 0;
  width: 726px;
  height: 78px;
  background-repeat: no-repeat;
  content: '';
  z-index: 1;
}

.contact-dec img {
  max-width: 224px;
  position: absolute;
  right: 25px;
  top: -242px;
}

form#contact:after {
  background-image: url(../images/contact-bottom-right-v2.png);
  position: absolute;
  right: 0;
  bottom: 0;
  width: 532px;
  height: 106px;
  background-repeat: no-repeat;
  content: '';
  z-index: 1;
}

form#contact {
  box-shadow: 0px 0px 15px rgba(0,0,0,0.1);
  position: relative;
  background-color: #fff;
  border-radius: 23px;
  text-align: center;
}

form#contact #map iframe {
  border-top-left-radius: 23px;
  border-bottom-left-radius: 23px;
  margin-bottom: -7px;
  position: relative;
  z-index: 2;
}

.fill-form {
  padding: 80px 60px 80px 30px;
}

.fill-form .info-post {
  margin-bottom: 20px;
}

.fill-form .icon {
  text-align: center;
  box-shadow: 0px 0px 15px rgba(0,0,0,0.1);
  border-radius: 23px;
  padding: 25px 15px;
}

.fill-form .icon img {
  max-width: 60px;
  display: block;
  margin: 0 auto;
}

.fill-form .icon a {
  margin-top: 15px;
  display: inline-block;
  font-size: 15px;
  font-weight: 500;
  color: #2a2a2a;
  transition: all .3s;
}

.fill-form .icon:hover a {
  color: #fe664e;
}

form#contact input {
  width: 100%;
  height: 46px;
  background-color: transparent;
  border: 1px solid #eee;
  outline: none;
  font-size: 15px;
  font-weight: 300;
  color: #2a2a2a;
  padding: 0px 20px;
  border-radius: 23px;
  margin-top: 30px;
}

form#contact input::placeholder {
  color: #aaa;
}

form#contact textarea {
  width: 100%;
  min-width: 100%;
  max-width: 100%;
  max-height: 200px;
  min-height: 200px;
  height: 200px;
  border-radius: 23px;
  background-color: transparent;
  border: 1px solid #eee;
  outline: none;
  font-size: 15px;
  font-weight: 300;
  color: #2a2a2a;
  padding: 15px 20px;
  margin-top: 30px;
}

form#contact textarea::placeholder {
  color: #aaa;
}

form#contact button {
  display: inline-block;
  background-color: #fff;
  font-size: 15px;
  font-weight: 400;
  color: #fe664e;
  margin-top: 30px;
  width: 100%;
  text-transform: capitalize;
  padding: 12px 25px;
  border-radius: 23px;
  letter-spacing: 0.25px;
  border: 1px solid #fe664e;
  transition: all .3s;
  outline: none;
}

form#contact button:hover {
  background-color: #fe664e!important;
  color: #fff!important;
}

/* 
---------------------------------------------
Footer Style
--------------------------------------------- 
*/

footer {
  background-image: url(../images/footer-bg-v2.jpg);
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
  margin-top: 130px;
}

footer p {
  text-align: center;
  margin: 20px 0px;
  color: #fff;
}

footer p a {
  color: #fff;
  transition: all .5s;
}

/* 
---------------------------------------------
responsive
--------------------------------------------- 
*/

@media (max-width: 1200px) {
  .header-area .main-nav .logo h4 {
    font-size: 24px;
  }
  .header-area .main-nav .logo h4 img {
    max-width: 25px;
    margin-left: 0px;
  }
  .header-area .main-nav .nav li:last-child {
    padding-left: 20px;
  }
}

@media (max-width: 992px) {
  form#contact {
    overflow: hidden;
  }
  .header-area .main-nav .logo h4 {
    font-size: 20px;
  }
  .main-banner .left-content {
    margin-right: 0px;
  }
  .main-banner {
    text-align: center;
    padding: 226px 0px 30px 0px;
  }
  .main-banner:before {
    display: none;
  }
  .main-banner .right-image {
    margin: 30px auto 0px auto;
    text-align: center;
  }
  .features-item {
    margin-bottom: 45px;
  }
  .last-features-item,
  .last-skill-item {
    margin-bottom: 0px !important;
  }
  .skill-item {
    margin-bottom: 30px;
  }
  .about-left-image img {
    margin-right: 0px;
    margin-bottom: 45px;;
  }
  .services .naccs .menu div {
    font-size: 15px;
    font-weight: 500;
  }
  .service-item {
    text-align: center;
  }
  .service-item .icon {
    margin-top: 0px;
    margin-bottom: 30px;
  }
  .about-us .left-image {
    margin-right: 30px;
    margin-left: 30px;
    margin-bottom: 45px;
  }
  .blog-posts {
    margin-left: 0px;
    margin-top: 30px;
  }
  .post-item {
    margin-bottom: 70px;
  }
  .our-portfolio .owl-nav {
    display: none !important;
  }
  .contact-info {
    margin-top: 60px;
  }
  form#contact {
    padding: 45px;
  }
}

@media (max-width: 767px) {
  .header-area .main-nav .logo h4 {
    font-size: 30px;
  }
  .header-area .main-nav .logo h4 img {
    max-width: 30px;
    margin-left: 5px;
  }
  .main-banner .info-stat {
    margin-bottom: 15px;
  }
  .service-item {
    text-align: center;
    padding: 30px;
  }
  .service-item .icon {
    float: none;
    margin-right: 0px;
    margin-bottom: 15px;
  }
  .service-item .right-content {
    display: inline-block;
  }
  .services .naccs .menu div .thumb {
    padding: 5px;
  }
  .services .icon img {
    margin: 0px;
  }
  .services ul.nacc li.active {
    padding: 45px;
  }
  .services .naccs .menu div  {
    font-size: 0px;
  }
  .services ul.nacc li .right-image img {
    float: none;
  }
  .our-portfolio .section-heading,
  .about-us .section-heading,
  .about-us .about-item,
  .about-us p,
  .about-us .main-green-button {
    text-align: center;
  }
  .our-portfolio .section-heading .line-dec {
    margin: 0 auto;
  }
  .our-services .section-heading {
    margin-left: 15px;
    margin-right: 15px;
  }
  .free-quote form input {
    margin-left: 0px;
    padding: 0px 30px;
  }
  .free-quote form button {
    margin-left: 0px;
    border-bottom-left-radius: 40px;
    border-top-right-radius: 0px;
  }
  .blog-posts {
    margin-left: 0px;
    margin-top: 30px;
  }
  .post-item {
    margin-bottom: 30px;
  }
  .post-item .thumb img {
    max-width: 140px;
  }
  .post-item .right-content p {
    display: none;
  }
  .about-us .about-item {
    margin-top: 15px;
  }
  form#contact {
    padding: 30px;
  }
}
/*

TemplateMo 568 DigiMedia

https://templatemo.com/tm-568-digimedia

*/

/* ---------------------------------------------
Table of contents
------------------------------------------------
01. font & reset css
02. reset
03. global styles
04. header
05. banner
06. features
07. testimonials
08. contact
09. footer
10. preloader
11. search
12. portfolio

--------------------------------------------- */
/* 
---------------------------------------------
font & reset css
--------------------------------------------- 
*/
/* 
---------------------------------------------
reset
--------------------------------------------- 
*/
html, body, div, span, applet, object, iframe, h1, h2, h3, h4, h5, h6, p, blockquote, div
pre, a, abbr, acronym, address, big, cite, code, del, dfn, em, font, img, ins, kbd, q,
s, samp, small, strike, strong, sub, sup, tt, var, b, u, i, center, dl, dt, dd, ol, ul, li,
figure, header, nav, section, article, aside, footer, figcaption {
  margin: 0;
  padding: 0;
  border: 0;
  outline: 0;
}

/* clear fix */
.grid:after {
  content: '';
  display: block;
  clear: both;
}

/* ---- .grid-item ---- */

.grid-sizer,
.grid-item {
  width: 50%;
}

.grid-item {
  float: left;
}

.grid-item img {
  display: block;
  max-width: 100%;
}

.clearfix:after {
  content: ".";
  display: block;
  clear: both;
  visibility: hidden;
  line-height: 0;
  height: 0;
}

.clearfix {
  display: inline-block;
}

html[xmlns] .clearfix {
  display: block;
}

* html .clearfix {
  height: 1%;
}

ul, li {
  padding: 0;
  margin: 0;
  list-style: none;
}

header, nav, section, article, aside, footer, hgroup {
  display: block;
}

* {
  box-sizing: border-box;
}

html, body {
  font-family: 'Poppins', sans-serif;
  font-weight: 400;
  background-color: #fff;
  -ms-text-size-adjust: 100%;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

a {
  text-decoration: none !important;
}

h1, h2, h3, h4, h5, h6 {
  margin-top: 0px;
  margin-bottom: 0px;
}

ul {
  margin-bottom: 0px;
}

p {
  font-size: 15px;
  line-height: 30px;
  font-weight: 300;
  color: #afafaf;
}

img {
  width: 100%;
  overflow: hidden;
}

/* 
---------------------------------------------
global styles
--------------------------------------------- 
*/
html,
body {
  background: #fff;
  font-family: 'Poppins', sans-serif;
}

::selection {
  background: #4da6e7;
  color: #fff !important;
}

::-moz-selection {
  background: #4da6e7;
  color: #fff !important;
}

@media (max-width: 991px) {
  html, body {
    overflow-x: hidden;
  }
  .mobile-top-fix {
    margin-top: 30px;
    margin-bottom: 0px;
  }
  .mobile-bottom-fix {
    margin-bottom: 30px;
  }
  .mobile-bottom-fix-big {
    margin-bottom: 60px;
  }
}

.page-section {
  margin-top: 120px;
}

.section-heading {
  position: relative;
  z-index: 2;
}

.section-heading h6 {
  font-size: 15px;
  font-weight: 700;
  color: #4da6e7;
  text-transform: uppercase;
  margin-bottom: 15px;
}

.section-heading h4 {
  color: #2a2a2a;
  font-size: 35px;
  font-weight: 700;
  text-transform: capitalize;
  margin-bottom: 25px;
}

.section-heading h4 em {
  font-style: normal;
  color: #4da6e7;
}

.section-heading .line-dec {
  width: 50px;
  height: 2px;
  background-color: #4da6e7;
}

.border-first-button a {
  display: inline-block !important;
  padding: 10px 20px !important;
  color: #4da6e7 !important;
  border: 1px solid #4da6e7 !important;
  border-radius: 23px;
  font-weight: 500 !important;
  letter-spacing: 0.3px !important;
  transition: all .5s;
}

.border-first-button a:hover {
  background-color: #4da6e7;
  color: #fff !important;
}



/* 
---------------------------------------------
header
--------------------------------------------- 
*/

.pre-header {
  background-color: #efefef;
  height: 60px;
  padding: 15px 0px;
}

.pre-header ul li {
  display: inline-block;
}

.pre-header ul.info li {
  margin-right: 45px;
}

.pre-header ul.info li a {
  color: #afafaf;
  font-size: 14px;
  transition: all .3s;
}

.pre-header ul.info li a:hover {
  color: #4da6e7;
}

.pre-header ul.info li a i {
  font-size: 18px;
  margin-right: 8px;
}

.pre-header ul.social-media {
  text-align: right;
}

.pre-header ul.social-media li {
  margin-left: 5px;
}

.pre-header ul.social-media li a {
  background-color: #afafaf;
  color: #fff;
  display: inline-block;
  width: 30px;
  height: 30px;
  line-height: 30px;
  text-align: center;
  border-radius: 50%;
  font-size: 14px;
  transition: all .3s;
}

.pre-header ul.social-media li a:hover {
  background-color: #4da6e7;
}

.background-header {
  background-color: #fff!important;
  height: 80px!important;
  position: fixed!important;
  top: 0px;
  left: 0px;
  right: 0px;
  box-shadow: 0px 5px 8px rgba(0,0,0,0.03);
}

.background-header .logo,
.background-header .main-nav .nav li a {
  color: #fff;
}

.background-header .main-nav .nav li:hover a {
  color: #4da6e7;
}

.background-header .nav li a.active {
  position: relative;
  color: #fff;
}

.background-header .nav li a.active:after {
  position: absolute;
  width: 100%;
  height: 1px;
  background-color: #4da6e7;
  content: '';
  left: 50%;
  bottom: -20px;
  transform: translateX(-50%);
}

.background-header .nav li:last-child a.active:after {
  background-color: transparent;
}

.header-area {
  background-color: #fff;
  box-shadow: 0px 5px 8px rgba(0,0,0,0.03);
  position: absolute;
  left: 0px;
  right: 0px;
  z-index: 100;
  height: 100px;
  -webkit-transition: all .5s ease 0s;
  -moz-transition: all .5s ease 0s;
  -o-transition: all .5s ease 0s;
  transition: all .5s ease 0s;
}

.header-area .main-nav {
  min-height: 80px;
  background: transparent;
}

.header-area .main-nav .logo {
  float: left;
  -webkit-transition: all 0.3s ease 0s;
  -moz-transition: all 0.3s ease 0s;
  -o-transition: all 0.3s ease 0s;
  transition: all 0.3s ease 0s;
}

.header-area .main-nav .logo {
    line-height: 100px;
    float: left;
    -webkit-transition: all 0.3s ease 0s;
    -moz-transition: all 0.3s ease 0s;
    -o-transition: all 0.3s ease 0s;
    transition: all 0.3s ease 0s;
}

.background-header .main-nav .logo {
  line-height: 80px;
}

.background-header .main-nav .nav {
  margin-top: 20px !important;
}

.header-area .main-nav .nav {
  float: right;
  margin-top: 30px;
  margin-right: 0px;
  background-color: transparent;
  -webkit-transition: all 0.3s ease 0s;
  -moz-transition: all 0.3s ease 0s;
  -o-transition: all 0.3s ease 0s;
  transition: all 0.3s ease 0s;
  position: relative;
  z-index: 999;
}

.header-area .main-nav .nav li {
  padding-left: 20px;
  padding-right: 20px;
}

.header-area .main-nav .nav li:last-child {
  padding-right: 0px;
  padding-left: 40px;
}

.header-area .main-nav .nav li:last-child a ,
.background-header .main-nav .nav li:last-child a {
  padding: 0px 20px !important;
  font-weight: 400;
}

.header-area .main-nav .nav li:last-child a:hover ,
.background-header .main-nav .nav li:last-child a:hover {
  color: #fff !important;
}

.header-area .main-nav .nav li a {
  display: block;
  font-weight: 500;
  font-size: 15px;
  color: #2a2a2a;
  text-transform: capitalize;
  -webkit-transition: all 0.3s ease 0s;
  -moz-transition: all 0.3s ease 0s;
  -o-transition: all 0.3s ease 0s;
  transition: all 0.3s ease 0s;
  height: 40px;
  line-height: 40px;
  border: transparent;
  letter-spacing: 1px;
}

.header-area .main-nav .nav li:hover a,
.header-area .main-nav .nav li a.active {
  color: #4da6e7!important;
}

.background-header .main-nav .nav li:hover a,
.background-header .main-nav .nav li a.active {
  color: #4da6e7!important;
  opacity: 1;
}

.header-area .main-nav .nav li.submenu {
  position: relative;
  padding-right: 30px;
}

.header-area .main-nav .nav li.submenu:after {
  font-family: FontAwesome;
  content: "\f107";
  font-size: 12px;
  color: #2a2a2a;
  position: absolute;
  right: 18px;
  top: 12px;
}

.background-header .main-nav .nav li.submenu:after {
  color: #2a2a2a;
}

.header-area .main-nav .nav li.submenu ul {
  position: absolute;
  width: 200px;
  box-shadow: 0 2px 28px 0 rgba(0, 0, 0, 0.06);
  overflow: hidden;
  top: 50px;
  opacity: 0;
  transform: translateY(+2em);
  visibility: hidden;
  z-index: -1;
  transition: all 0.3s ease-in-out 0s, visibility 0s linear 0.3s, z-index 0s linear 0.01s;
}

.header-area .main-nav .nav li.submenu ul li {
  margin-left: 0px;
  padding-left: 0px;
  padding-right: 0px;
}

.header-area .main-nav .nav li.submenu ul li a {
  opacity: 1;
  display: block;
  background: #f7f7f7;
  color: #2a2a2a!important;
  padding-left: 20px;
  height: 40px;
  line-height: 40px;
  -webkit-transition: all 0.3s ease 0s;
  -moz-transition: all 0.3s ease 0s;
  -o-transition: all 0.3s ease 0s;
  transition: all 0.3s ease 0s;
  position: relative;
  font-size: 13px;
  font-weight: 400;
  border-bottom: 1px solid #eee;
}

.header-area .main-nav .nav li.submenu ul li a:hover {
  background: #fff;
  color: #4da6e7!important;
  padding-left: 25px;
}

.header-area .main-nav .nav li.submenu ul li a:hover:before {
  width: 3px;
}

.header-area .main-nav .nav li.submenu:hover ul {
  visibility: visible;
  opacity: 1;
  z-index: 1;
  transform: translateY(0%);
  transition-delay: 0s, 0s, 0.3s;
}

.header-area .main-nav .menu-trigger {
  cursor: pointer;
  display: block;
  position: absolute;
  top: 33px;
  width: 32px;
  height: 40px;
  text-indent: -9999em;
  z-index: 99;
  right: 40px;
  display: none;
}

.background-header .main-nav .menu-trigger {
  top: 23px;
}

.header-area .main-nav .menu-trigger span,
.header-area .main-nav .menu-trigger span:before,
.header-area .main-nav .menu-trigger span:after {
  -moz-transition: all 0.4s;
  -o-transition: all 0.4s;
  -webkit-transition: all 0.4s;
  transition: all 0.4s;
  background-color: #2a2a2a;
  display: block;
  position: absolute;
  width: 30px;
  height: 2px;
  left: 0;
}

.background-header .main-nav .menu-trigger span,
.background-header .main-nav .menu-trigger span:before,
.background-header .main-nav .menu-trigger span:after {
  background-color: #2a2a2a;
}

.header-area .main-nav .menu-trigger span:before,
.header-area .main-nav .menu-trigger span:after {
  -moz-transition: all 0.4s;
  -o-transition: all 0.4s;
  -webkit-transition: all 0.4s;
  transition: all 0.4s;
  background-color: #2a2a2a;
  display: block;
  position: absolute;
  width: 30px;
  height: 2px;
  left: 0;
  width: 75%;
}

.background-header .main-nav .menu-trigger span:before,
.background-header .main-nav .menu-trigger span:after {
  background-color: #2a2a2a;
}

.header-area .main-nav .menu-trigger span:before,
.header-area .main-nav .menu-trigger span:after {
  content: "";
}

.header-area .main-nav .menu-trigger span {
  top: 16px;
}

.header-area .main-nav .menu-trigger span:before {
  -moz-transform-origin: 33% 100%;
  -ms-transform-origin: 33% 100%;
  -webkit-transform-origin: 33% 100%;
  transform-origin: 33% 100%;
  top: -10px;
  z-index: 10;
}

.header-area .main-nav .menu-trigger span:after {
  -moz-transform-origin: 33% 0;
  -ms-transform-origin: 33% 0;
  -webkit-transform-origin: 33% 0;
  transform-origin: 33% 0;
  top: 10px;
}

.header-area .main-nav .menu-trigger.active span,
.header-area .main-nav .menu-trigger.active span:before,
.header-area .main-nav .menu-trigger.active span:after {
  background-color: transparent;
  width: 100%;
}

.header-area .main-nav .menu-trigger.active span:before {
  -moz-transform: translateY(6px) translateX(1px) rotate(45deg);
  -ms-transform: translateY(6px) translateX(1px) rotate(45deg);
  -webkit-transform: translateY(6px) translateX(1px) rotate(45deg);
  transform: translateY(6px) translateX(1px) rotate(45deg);
  background-color: #2a2a2a;
}

.background-header .main-nav .menu-trigger.active span:before {
  background-color: #2a2a2a;
}

.header-area .main-nav .menu-trigger.active span:after {
  -moz-transform: translateY(-6px) translateX(1px) rotate(-45deg);
  -ms-transform: translateY(-6px) translateX(1px) rotate(-45deg);
  -webkit-transform: translateY(-6px) translateX(1px) rotate(-45deg);
  transform: translateY(-6px) translateX(1px) rotate(-45deg);
  background-color: #2a2a2a;
}

.background-header .main-nav .menu-trigger.active span:after {
  background-color: #2a2a2a;
}

.header-area.header-sticky {
  min-height: 80px;
}

.header-area .nav {
  margin-top: 30px;
}

.header-area.header-sticky .nav li a.active {
  color: #4da6e7;
}

@media (max-width: 1200px) {
  .header-area .main-nav .nav li {
    padding-left: 12px;
    padding-right: 12px;
  }
  .header-area .main-nav:before {
    display: none;
  }
}

@media (max-width: 992px) {
  .header-area .main-nav .nav li:last-child  ,
  .background-header .main-nav .nav li:last-child {
    display: none;
  }
  .header-area .main-nav .nav li:nth-child(6),
  .background-header .main-nav .nav li:nth-child(6) {
    padding-right: 0px;
  }
  .background-header .nav li a.active:after {
    display: none;
  }
}

@media (max-width: 767px) {
  .pre-header ul.info li:last-child {
    display: none;
  }
  .background-header .main-nav .nav {
    margin-top: 80px !important;
  }
  .header-area .main-nav .logo {
    color: #1e1e1e;
  }
  .header-area.header-sticky .nav li a:hover,
  .header-area.header-sticky .nav li a.active {
    color: #4da6e7!important;
    opacity: 1;
  }
  .header-area.header-sticky .nav li.search-icon a {
    width: 100%;
  }
  .header-area {
    background-color: #fff;
    padding: 0px 15px;
    height: 100px;
    box-shadow: none;
    text-align: center;
    box-shadow: 0px 5px 8px rgba(0,0,0,0.03);
  }
  .header-area .container {
    padding: 0px;
  }
  .header-area .logo {
    margin-left: 30px;
  }
  .header-area .menu-trigger {
    display: block !important;
  }
  .header-area .main-nav {
    overflow: hidden;
  }
  .header-area .main-nav .nav {
    float: none;
    width: 100%;
    display: none;
    -webkit-transition: all 0s ease 0s;
    -moz-transition: all 0s ease 0s;
    -o-transition: all 0s ease 0s;
    transition: all 0s ease 0s;
    margin-left: 0px;
  }
  .background-header .nav {
    margin-top: 80px;
  }
  .header-area .main-nav .nav li:first-child {
    border-top: 1px solid #eee;
  }
  .header-area.header-sticky .nav {
    margin-top: 100px;
  }
  .header-area .main-nav .nav li {
    width: 100%;
    background: #fff;
    border-bottom: 1px solid #e7e7e7;
    padding-left: 0px !important;
    padding-right: 0px !important;
  }
  .header-area .main-nav .nav li a {
    height: 50px !important;
    line-height: 50px !important;
    padding: 0px !important;
    border: none !important;
    background: #f7f7f7 !important;
    color: #191a20 !important;
  }
  .header-area .main-nav .nav li a:hover {
    background: #eee !important;
    color: #4da6e7!important;
  }
  .header-area .main-nav .nav li.submenu ul {
    position: relative;
    visibility: inherit;
    opacity: 1;
    z-index: 1;
    transform: translateY(0%);
    transition-delay: 0s, 0s, 0.3s;
    top: 0px;
    width: 100%;
    box-shadow: none;
    height: 0px;
  }
  .header-area .main-nav .nav li.submenu ul li a {
    font-size: 12px;
    font-weight: 400;
  }
  .header-area .main-nav .nav li.submenu ul li a:hover:before {
    width: 0px;
  }
  .header-area .main-nav .nav li.submenu ul.active {
    height: auto !important;
  }
  .header-area .main-nav .nav li.submenu:after {
    color: #3B566E;
    right: 25px;
    font-size: 14px;
    top: 15px;
  }
  .header-area .main-nav .nav li.submenu:hover ul, .header-area .main-nav .nav li.submenu:focus ul {
    height: 0px;
  }
}

@media (min-width: 767px) {
  .header-area .main-nav .nav {
    display: flex !important;
  }
}

/* 
---------------------------------------------
preloader
--------------------------------------------- 
*/

.js-preloader {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-color: #fff;
    display: -webkit-box;
    display: flex;
    -webkit-box-align: center;
    align-items: center;
    -webkit-box-pack: center;
    justify-content: center;
    opacity: 1;
    visibility: visible;
    z-index: 9999;
    -webkit-transition: opacity 0.25s ease;
    transition: opacity 0.25s ease;
}

.js-preloader.loaded {
    opacity: 0;
    visibility: hidden;
    pointer-events: none;
}

@-webkit-keyframes dot {
    50% {
        -webkit-transform: translateX(96px);
        transform: translateX(96px);
    }
}

@keyframes dot {
    50% {
        -webkit-transform: translateX(96px);
        transform: translateX(96px);
    }
}

@-webkit-keyframes dots {
    50% {
        -webkit-transform: translateX(-31px);
        transform: translateX(-31px);
    }
}

@keyframes dots {
    50% {
        -webkit-transform: translateX(-31px);
        transform: translateX(-31px);
    }
}

.preloader-inner {
    position: relative;
    width: 142px;
    height: 40px;
    background: #fff;
}

.preloader-inner .dot {
    position: absolute;
    width: 16px;
    height: 16px;
    top: 12px;
    left: 15px;
    background: #4da6e7;
    border-radius: 50%;
    -webkit-transform: translateX(0);
    transform: translateX(0);
    -webkit-animation: dot 2.8s infinite;
    animation: dot 2.8s infinite;
}

.preloader-inner .dots {
    -webkit-transform: translateX(0);
    transform: translateX(0);
    margin-top: 12px;
    margin-left: 31px;
    -webkit-animation: dots 2.8s infinite;
    animation: dots 2.8s infinite;
}

.preloader-inner .dots span {
    display: block;
    float: left;
    width: 16px;
    height: 16px;
    margin-left: 16px;
    background: #4da6e7;
    border-radius: 50%;
}



/* 
---------------------------------------------
Banner Style
--------------------------------------------- 
*/

.main-banner {
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  padding: 226px 0px 120px 0px;
  position: relative;
  overflow: hidden;
}

.main-banner:after {
  content: '';
  background-image: url(../images/slider-left-dec.jpg);
  background-repeat: no-repeat;
  position: absolute;
  left: 0;
  top: 60px;
  width: 262px;
  height: 625px;
  z-index: 1;
}

.main-banner:before {
  content: '';
  background-image: url(../images/slider-right-dec.jpg);
  background-repeat: no-repeat;
  position: absolute;
  right: 0;
  top: 60px;
  width: 1159px;
  height: 797px;
  z-index: -1;
}

.main-banner .left-content {
  margin-right: 15px;
}

.main-banner .left-content h6 {
  text-transform: capitalize;
  font-size: 20px;
  font-weight: 700;
  color: #4da6e7;
  margin-bottom: 15px;
  text-transform: uppercase;
}

.main-banner .left-content h2 {
  z-index: 2;
  position: relative;
  font-weight: 700;
  font-size: 50px;
  color: #2a2a2a;
  margin-bottom: 20px;
}

.main-banner .left-content p {
  margin-bottom: 30px;
  margin-right: 45px;
}

.main-banner .right-image {
  text-align: right;
  position: relative;
  z-index: 20;
}

.main-banner .right-image img {
  max-width: 593px;
}



/* 
---------------------------------------------
About Style
--------------------------------------------- 
*/

#about {
  padding-top: 130px;
}

.about-left-image img {
  margin-right: 45px;
}

.about-right-content p {
  margin-top: 30px;
  margin-bottom: 45px;
}

.skills-content {
  position: relative;
  z-index: 1;
  margin-top: -50px;
  background-color: #f5f5f5;
  border-bottom-right-radius: 50px;
  border-bottom-left-radius: 50px;
  padding: 110px 0px 50px 0px;
}

.skill-item {
  text-align: center;
}

.progress {
  width: 150px;
  height: 150px;
  line-height: 150px;
  background: none;
  margin: 0 auto;
  box-shadow: none;
  position: relative;
}
.progress:after {
  content: "";
  width: 100%;
  height: 100%;
  border-radius: 50%;
  border: 5px solid #fff;
  position: absolute;
  top: 0;
  left: 0;
}
.progress > span {
  width: 50%;
  height: 100%;
  overflow: hidden;
  position: absolute;
  top: 0;
  z-index: 1;
}
.progress .progress-left {
  left: 0;
}
.progress .progress-bar {
  width: 100%;
  height: 100%;
  background: none;
  border-width: 5px;
  border-style: solid;
  position: absolute;
  top: 0;
  border-color: #fd6a54;
}

.first-skill-item .progress .progress-bar {
  border-color: #4da6e7;
}

.second-skill-item .progress .progress-bar {
  border-color: #726ae3;
}

.third-skill-item .progress .progress-bar {
  border-color: #f58b56;
}

.progress .progress-left .progress-bar {
  left: 100%;
  border-top-right-radius: 75px;
  border-bottom-right-radius: 75px;
  border-left: 0;
  -webkit-transform-origin: center left;
  transform-origin: center left;
}
.progress .progress-right {
  right: 0;
}
.progress .progress-right .progress-bar {
  left: -100%;
  border-top-left-radius: 75px;
  border-bottom-left-radius: 75px;
  border-right: 0;
  -webkit-transform-origin: center right;
  transform-origin: center right;
}
.progress .progress-value {
  text-align: center;
  color: #2a2a2a;
  display: flex;
  width: 100%;
  border-radius: 50%;
  font-size: 35px;
  text-align: center;
  line-height: 25px;
  align-items: center;
  justify-content: center;
  height: 100%;
  font-weight: 700;
}
.progress .progress-value div {
  margin-top: 10px;
}
.progress .progress-value span {
  font-size: 18px;
  text-transform: none;
  color: #afafaf;
  font-weight: 300;
}

/* This for loop creates the  necessary css animation names 
Due to the split circle of progress-left and progress right, we must use the animations on each side. 
*/
.progress[data-percentage="10"] .progress-right .progress-bar {
  animation: loading-1 1.5s linear forwards;
}
.progress[data-percentage="10"] .progress-left .progress-bar {
  animation: 0;
}

.progress[data-percentage="20"] .progress-right .progress-bar {
  animation: loading-2 1.5s linear forwards;
}
.progress[data-percentage="20"] .progress-left .progress-bar {
  animation: 0;
}

.progress[data-percentage="30"] .progress-right .progress-bar {
  animation: loading-3 1.5s linear forwards;
}
.progress[data-percentage="30"] .progress-left .progress-bar {
  animation: 0;
}

.progress[data-percentage="40"] .progress-right .progress-bar {
  animation: loading-4 1.5s linear forwards;
}
.progress[data-percentage="40"] .progress-left .progress-bar {
  animation: 0;
}

.progress[data-percentage="50"] .progress-right .progress-bar {
  animation: loading-5 1.5s linear forwards;
}
.progress[data-percentage="50"] .progress-left .progress-bar {
  animation: 0;
}

.progress[data-percentage="60"] .progress-right .progress-bar {
  animation: loading-5 1.5s linear forwards;
}
.progress[data-percentage="60"] .progress-left .progress-bar {
  animation: loading-1 1.5s linear forwards 1.5s;
}

.progress[data-percentage="70"] .progress-right .progress-bar {
  animation: loading-5 1.5s linear forwards;
}
.progress[data-percentage="70"] .progress-left .progress-bar {
  animation: loading-2 1.5s linear forwards 1.5s;
}

.progress[data-percentage="80"] .progress-right .progress-bar {
  animation: loading-5 1.5s linear forwards;
}
.progress[data-percentage="80"] .progress-left .progress-bar {
  animation: loading-3 1.5s linear forwards 1.5s;
}

.progress[data-percentage="90"] .progress-right .progress-bar {
  animation: loading-5 1.5s linear forwards;
}
.progress[data-percentage="90"] .progress-left .progress-bar {
  animation: loading-4 1.5s linear forwards 1.5s;
}

.progress[data-percentage="100"] .progress-right .progress-bar {
  animation: loading-5 1.5s linear forwards;
}
.progress[data-percentage="100"] .progress-left .progress-bar {
  animation: loading-5 1.5s linear forwards 1.5s;
}

@keyframes loading-1 {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(36);
    transform: rotate(36deg);
  }
}
@keyframes loading-2 {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(72);
    transform: rotate(72deg);
  }
}
@keyframes loading-3 {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(108);
    transform: rotate(108deg);
  }
}
@keyframes loading-4 {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(144);
    transform: rotate(144deg);
  }
}
@keyframes loading-5 {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(180);
    transform: rotate(180deg);
  }
}
.progress {
  margin-bottom: 1em;
}

/* 
---------------------------------------------
Services Style
--------------------------------------------- 
*/

.services {
  padding-top: 130px;
  position: relative;
}

.services:after {
  content: '';
  background-image: url(../images/services-left-dec.jpg);
  background-repeat: no-repeat;
  position: absolute;
  left: 0;
  top: 0px;
  width: 786px;
  height: 1217px;
  z-index: 0;
}

.services:before {
  content: '';
  background-image: url(../images/services-right-dec.jpg);
  background-repeat: no-repeat;
  position: absolute;
  right: 0;
  top: 400px;
  width: 161px;
  height: 413px;
  z-index: 0;
}

.services .section-heading {
  text-align: center;
  margin-bottom: 80px;
}

.services .section-heading .line-dec {
  margin: 0 auto;
}

.services .naccs {
  position: relative;
  z-index: 1;
}

.services .icon {
  display: block;
  text-align: center;
  margin: 0 auto;
}

.services .naccs .menu div h4 {
  color: #fff;
  font-size: 15px;
  font-weight: 400;
  width: 100%;
}

.services .icon img {
  margin-bottom: 10px;
  max-width: 60px;
  min-width: 60px;
}

.services .naccs .menu {
  text-align: center;
  margin-bottom: 30px;
}

.services .naccs .menu div {
  color: #2a2a2a;
  margin: 0px;
  width: 15%;
  font-size: 20px;
  font-weight: 700;
  display: inline-block;
  text-align: center;
  cursor: pointer;
  position: relative;
  border-radius: 15px;
  transition: 1s all cubic-bezier(0.075, 0.82, 0.165, 1);
}

.services .naccs .menu div .thumb {
  display: inline-block;
  width: 100%;
  padding: 30px 0px;
  background-color: #fff;
}

.services .naccs .menu div.active {
  box-shadow: 0px 0px 15px rgba(0,0,0,0.1);
}

.services ul.nacc {
  height: 100% !important;
  position: relative;
  min-height: 100%;
  list-style: none;
  margin: 0;
  padding: 0;
  transition: 0.5s all cubic-bezier(0.075, 0.82, 0.165, 1);
}

.services ul.nacc li {
  opacity: 0;
  transform: translateX(-50px);
  position: absolute;
  list-style: none;
  transition: 1s all cubic-bezier(0.075, 0.82, 0.165, 1);
}

.services ul.nacc li.active {
  transition-delay: 0.3s;
  position: relative;
  z-index: 2;
  opacity: 1;
  transform: translateX(0px);
  box-shadow: 0px 0px 15px rgba(0,0,0,0.1);
  background-color: #fff;
  border-radius: 15px;
  padding: 80px 120px 50px 120px;
}

.services ul.nacc li {
  width: 100%;
}

.services ul.nacc li .right-image img {
  max-width: 420px;
  float: right;
}

.services .nacc .thumb h4 {
  color: #2a2a2a;
  font-size: 20px;
  font-weight: 700;
  line-height: 35px;
  margin-bottom: 25px;
}

.services .nacc .thumb .main-white-button {
  text-align: right;
  margin-top: 40px;
}

.services .nacc .thumb .main-white-button a {
  background-color: #8d99af;
  color: #fff;
}

.services .nacc .thumb .main-white-button a i {
  background-color: #fff;
  color: #8d99af;
}

.services .left-text h4 {
  font-size: 20px;
  font-weight: 700;
  color: #4da6e7 !important;
}

.services .left-text p {
  margin-bottom: 30px;
}

.nacc .ticks-list span {
  display: inline-block;
  opacity: 1;
  margin-right: 45px;
  margin-bottom: 20px;
  font-size: 15px;
  font-weight: 400;
}



/* 
---------------------------------------------
Free Quote
--------------------------------------------- 
*/

.free-quote {
  background-image: url(../images/quote-bg-v3.jpg);
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  padding: 120px 0px;
  text-align: center;
  position: relative;
  z-index: 2;
  margin-top: 130px;
}

.free-quote .section-heading {
  margin-bottom: 60px;
}

.free-quote .section-heading h6,
.free-quote .section-heading h4 {
  color: #fff;
}

.free-quote .section-heading .line-dec {
  margin: 0 auto;
  background-color: #fff;
}

.free-quote form {
  background-color: #fff;
  display: inline-block;
  width: 100%;
  min-height: 80px;
  border-radius: 40px;
  position: relative;
  z-index: 1;
}

.free-quote form input {
  width: 100%;
  margin-top: 20px;
  margin-left: 30px;
  color: #afafaf;
  font-weight: 400;
  font-size: 15px;
  height: 40px;
  background-color: transparent;
  border-bottom: 1px solid #eee;
  border-top: none;
  border-left: none;
  border-right: none;
  position: relative;
  z-index: 2;
  outline: none;
}

.free-quote form button {
  width: 100%;
  height: 80px;
  border-top-right-radius: 40px;
  border-bottom-right-radius: 40px;
  outline: none;
  border: none;
  margin-left: 30px;
  background-color: #4da6e7;
  font-size: 15px;
  color: #fff;
}


/* 
---------------------------------------------
Portfolio
--------------------------------------------- 
*/

.our-portfolio {
  padding-top: 130px;
  overflow: hidden;
  position: relative;
}

.our-portfolio:before {
  content: '';
  background-image: url(../images/portfolio-right-dec.jpg);
  background-repeat: no-repeat;
  position: absolute;
  right: 0;
  top: 0px;
  width: 414px;
  height: 861px;
  z-index: 1;
}

.our-portfolio:after {
  content: '';
  background-image: url(../images/portfolio-left-dec.jpg);
  background-repeat: no-repeat;
  position: absolute;
  left: 0;
  top: 0px;
  width: 677px;
  height: 759px;
  z-index: 1;
}

.our-portfolio .section-heading {
  margin-bottom: 80px;
}

.our-portfolio .container-fluid {
  padding-right: 15px;
  padding-left: 15px;
  position: relative;
  z-index: 2;
}

.our-portfolio .item {
  position: relative;
  z-index: 222;
}

.portfolio-item {
  border-radius: 25px;
  box-shadow: 0px 0px 15px rgba(0,0,0,0.1);
  margin: 15px;
}

.portfolio-item .thumb {
  position: relative;
  border-radius: 50px;
}

.portfolio-item:hover .down-content h4,
.portfolio-item:hover .down-content span {
  color: #4da6e7;
}

.portfolio-item .thumb img {
  border-top-right-radius: 23px;
  border-top-left-radius: 23px;
  overflow: hidden;
}

.portfolio-item .down-content {
  background-color: #fff;
  text-align: center;
  padding: 18px 0px;
  border-bottom-right-radius: 23px;
  border-bottom-left-radius: 23px;
}

.portfolio-item .down-content h4 {
  font-size: 20px;
  font-weight: 700;
  color: #2a2a2a;
  margin-bottom: 8px;
  transition: all .3s;
}

.portfolio-item .down-content span {
  font-size: 15px;
  color: #afafaf;
  transition: all .3s;
}

.our-portfolio .owl-nav {
  display: inline-block!important;
  position: absolute;
  top: -125px;
  right: 15%;
  max-width: 1320px;
}

.our-portfolio .owl-nav .owl-next {
  margin-left: 10px;
}

.our-portfolio .owl-nav span {
  width: 46px;
  height: 46px;
  display: inline-block;
  text-align: center;
  line-height: 46px;
  font-size: 30px;
  background-color: #eee;
  border-radius: 50%;
  color: #fff;
  transition: all 0.5s;
}

.our-portfolio .owl-nav span:hover {
  color: #fff;
  background-color: #4da6e7;
}


/* 
---------------------------------------------
Blog
--------------------------------------------- 
*/

.blog:before {
  content: '';
  background-image: url(../images/blog-left-dec.jpg);
  background-repeat: no-repeat;
  position: absolute;
  left: 0;
  top: 0px;
  width: 961px;
  height: 1020px;
  z-index: 0;
}

.blog {
  position: relative;
  padding-top: 130px;
}

.blog .section-heading {
  text-align: center;
  margin-bottom: 80px;
}

.blog .section-heading .line-dec {
  margin: 0 auto;
}

.blog-post {
  box-shadow: 0px 0px 15px rgba(0,0,0,0.1);
  border-radius: 25px;
  position: relative;
  z-index: 2;
}

.show-up {
  position: relative;
  z-index: 222;
}

.blog-post .thumb img {
  border-top-right-radius: 23px;
  border-top-left-radius: 23px;
}

.blog-post .down-content {
  border-bottom-right-radius: 23px;
  border-bottom-left-radius: 23px;
  background-color: #fff;
  padding: 30px;
}

.blog-post .down-content span.category {
  font-size: 15px;
  color: #fff;
  padding: 8px 12px;
  background-color: #4da6e7;
  border-radius: 18px;
  display: inline-block;
}

.blog-post .down-content span.date {
  font-size: 15px;
  color: #afafaf;
  text-align: right;
  float: right;
  margin-top: 4px;
}

.blog-post .down-content h4 {
  font-size: 20px;
  font-weight: 700;
  color: #2a2a2a;
  margin-top: 20px;
  margin-bottom: 20px;
  line-height: 30px;
}

.blog-post .down-content p {
  margin-bottom: 30px;
}

.blog-post .down-content span.author {
  font-size: 15px;
  color: #2a2a2a;
}

.blog-post .down-content span.author img {
  max-width: 56px;
  border-radius: 50%;
  margin-right: 15px;
}

.blog-post .down-content .border-first-button {
  display: inline-block;
  float: right;
}

.blog-posts {
  margin-left: 30px;
}

.post-item {
  margin-bottom: 62px;
}

.last-post-item {
  margin-bottom: 0px;
}

.post-item .thumb {
  display: inline-block;
  float: left;
  margin-right: 30px;
}

.post-item .thumb img {
  border-radius: 23px;
  display: inline-block;
}

.post-item .right-content {
  padding-top: 20px;
}

.post-item .right-content span.category {
  font-size: 15px;
  color: #fff;
  padding: 8px 12px;
  background-color: #4da6e7;
  border-radius: 18px;
  display: inline-block;
}

.post-item .right-content span.date {
  font-size: 15px;
  color: #afafaf;
  text-align: right;
  float: right;
  margin-top: 4px;
}

.post-item .right-content h4 {
  font-size: 20px;
  font-weight: 700;
  color: #2a2a2a;
  margin-top: 20px;
  margin-bottom: 20px;
  line-height: 30px;
}


/* 
---------------------------------------------
contact
--------------------------------------------- 
*/

.contact-us {
  padding-top: 130px;
}

.contact-us .section-heading .line-dec {
  margin: 0 auto;
}

.contact-us .section-heading {
  text-align: center;
  margin-bottom: 80px;
}


form#contact:before {
  background-image: url(../images/contact-top-right-v3.png);
  position: absolute;
  right: 0;
  top: 0;
  width: 726px;
  height: 78px;
  background-repeat: no-repeat;
  content: '';
  z-index: 1;
}

.contact-dec img {
  max-width: 224px;
  position: absolute;
  right: 25px;
  top: -242px;
}

form#contact:after {
  background-image: url(../images/contact-bottom-right-v3.png);
  position: absolute;
  right: 0;
  bottom: 0;
  width: 532px;
  height: 106px;
  background-repeat: no-repeat;
  content: '';
  z-index: 1;
}

form#contact {
  box-shadow: 0px 0px 15px rgba(0,0,0,0.1);
  position: relative;
  background-color: #fff;
  border-radius: 23px;
  text-align: center;
}

form#contact #map iframe {
  border-top-left-radius: 23px;
  border-bottom-left-radius: 23px;
  margin-bottom: -7px;
  position: relative;
  z-index: 2;
}

.fill-form {
  padding: 80px 60px 80px 30px;
}

.fill-form .info-post {
  margin-bottom: 20px;
}

.fill-form .icon {
  text-align: center;
  box-shadow: 0px 0px 15px rgba(0,0,0,0.1);
  border-radius: 23px;
  padding: 25px 15px;
}

.fill-form .icon img {
  max-width: 60px;
  display: block;
  margin: 0 auto;
}

.fill-form .icon a {
  margin-top: 15px;
  display: inline-block;
  font-size: 15px;
  font-weight: 500;
  color: #2a2a2a;
  transition: all .3s;
}

.fill-form .icon:hover a {
  color: #4da6e7;
}

form#contact input {
  width: 100%;
  height: 46px;
  background-color: transparent;
  border: 1px solid #eee;
  outline: none;
  font-size: 15px;
  font-weight: 300;
  color: #2a2a2a;
  padding: 0px 20px;
  border-radius: 23px;
  margin-top: 30px;
}

form#contact input::placeholder {
  color: #aaa;
}

form#contact textarea {
  width: 100%;
  min-width: 100%;
  max-width: 100%;
  max-height: 200px;
  min-height: 200px;
  height: 200px;
  border-radius: 23px;
  background-color: transparent;
  border: 1px solid #eee;
  outline: none;
  font-size: 15px;
  font-weight: 300;
  color: #2a2a2a;
  padding: 15px 20px;
  margin-top: 30px;
}

form#contact textarea::placeholder {
  color: #aaa;
}

form#contact button {
  display: inline-block;
  background-color: #fff;
  font-size: 15px;
  font-weight: 400;
  color: #4da6e7;
  margin-top: 30px;
  width: 100%;
  text-transform: capitalize;
  padding: 12px 25px;
  border-radius: 23px;
  letter-spacing: 0.25px;
  border: 1px solid #4da6e7;
  transition: all .3s;
  outline: none;
}

form#contact button:hover {
  background-color: #4da6e7!important;
  color: #fff!important;
}

/* 
---------------------------------------------
Footer Style
--------------------------------------------- 
*/

footer {
  background-image: url(../images/footer-bg-v3.jpg);
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
  margin-top: 130px;
}

footer p {
  text-align: center;
  margin: 20px 0px;
  color: #fff;
}

footer p a {
  color: #fff;
  transition: all .5s;
}

/* 
---------------------------------------------
responsive
--------------------------------------------- 
*/

@media (max-width: 1200px) {
  .header-area .main-nav .logo h4 {
    font-size: 24px;
  }
  .header-area .main-nav .logo h4 img {
    max-width: 25px;
    margin-left: 0px;
  }
  .header-area .main-nav .nav li:last-child {
    padding-left: 20px;
  }
}

@media (max-width: 992px) {
  form#contact {
    overflow: hidden;
  }
  .header-area .main-nav .logo h4 {
    font-size: 20px;
  }
  .main-banner .left-content {
    margin-right: 0px;
  }
  .main-banner {
    text-align: center;
    padding: 226px 0px 30px 0px;
  }
  .main-banner:before {
    display: none;
  }
  .main-banner .right-image {
    margin: 30px auto 0px auto;
    text-align: center;
  }
  .features-item {
    margin-bottom: 45px;
  }
  .last-features-item,
  .last-skill-item {
    margin-bottom: 0px !important;
  }
  .skill-item {
    margin-bottom: 30px;
  }
  .about-left-image img {
    margin-right: 0px;
    margin-bottom: 45px;;
  }
  .services .naccs .menu div {
    font-size: 15px;
    font-weight: 500;
  }
  .service-item {
    text-align: center;
  }
  .service-item .icon {
    margin-top: 0px;
    margin-bottom: 30px;
  }
  .about-us .left-image {
    margin-right: 30px;
    margin-left: 30px;
    margin-bottom: 45px;
  }
  .blog-posts {
    margin-left: 0px;
    margin-top: 30px;
  }
  .post-item {
    margin-bottom: 70px;
  }
  .our-portfolio .owl-nav {
    display: none !important;
  }
  .contact-info {
    margin-top: 60px;
  }
  form#contact {
    padding: 45px;
  }
}

@media (max-width: 767px) {
  .header-area .main-nav .logo h4 {
    font-size: 30px;
  }
  .header-area .main-nav .logo h4 img {
    max-width: 30px;
    margin-left: 5px;
  }
  .main-banner .info-stat {
    margin-bottom: 15px;
  }
  .service-item {
    text-align: center;
    padding: 30px;
  }
  .service-item .icon {
    float: none;
    margin-right: 0px;
    margin-bottom: 15px;
  }
  .service-item .right-content {
    display: inline-block;
  }
  .services .naccs .menu div .thumb {
    padding: 5px;
  }
  .services .icon img {
    margin: 0px;
  }
  .services ul.nacc li.active {
    padding: 45px;
  }
  .services .naccs .menu div  {
    font-size: 0px;
  }
  .services ul.nacc li .right-image img {
    float: none;
  }
  .our-portfolio .section-heading,
  .about-us .section-heading,
  .about-us .about-item,
  .about-us p,
  .about-us .main-green-button {
    text-align: center;
  }
  .our-portfolio .section-heading .line-dec {
    margin: 0 auto;
  }
  .our-services .section-heading {
    margin-left: 15px;
    margin-right: 15px;
  }
  .free-quote form input {
    margin-left: 0px;
    padding: 0px 30px;
  }
  .free-quote form button {
    margin-left: 0px;
    border-bottom-left-radius: 40px;
    border-top-right-radius: 0px;
  }
  .blog-posts {
    margin-left: 0px;
    margin-top: 30px;
  }
  .post-item {
    margin-bottom: 30px;
  }
  .post-item .thumb img {
    max-width: 140px;
  }
  .post-item .right-content p {
    display: none;
  }
  .about-us .about-item {
    margin-top: 15px;
  }
  form#contact {
    padding: 30px;
  }
}
<?xml version="1.0" standalone="no"?>
<!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd" >
<svg xmlns="http://www.w3.org/2000/svg">
<metadata>
This is a custom SVG font generated by IcoMoon.
<iconset grid="14"></iconset>
</metadata>
<defs>
<font id="flexslider-icon" horiz-adv-x="448" >
<font-face units-per-em="448" ascent="384" descent="-64" />
<missing-glyph horiz-adv-x="448" />
<glyph unicode="&#xf001;" d="M 185.50-9.25l-163.00,162.75q-9.25,9.25 -9.25,22.625t 9.25,22.625l 163.00,162.75q 9.25,9.25 22.625,9.25t 22.625-9.25l 18.75-18.75q 9.25-9.25 9.25-22.625t-9.25-22.625l-121.50-121.50l 121.50-121.25q 9.25-9.50 9.25-22.75t-9.25-22.50l-18.75-18.75q-9.25-9.25 -22.625-9.25t-22.625,9.25z" horiz-adv-x="288"  />
<glyph unicode="&#xf002;" d="M 274.75,176.00q0.00-13.00 -9.25-22.75l-163.00-162.75q-9.25-9.25 -22.50-9.25t-22.50,9.25l-19.00,18.75q-9.25,9.75 -9.25,22.75q0.00,13.25 9.25,22.50l 121.50,121.50l-121.50,121.25q-9.25,9.75 -9.25,22.75q0.00,13.25 9.25,22.50l 19.00,18.75q 9.00,9.50 22.50,9.50t 22.50-9.50l 163.00-162.75q 9.25-9.25 9.25-22.50z" horiz-adv-x="288"  />
<glyph unicode="&#xf003;" d="M 346.00,152.25l-332.00-184.50q-5.75-3.25 -9.875-0.75t-4.125,9.00l0.00,368.00 q0.00,6.50 4.125,9.00t 9.875-0.75l 332.00-184.50q 5.75-3.25 5.75-7.75t-5.75-7.75z" horiz-adv-x="352"  />
<glyph unicode="&#xf004;" d="M 384.00,336.00l0.00-352.00 q0.00-6.50 -4.75-11.25t-11.25-4.75l-128.00,0.00 q-6.50,0.00 -11.25,4.75t-4.75,11.25l0.00,352.00 q0.00,6.50 4.75,11.25t 11.25,4.75l 128.00,0.00 q 6.50,0.00 11.25-4.75t 4.75-11.25zM 160.00,336.00l0.00-352.00 q0.00-6.50 -4.75-11.25t-11.25-4.75l-128.00,0.00 q-6.50,0.00 -11.25,4.75t-4.75,11.25l0.00,352.00 q0.00,6.50 4.75,11.25t 11.25,4.75l 128.00,0.00 q 6.50,0.00 11.25-4.75t 4.75-11.25z" horiz-adv-x="384"  />
<glyph unicode="&#xf005;" d="M 402.75,208.00q0.00-13.25 -9.25-22.50l-162.75-162.75q-9.50-9.50 -22.75-9.50q-13.50,0.00 -22.50,9.50l-162.75,162.75q-9.50,9.00 -9.50,22.50q0.00,13.25 9.50,22.75l 18.50,18.75q 9.75,9.25 22.75,9.25q 13.25,0.00 22.50-9.25l 121.50-121.50l 121.50,121.50q 9.25,9.25 22.50,9.25q 13.00,0.00 22.75-9.25l 18.75-18.75q 9.25-9.75 9.25-22.75z" horiz-adv-x="416"  />
<glyph unicode="&#x20;" horiz-adv-x="224" />
<glyph class="hidden" unicode="&#xf000;" d="M0,384L 448 -64L0 -64 z" horiz-adv-x="0" />
</font></defs></svg>
<?xml version="1.0" standalone="no"?>
<!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd" >
<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1">
<metadata></metadata>
<defs>
<font id="fontawesomeregular" horiz-adv-x="1536" >
<font-face units-per-em="1792" ascent="1536" descent="-256" />
<missing-glyph horiz-adv-x="448" />
<glyph unicode=" "  horiz-adv-x="448" />
<glyph unicode="&#x09;" horiz-adv-x="448" />
<glyph unicode="&#xa0;" horiz-adv-x="448" />
<glyph unicode="&#xa8;" horiz-adv-x="1792" />
<glyph unicode="&#xa9;" horiz-adv-x="1792" />
<glyph unicode="&#xae;" horiz-adv-x="1792" />
<glyph unicode="&#xb4;" horiz-adv-x="1792" />
<glyph unicode="&#xc6;" horiz-adv-x="1792" />
<glyph unicode="&#xd8;" horiz-adv-x="1792" />
<glyph unicode="&#x2000;" horiz-adv-x="768" />
<glyph unicode="&#x2001;" horiz-adv-x="1537" />
<glyph unicode="&#x2002;" horiz-adv-x="768" />
<glyph unicode="&#x2003;" horiz-adv-x="1537" />
<glyph unicode="&#x2004;" horiz-adv-x="512" />
<glyph unicode="&#x2005;" horiz-adv-x="384" />
<glyph unicode="&#x2006;" horiz-adv-x="256" />
<glyph unicode="&#x2007;" horiz-adv-x="256" />
<glyph unicode="&#x2008;" horiz-adv-x="192" />
<glyph unicode="&#x2009;" horiz-adv-x="307" />
<glyph unicode="&#x200a;" horiz-adv-x="85" />
<glyph unicode="&#x202f;" horiz-adv-x="307" />
<glyph unicode="&#x205f;" horiz-adv-x="384" />
<glyph unicode="&#x2122;" horiz-adv-x="1792" />
<glyph unicode="&#x221e;" horiz-adv-x="1792" />
<glyph unicode="&#x2260;" horiz-adv-x="1792" />
<glyph unicode="&#x25fc;" horiz-adv-x="500" d="M0 0z" />
<glyph unicode="&#xf000;" horiz-adv-x="1792" d="M1699 1350q0 -35 -43 -78l-632 -632v-768h320q26 0 45 -19t19 -45t-19 -45t-45 -19h-896q-26 0 -45 19t-19 45t19 45t45 19h320v768l-632 632q-43 43 -43 78q0 23 18 36.5t38 17.5t43 4h1408q23 0 43 -4t38 -17.5t18 -36.5z" />
<glyph unicode="&#xf001;" d="M1536 1312v-1120q0 -50 -34 -89t-86 -60.5t-103.5 -32t-96.5 -10.5t-96.5 10.5t-103.5 32t-86 60.5t-34 89t34 89t86 60.5t103.5 32t96.5 10.5q105 0 192 -39v537l-768 -237v-709q0 -50 -34 -89t-86 -60.5t-103.5 -32t-96.5 -10.5t-96.5 10.5t-103.5 32t-86 60.5t-34 89 t34 89t86 60.5t103.5 32t96.5 10.5q105 0 192 -39v967q0 31 19 56.5t49 35.5l832 256q12 4 28 4q40 0 68 -28t28 -68z" />
<glyph unicode="&#xf002;" horiz-adv-x="1664" d="M1152 704q0 185 -131.5 316.5t-316.5 131.5t-316.5 -131.5t-131.5 -316.5t131.5 -316.5t316.5 -131.5t316.5 131.5t131.5 316.5zM1664 -128q0 -52 -38 -90t-90 -38q-54 0 -90 38l-343 342q-179 -124 -399 -124q-143 0 -273.5 55.5t-225 150t-150 225t-55.5 273.5 t55.5 273.5t150 225t225 150t273.5 55.5t273.5 -55.5t225 -150t150 -225t55.5 -273.5q0 -220 -124 -399l343 -343q37 -37 37 -90z" />
<glyph unicode="&#xf003;" horiz-adv-x="1792" d="M1664 32v768q-32 -36 -69 -66q-268 -206 -426 -338q-51 -43 -83 -67t-86.5 -48.5t-102.5 -24.5h-1h-1q-48 0 -102.5 24.5t-86.5 48.5t-83 67q-158 132 -426 338q-37 30 -69 66v-768q0 -13 9.5 -22.5t22.5 -9.5h1472q13 0 22.5 9.5t9.5 22.5zM1664 1083v11v13.5t-0.5 13 t-3 12.5t-5.5 9t-9 7.5t-14 2.5h-1472q-13 0 -22.5 -9.5t-9.5 -22.5q0 -168 147 -284q193 -152 401 -317q6 -5 35 -29.5t46 -37.5t44.5 -31.5t50.5 -27.5t43 -9h1h1q20 0 43 9t50.5 27.5t44.5 31.5t46 37.5t35 29.5q208 165 401 317q54 43 100.5 115.5t46.5 131.5z M1792 1120v-1088q0 -66 -47 -113t-113 -47h-1472q-66 0 -113 47t-47 113v1088q0 66 47 113t113 47h1472q66 0 113 -47t47 -113z" />
<glyph unicode="&#xf004;" horiz-adv-x="1792" d="M896 -128q-26 0 -44 18l-624 602q-10 8 -27.5 26t-55.5 65.5t-68 97.5t-53.5 121t-23.5 138q0 220 127 344t351 124q62 0 126.5 -21.5t120 -58t95.5 -68.5t76 -68q36 36 76 68t95.5 68.5t120 58t126.5 21.5q224 0 351 -124t127 -344q0 -221 -229 -450l-623 -600 q-18 -18 -44 -18z" />
<glyph unicode="&#xf005;" horiz-adv-x="1664" d="M1664 889q0 -22 -26 -48l-363 -354l86 -500q1 -7 1 -20q0 -21 -10.5 -35.5t-30.5 -14.5q-19 0 -40 12l-449 236l-449 -236q-22 -12 -40 -12q-21 0 -31.5 14.5t-10.5 35.5q0 6 2 20l86 500l-364 354q-25 27 -25 48q0 37 56 46l502 73l225 455q19 41 49 41t49 -41l225 -455 l502 -73q56 -9 56 -46z" />
<glyph unicode="&#xf006;" horiz-adv-x="1664" d="M1137 532l306 297l-422 62l-189 382l-189 -382l-422 -62l306 -297l-73 -421l378 199l377 -199zM1664 889q0 -22 -26 -48l-363 -354l86 -500q1 -7 1 -20q0 -50 -41 -50q-19 0 -40 12l-449 236l-449 -236q-22 -12 -40 -12q-21 0 -31.5 14.5t-10.5 35.5q0 6 2 20l86 500 l-364 354q-25 27 -25 48q0 37 56 46l502 73l225 455q19 41 49 41t49 -41l225 -455l502 -73q56 -9 56 -46z" />
<glyph unicode="&#xf007;" horiz-adv-x="1408" d="M1408 131q0 -120 -73 -189.5t-194 -69.5h-874q-121 0 -194 69.5t-73 189.5q0 53 3.5 103.5t14 109t26.5 108.5t43 97.5t62 81t85.5 53.5t111.5 20q9 0 42 -21.5t74.5 -48t108 -48t133.5 -21.5t133.5 21.5t108 48t74.5 48t42 21.5q61 0 111.5 -20t85.5 -53.5t62 -81 t43 -97.5t26.5 -108.5t14 -109t3.5 -103.5zM1088 1024q0 -159 -112.5 -271.5t-271.5 -112.5t-271.5 112.5t-112.5 271.5t112.5 271.5t271.5 112.5t271.5 -112.5t112.5 -271.5z" />
<glyph unicode="&#xf008;" horiz-adv-x="1920" d="M384 -64v128q0 26 -19 45t-45 19h-128q-26 0 -45 -19t-19 -45v-128q0 -26 19 -45t45 -19h128q26 0 45 19t19 45zM384 320v128q0 26 -19 45t-45 19h-128q-26 0 -45 -19t-19 -45v-128q0 -26 19 -45t45 -19h128q26 0 45 19t19 45zM384 704v128q0 26 -19 45t-45 19h-128 q-26 0 -45 -19t-19 -45v-128q0 -26 19 -45t45 -19h128q26 0 45 19t19 45zM1408 -64v512q0 26 -19 45t-45 19h-768q-26 0 -45 -19t-19 -45v-512q0 -26 19 -45t45 -19h768q26 0 45 19t19 45zM384 1088v128q0 26 -19 45t-45 19h-128q-26 0 -45 -19t-19 -45v-128q0 -26 19 -45 t45 -19h128q26 0 45 19t19 45zM1792 -64v128q0 26 -19 45t-45 19h-128q-26 0 -45 -19t-19 -45v-128q0 -26 19 -45t45 -19h128q26 0 45 19t19 45zM1408 704v512q0 26 -19 45t-45 19h-768q-26 0 -45 -19t-19 -45v-512q0 -26 19 -45t45 -19h768q26 0 45 19t19 45zM1792 320v128 q0 26 -19 45t-45 19h-128q-26 0 -45 -19t-19 -45v-128q0 -26 19 -45t45 -19h128q26 0 45 19t19 45zM1792 704v128q0 26 -19 45t-45 19h-128q-26 0 -45 -19t-19 -45v-128q0 -26 19 -45t45 -19h128q26 0 45 19t19 45zM1792 1088v128q0 26 -19 45t-45 19h-128q-26 0 -45 -19 t-19 -45v-128q0 -26 19 -45t45 -19h128q26 0 45 19t19 45zM1920 1248v-1344q0 -66 -47 -113t-113 -47h-1600q-66 0 -113 47t-47 113v1344q0 66 47 113t113 47h1600q66 0 113 -47t47 -113z" />
<glyph unicode="&#xf009;" horiz-adv-x="1664" d="M768 512v-384q0 -52 -38 -90t-90 -38h-512q-52 0 -90 38t-38 90v384q0 52 38 90t90 38h512q52 0 90 -38t38 -90zM768 1280v-384q0 -52 -38 -90t-90 -38h-512q-52 0 -90 38t-38 90v384q0 52 38 90t90 38h512q52 0 90 -38t38 -90zM1664 512v-384q0 -52 -38 -90t-90 -38 h-512q-52 0 -90 38t-38 90v384q0 52 38 90t90 38h512q52 0 90 -38t38 -90zM1664 1280v-384q0 -52 -38 -90t-90 -38h-512q-52 0 -90 38t-38 90v384q0 52 38 90t90 38h512q52 0 90 -38t38 -90z" />
<glyph unicode="&#xf00a;" horiz-adv-x="1792" d="M512 288v-192q0 -40 -28 -68t-68 -28h-320q-40 0 -68 28t-28 68v192q0 40 28 68t68 28h320q40 0 68 -28t28 -68zM512 800v-192q0 -40 -28 -68t-68 -28h-320q-40 0 -68 28t-28 68v192q0 40 28 68t68 28h320q40 0 68 -28t28 -68zM1152 288v-192q0 -40 -28 -68t-68 -28h-320 q-40 0 -68 28t-28 68v192q0 40 28 68t68 28h320q40 0 68 -28t28 -68zM512 1312v-192q0 -40 -28 -68t-68 -28h-320q-40 0 -68 28t-28 68v192q0 40 28 68t68 28h320q40 0 68 -28t28 -68zM1152 800v-192q0 -40 -28 -68t-68 -28h-320q-40 0 -68 28t-28 68v192q0 40 28 68t68 28 h320q40 0 68 -28t28 -68zM1792 288v-192q0 -40 -28 -68t-68 -28h-320q-40 0 -68 28t-28 68v192q0 40 28 68t68 28h320q40 0 68 -28t28 -68zM1152 1312v-192q0 -40 -28 -68t-68 -28h-320q-40 0 -68 28t-28 68v192q0 40 28 68t68 28h320q40 0 68 -28t28 -68zM1792 800v-192 q0 -40 -28 -68t-68 -28h-320q-40 0 -68 28t-28 68v192q0 40 28 68t68 28h320q40 0 68 -28t28 -68zM1792 1312v-192q0 -40 -28 -68t-68 -28h-320q-40 0 -68 28t-28 68v192q0 40 28 68t68 28h320q40 0 68 -28t28 -68z" />
<glyph unicode="&#xf00b;" horiz-adv-x="1792" d="M512 288v-192q0 -40 -28 -68t-68 -28h-320q-40 0 -68 28t-28 68v192q0 40 28 68t68 28h320q40 0 68 -28t28 -68zM512 800v-192q0 -40 -28 -68t-68 -28h-320q-40 0 -68 28t-28 68v192q0 40 28 68t68 28h320q40 0 68 -28t28 -68zM1792 288v-192q0 -40 -28 -68t-68 -28h-960 q-40 0 -68 28t-28 68v192q0 40 28 68t68 28h960q40 0 68 -28t28 -68zM512 1312v-192q0 -40 -28 -68t-68 -28h-320q-40 0 -68 28t-28 68v192q0 40 28 68t68 28h320q40 0 68 -28t28 -68zM1792 800v-192q0 -40 -28 -68t-68 -28h-960q-40 0 -68 28t-28 68v192q0 40 28 68t68 28 h960q40 0 68 -28t28 -68zM1792 1312v-192q0 -40 -28 -68t-68 -28h-960q-40 0 -68 28t-28 68v192q0 40 28 68t68 28h960q40 0 68 -28t28 -68z" />
<glyph unicode="&#xf00c;" horiz-adv-x="1792" d="M1671 970q0 -40 -28 -68l-724 -724l-136 -136q-28 -28 -68 -28t-68 28l-136 136l-362 362q-28 28 -28 68t28 68l136 136q28 28 68 28t68 -28l294 -295l656 657q28 28 68 28t68 -28l136 -136q28 -28 28 -68z" />
<glyph unicode="&#xf00d;" horiz-adv-x="1408" d="M1298 214q0 -40 -28 -68l-136 -136q-28 -28 -68 -28t-68 28l-294 294l-294 -294q-28 -28 -68 -28t-68 28l-136 136q-28 28 -28 68t28 68l294 294l-294 294q-28 28 -28 68t28 68l136 136q28 28 68 28t68 -28l294 -294l294 294q28 28 68 28t68 -28l136 -136q28 -28 28 -68 t-28 -68l-294 -294l294 -294q28 -28 28 -68z" />
<glyph unicode="&#xf00e;" horiz-adv-x="1664" d="M1024 736v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-224v-224q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v224h-224q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h224v224q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5v-224h224 q13 0 22.5 -9.5t9.5 -22.5zM1152 704q0 185 -131.5 316.5t-316.5 131.5t-316.5 -131.5t-131.5 -316.5t131.5 -316.5t316.5 -131.5t316.5 131.5t131.5 316.5zM1664 -128q0 -53 -37.5 -90.5t-90.5 -37.5q-54 0 -90 38l-343 342q-179 -124 -399 -124q-143 0 -273.5 55.5 t-225 150t-150 225t-55.5 273.5t55.5 273.5t150 225t225 150t273.5 55.5t273.5 -55.5t225 -150t150 -225t55.5 -273.5q0 -220 -124 -399l343 -343q37 -37 37 -90z" />
<glyph unicode="&#xf010;" horiz-adv-x="1664" d="M1024 736v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-576q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h576q13 0 22.5 -9.5t9.5 -22.5zM1152 704q0 185 -131.5 316.5t-316.5 131.5t-316.5 -131.5t-131.5 -316.5t131.5 -316.5t316.5 -131.5t316.5 131.5t131.5 316.5z M1664 -128q0 -53 -37.5 -90.5t-90.5 -37.5q-54 0 -90 38l-343 342q-179 -124 -399 -124q-143 0 -273.5 55.5t-225 150t-150 225t-55.5 273.5t55.5 273.5t150 225t225 150t273.5 55.5t273.5 -55.5t225 -150t150 -225t55.5 -273.5q0 -220 -124 -399l343 -343q37 -37 37 -90z " />
<glyph unicode="&#xf011;" d="M1536 640q0 -156 -61 -298t-164 -245t-245 -164t-298 -61t-298 61t-245 164t-164 245t-61 298q0 182 80.5 343t226.5 270q43 32 95.5 25t83.5 -50q32 -42 24.5 -94.5t-49.5 -84.5q-98 -74 -151.5 -181t-53.5 -228q0 -104 40.5 -198.5t109.5 -163.5t163.5 -109.5 t198.5 -40.5t198.5 40.5t163.5 109.5t109.5 163.5t40.5 198.5q0 121 -53.5 228t-151.5 181q-42 32 -49.5 84.5t24.5 94.5q31 43 84 50t95 -25q146 -109 226.5 -270t80.5 -343zM896 1408v-640q0 -52 -38 -90t-90 -38t-90 38t-38 90v640q0 52 38 90t90 38t90 -38t38 -90z" />
<glyph unicode="&#xf012;" horiz-adv-x="1792" d="M256 96v-192q0 -14 -9 -23t-23 -9h-192q-14 0 -23 9t-9 23v192q0 14 9 23t23 9h192q14 0 23 -9t9 -23zM640 224v-320q0 -14 -9 -23t-23 -9h-192q-14 0 -23 9t-9 23v320q0 14 9 23t23 9h192q14 0 23 -9t9 -23zM1024 480v-576q0 -14 -9 -23t-23 -9h-192q-14 0 -23 9t-9 23 v576q0 14 9 23t23 9h192q14 0 23 -9t9 -23zM1408 864v-960q0 -14 -9 -23t-23 -9h-192q-14 0 -23 9t-9 23v960q0 14 9 23t23 9h192q14 0 23 -9t9 -23zM1792 1376v-1472q0 -14 -9 -23t-23 -9h-192q-14 0 -23 9t-9 23v1472q0 14 9 23t23 9h192q14 0 23 -9t9 -23z" />
<glyph unicode="&#xf013;" d="M1024 640q0 106 -75 181t-181 75t-181 -75t-75 -181t75 -181t181 -75t181 75t75 181zM1536 749v-222q0 -12 -8 -23t-20 -13l-185 -28q-19 -54 -39 -91q35 -50 107 -138q10 -12 10 -25t-9 -23q-27 -37 -99 -108t-94 -71q-12 0 -26 9l-138 108q-44 -23 -91 -38 q-16 -136 -29 -186q-7 -28 -36 -28h-222q-14 0 -24.5 8.5t-11.5 21.5l-28 184q-49 16 -90 37l-141 -107q-10 -9 -25 -9q-14 0 -25 11q-126 114 -165 168q-7 10 -7 23q0 12 8 23q15 21 51 66.5t54 70.5q-27 50 -41 99l-183 27q-13 2 -21 12.5t-8 23.5v222q0 12 8 23t19 13 l186 28q14 46 39 92q-40 57 -107 138q-10 12 -10 24q0 10 9 23q26 36 98.5 107.5t94.5 71.5q13 0 26 -10l138 -107q44 23 91 38q16 136 29 186q7 28 36 28h222q14 0 24.5 -8.5t11.5 -21.5l28 -184q49 -16 90 -37l142 107q9 9 24 9q13 0 25 -10q129 -119 165 -170q7 -8 7 -22 q0 -12 -8 -23q-15 -21 -51 -66.5t-54 -70.5q26 -50 41 -98l183 -28q13 -2 21 -12.5t8 -23.5z" />
<glyph unicode="&#xf014;" horiz-adv-x="1408" d="M512 800v-576q0 -14 -9 -23t-23 -9h-64q-14 0 -23 9t-9 23v576q0 14 9 23t23 9h64q14 0 23 -9t9 -23zM768 800v-576q0 -14 -9 -23t-23 -9h-64q-14 0 -23 9t-9 23v576q0 14 9 23t23 9h64q14 0 23 -9t9 -23zM1024 800v-576q0 -14 -9 -23t-23 -9h-64q-14 0 -23 9t-9 23v576 q0 14 9 23t23 9h64q14 0 23 -9t9 -23zM1152 76v948h-896v-948q0 -22 7 -40.5t14.5 -27t10.5 -8.5h832q3 0 10.5 8.5t14.5 27t7 40.5zM480 1152h448l-48 117q-7 9 -17 11h-317q-10 -2 -17 -11zM1408 1120v-64q0 -14 -9 -23t-23 -9h-96v-948q0 -83 -47 -143.5t-113 -60.5h-832 q-66 0 -113 58.5t-47 141.5v952h-96q-14 0 -23 9t-9 23v64q0 14 9 23t23 9h309l70 167q15 37 54 63t79 26h320q40 0 79 -26t54 -63l70 -167h309q14 0 23 -9t9 -23z" />
<glyph unicode="&#xf015;" horiz-adv-x="1664" d="M1408 544v-480q0 -26 -19 -45t-45 -19h-384v384h-256v-384h-384q-26 0 -45 19t-19 45v480q0 1 0.5 3t0.5 3l575 474l575 -474q1 -2 1 -6zM1631 613l-62 -74q-8 -9 -21 -11h-3q-13 0 -21 7l-692 577l-692 -577q-12 -8 -24 -7q-13 2 -21 11l-62 74q-8 10 -7 23.5t11 21.5 l719 599q32 26 76 26t76 -26l244 -204v195q0 14 9 23t23 9h192q14 0 23 -9t9 -23v-408l219 -182q10 -8 11 -21.5t-7 -23.5z" />
<glyph unicode="&#xf016;" d="M1468 1156q28 -28 48 -76t20 -88v-1152q0 -40 -28 -68t-68 -28h-1344q-40 0 -68 28t-28 68v1600q0 40 28 68t68 28h896q40 0 88 -20t76 -48zM1024 1400v-376h376q-10 29 -22 41l-313 313q-12 12 -41 22zM1408 -128v1024h-416q-40 0 -68 28t-28 68v416h-768v-1536h1280z " />
<glyph unicode="&#xf017;" d="M896 992v-448q0 -14 -9 -23t-23 -9h-320q-14 0 -23 9t-9 23v64q0 14 9 23t23 9h224v352q0 14 9 23t23 9h64q14 0 23 -9t9 -23zM1312 640q0 148 -73 273t-198 198t-273 73t-273 -73t-198 -198t-73 -273t73 -273t198 -198t273 -73t273 73t198 198t73 273zM1536 640 q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf018;" horiz-adv-x="1920" d="M1111 540v4l-24 320q-1 13 -11 22.5t-23 9.5h-186q-13 0 -23 -9.5t-11 -22.5l-24 -320v-4q-1 -12 8 -20t21 -8h244q12 0 21 8t8 20zM1870 73q0 -73 -46 -73h-704q13 0 22 9.5t8 22.5l-20 256q-1 13 -11 22.5t-23 9.5h-272q-13 0 -23 -9.5t-11 -22.5l-20 -256 q-1 -13 8 -22.5t22 -9.5h-704q-46 0 -46 73q0 54 26 116l417 1044q8 19 26 33t38 14h339q-13 0 -23 -9.5t-11 -22.5l-15 -192q-1 -14 8 -23t22 -9h166q13 0 22 9t8 23l-15 192q-1 13 -11 22.5t-23 9.5h339q20 0 38 -14t26 -33l417 -1044q26 -62 26 -116z" />
<glyph unicode="&#xf019;" horiz-adv-x="1664" d="M1280 192q0 26 -19 45t-45 19t-45 -19t-19 -45t19 -45t45 -19t45 19t19 45zM1536 192q0 26 -19 45t-45 19t-45 -19t-19 -45t19 -45t45 -19t45 19t19 45zM1664 416v-320q0 -40 -28 -68t-68 -28h-1472q-40 0 -68 28t-28 68v320q0 40 28 68t68 28h465l135 -136 q58 -56 136 -56t136 56l136 136h464q40 0 68 -28t28 -68zM1339 985q17 -41 -14 -70l-448 -448q-18 -19 -45 -19t-45 19l-448 448q-31 29 -14 70q17 39 59 39h256v448q0 26 19 45t45 19h256q26 0 45 -19t19 -45v-448h256q42 0 59 -39z" />
<glyph unicode="&#xf01a;" d="M1120 608q0 -12 -10 -24l-319 -319q-11 -9 -23 -9t-23 9l-320 320q-15 16 -7 35q8 20 30 20h192v352q0 14 9 23t23 9h192q14 0 23 -9t9 -23v-352h192q14 0 23 -9t9 -23zM768 1184q-148 0 -273 -73t-198 -198t-73 -273t73 -273t198 -198t273 -73t273 73t198 198t73 273 t-73 273t-198 198t-273 73zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf01b;" d="M1118 660q-8 -20 -30 -20h-192v-352q0 -14 -9 -23t-23 -9h-192q-14 0 -23 9t-9 23v352h-192q-14 0 -23 9t-9 23q0 12 10 24l319 319q11 9 23 9t23 -9l320 -320q15 -16 7 -35zM768 1184q-148 0 -273 -73t-198 -198t-73 -273t73 -273t198 -198t273 -73t273 73t198 198 t73 273t-73 273t-198 198t-273 73zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf01c;" d="M1023 576h316q-1 3 -2.5 8t-2.5 8l-212 496h-708l-212 -496q-1 -2 -2.5 -8t-2.5 -8h316l95 -192h320zM1536 546v-482q0 -26 -19 -45t-45 -19h-1408q-26 0 -45 19t-19 45v482q0 62 25 123l238 552q10 25 36.5 42t52.5 17h832q26 0 52.5 -17t36.5 -42l238 -552 q25 -61 25 -123z" />
<glyph unicode="&#xf01d;" d="M1184 640q0 -37 -32 -55l-544 -320q-15 -9 -32 -9q-16 0 -32 8q-32 19 -32 56v640q0 37 32 56q33 18 64 -1l544 -320q32 -18 32 -55zM1312 640q0 148 -73 273t-198 198t-273 73t-273 -73t-198 -198t-73 -273t73 -273t198 -198t273 -73t273 73t198 198t73 273zM1536 640 q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf01e;" d="M1536 1280v-448q0 -26 -19 -45t-45 -19h-448q-42 0 -59 40q-17 39 14 69l138 138q-148 137 -349 137q-104 0 -198.5 -40.5t-163.5 -109.5t-109.5 -163.5t-40.5 -198.5t40.5 -198.5t109.5 -163.5t163.5 -109.5t198.5 -40.5q119 0 225 52t179 147q7 10 23 12q14 0 25 -9 l137 -138q9 -8 9.5 -20.5t-7.5 -22.5q-109 -132 -264 -204.5t-327 -72.5q-156 0 -298 61t-245 164t-164 245t-61 298t61 298t164 245t245 164t298 61q147 0 284.5 -55.5t244.5 -156.5l130 129q29 31 70 14q39 -17 39 -59z" />
<glyph unicode="&#xf021;" d="M1511 480q0 -5 -1 -7q-64 -268 -268 -434.5t-478 -166.5q-146 0 -282.5 55t-243.5 157l-129 -129q-19 -19 -45 -19t-45 19t-19 45v448q0 26 19 45t45 19h448q26 0 45 -19t19 -45t-19 -45l-137 -137q71 -66 161 -102t187 -36q134 0 250 65t186 179q11 17 53 117 q8 23 30 23h192q13 0 22.5 -9.5t9.5 -22.5zM1536 1280v-448q0 -26 -19 -45t-45 -19h-448q-26 0 -45 19t-19 45t19 45l138 138q-148 137 -349 137q-134 0 -250 -65t-186 -179q-11 -17 -53 -117q-8 -23 -30 -23h-199q-13 0 -22.5 9.5t-9.5 22.5v7q65 268 270 434.5t480 166.5 q146 0 284 -55.5t245 -156.5l130 129q19 19 45 19t45 -19t19 -45z" />
<glyph unicode="&#xf022;" horiz-adv-x="1792" d="M384 352v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5zM384 608v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5z M384 864v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5zM1536 352v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-960q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h960q13 0 22.5 -9.5t9.5 -22.5z M1536 608v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-960q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h960q13 0 22.5 -9.5t9.5 -22.5zM1536 864v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-960q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h960q13 0 22.5 -9.5 t9.5 -22.5zM1664 160v832q0 13 -9.5 22.5t-22.5 9.5h-1472q-13 0 -22.5 -9.5t-9.5 -22.5v-832q0 -13 9.5 -22.5t22.5 -9.5h1472q13 0 22.5 9.5t9.5 22.5zM1792 1248v-1088q0 -66 -47 -113t-113 -47h-1472q-66 0 -113 47t-47 113v1088q0 66 47 113t113 47h1472q66 0 113 -47 t47 -113z" />
<glyph unicode="&#xf023;" horiz-adv-x="1152" d="M320 768h512v192q0 106 -75 181t-181 75t-181 -75t-75 -181v-192zM1152 672v-576q0 -40 -28 -68t-68 -28h-960q-40 0 -68 28t-28 68v576q0 40 28 68t68 28h32v192q0 184 132 316t316 132t316 -132t132 -316v-192h32q40 0 68 -28t28 -68z" />
<glyph unicode="&#xf024;" horiz-adv-x="1792" d="M320 1280q0 -72 -64 -110v-1266q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v1266q-64 38 -64 110q0 53 37.5 90.5t90.5 37.5t90.5 -37.5t37.5 -90.5zM1792 1216v-763q0 -25 -12.5 -38.5t-39.5 -27.5q-215 -116 -369 -116q-61 0 -123.5 22t-108.5 48 t-115.5 48t-142.5 22q-192 0 -464 -146q-17 -9 -33 -9q-26 0 -45 19t-19 45v742q0 32 31 55q21 14 79 43q236 120 421 120q107 0 200 -29t219 -88q38 -19 88 -19q54 0 117.5 21t110 47t88 47t54.5 21q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf025;" horiz-adv-x="1664" d="M1664 650q0 -166 -60 -314l-20 -49l-185 -33q-22 -83 -90.5 -136.5t-156.5 -53.5v-32q0 -14 -9 -23t-23 -9h-64q-14 0 -23 9t-9 23v576q0 14 9 23t23 9h64q14 0 23 -9t9 -23v-32q71 0 130 -35.5t93 -95.5l68 12q29 95 29 193q0 148 -88 279t-236.5 209t-315.5 78 t-315.5 -78t-236.5 -209t-88 -279q0 -98 29 -193l68 -12q34 60 93 95.5t130 35.5v32q0 14 9 23t23 9h64q14 0 23 -9t9 -23v-576q0 -14 -9 -23t-23 -9h-64q-14 0 -23 9t-9 23v32q-88 0 -156.5 53.5t-90.5 136.5l-185 33l-20 49q-60 148 -60 314q0 151 67 291t179 242.5 t266 163.5t320 61t320 -61t266 -163.5t179 -242.5t67 -291z" />
<glyph unicode="&#xf026;" horiz-adv-x="768" d="M768 1184v-1088q0 -26 -19 -45t-45 -19t-45 19l-333 333h-262q-26 0 -45 19t-19 45v384q0 26 19 45t45 19h262l333 333q19 19 45 19t45 -19t19 -45z" />
<glyph unicode="&#xf027;" horiz-adv-x="1152" d="M768 1184v-1088q0 -26 -19 -45t-45 -19t-45 19l-333 333h-262q-26 0 -45 19t-19 45v384q0 26 19 45t45 19h262l333 333q19 19 45 19t45 -19t19 -45zM1152 640q0 -76 -42.5 -141.5t-112.5 -93.5q-10 -5 -25 -5q-26 0 -45 18.5t-19 45.5q0 21 12 35.5t29 25t34 23t29 35.5 t12 57t-12 57t-29 35.5t-34 23t-29 25t-12 35.5q0 27 19 45.5t45 18.5q15 0 25 -5q70 -27 112.5 -93t42.5 -142z" />
<glyph unicode="&#xf028;" horiz-adv-x="1664" d="M768 1184v-1088q0 -26 -19 -45t-45 -19t-45 19l-333 333h-262q-26 0 -45 19t-19 45v384q0 26 19 45t45 19h262l333 333q19 19 45 19t45 -19t19 -45zM1152 640q0 -76 -42.5 -141.5t-112.5 -93.5q-10 -5 -25 -5q-26 0 -45 18.5t-19 45.5q0 21 12 35.5t29 25t34 23t29 35.5 t12 57t-12 57t-29 35.5t-34 23t-29 25t-12 35.5q0 27 19 45.5t45 18.5q15 0 25 -5q70 -27 112.5 -93t42.5 -142zM1408 640q0 -153 -85 -282.5t-225 -188.5q-13 -5 -25 -5q-27 0 -46 19t-19 45q0 39 39 59q56 29 76 44q74 54 115.5 135.5t41.5 173.5t-41.5 173.5 t-115.5 135.5q-20 15 -76 44q-39 20 -39 59q0 26 19 45t45 19q13 0 26 -5q140 -59 225 -188.5t85 -282.5zM1664 640q0 -230 -127 -422.5t-338 -283.5q-13 -5 -26 -5q-26 0 -45 19t-19 45q0 36 39 59q7 4 22.5 10.5t22.5 10.5q46 25 82 51q123 91 192 227t69 289t-69 289 t-192 227q-36 26 -82 51q-7 4 -22.5 10.5t-22.5 10.5q-39 23 -39 59q0 26 19 45t45 19q13 0 26 -5q211 -91 338 -283.5t127 -422.5z" />
<glyph unicode="&#xf029;" horiz-adv-x="1408" d="M384 384v-128h-128v128h128zM384 1152v-128h-128v128h128zM1152 1152v-128h-128v128h128zM128 129h384v383h-384v-383zM128 896h384v384h-384v-384zM896 896h384v384h-384v-384zM640 640v-640h-640v640h640zM1152 128v-128h-128v128h128zM1408 128v-128h-128v128h128z M1408 640v-384h-384v128h-128v-384h-128v640h384v-128h128v128h128zM640 1408v-640h-640v640h640zM1408 1408v-640h-640v640h640z" />
<glyph unicode="&#xf02a;" horiz-adv-x="1792" d="M63 0h-63v1408h63v-1408zM126 1h-32v1407h32v-1407zM220 1h-31v1407h31v-1407zM377 1h-31v1407h31v-1407zM534 1h-62v1407h62v-1407zM660 1h-31v1407h31v-1407zM723 1h-31v1407h31v-1407zM786 1h-31v1407h31v-1407zM943 1h-63v1407h63v-1407zM1100 1h-63v1407h63v-1407z M1226 1h-63v1407h63v-1407zM1352 1h-63v1407h63v-1407zM1446 1h-63v1407h63v-1407zM1635 1h-94v1407h94v-1407zM1698 1h-32v1407h32v-1407zM1792 0h-63v1408h63v-1408z" />
<glyph unicode="&#xf02b;" d="M448 1088q0 53 -37.5 90.5t-90.5 37.5t-90.5 -37.5t-37.5 -90.5t37.5 -90.5t90.5 -37.5t90.5 37.5t37.5 90.5zM1515 512q0 -53 -37 -90l-491 -492q-39 -37 -91 -37q-53 0 -90 37l-715 716q-38 37 -64.5 101t-26.5 117v416q0 52 38 90t90 38h416q53 0 117 -26.5t102 -64.5 l715 -714q37 -39 37 -91z" />
<glyph unicode="&#xf02c;" horiz-adv-x="1920" d="M448 1088q0 53 -37.5 90.5t-90.5 37.5t-90.5 -37.5t-37.5 -90.5t37.5 -90.5t90.5 -37.5t90.5 37.5t37.5 90.5zM1515 512q0 -53 -37 -90l-491 -492q-39 -37 -91 -37q-53 0 -90 37l-715 716q-38 37 -64.5 101t-26.5 117v416q0 52 38 90t90 38h416q53 0 117 -26.5t102 -64.5 l715 -714q37 -39 37 -91zM1899 512q0 -53 -37 -90l-491 -492q-39 -37 -91 -37q-36 0 -59 14t-53 45l470 470q37 37 37 90q0 52 -37 91l-715 714q-38 38 -102 64.5t-117 26.5h224q53 0 117 -26.5t102 -64.5l715 -714q37 -39 37 -91z" />
<glyph unicode="&#xf02d;" horiz-adv-x="1664" d="M1639 1058q40 -57 18 -129l-275 -906q-19 -64 -76.5 -107.5t-122.5 -43.5h-923q-77 0 -148.5 53.5t-99.5 131.5q-24 67 -2 127q0 4 3 27t4 37q1 8 -3 21.5t-3 19.5q2 11 8 21t16.5 23.5t16.5 23.5q23 38 45 91.5t30 91.5q3 10 0.5 30t-0.5 28q3 11 17 28t17 23 q21 36 42 92t25 90q1 9 -2.5 32t0.5 28q4 13 22 30.5t22 22.5q19 26 42.5 84.5t27.5 96.5q1 8 -3 25.5t-2 26.5q2 8 9 18t18 23t17 21q8 12 16.5 30.5t15 35t16 36t19.5 32t26.5 23.5t36 11.5t47.5 -5.5l-1 -3q38 9 51 9h761q74 0 114 -56t18 -130l-274 -906 q-36 -119 -71.5 -153.5t-128.5 -34.5h-869q-27 0 -38 -15q-11 -16 -1 -43q24 -70 144 -70h923q29 0 56 15.5t35 41.5l300 987q7 22 5 57q38 -15 59 -43zM575 1056q-4 -13 2 -22.5t20 -9.5h608q13 0 25.5 9.5t16.5 22.5l21 64q4 13 -2 22.5t-20 9.5h-608q-13 0 -25.5 -9.5 t-16.5 -22.5zM492 800q-4 -13 2 -22.5t20 -9.5h608q13 0 25.5 9.5t16.5 22.5l21 64q4 13 -2 22.5t-20 9.5h-608q-13 0 -25.5 -9.5t-16.5 -22.5z" />
<glyph unicode="&#xf02e;" horiz-adv-x="1280" d="M1164 1408q23 0 44 -9q33 -13 52.5 -41t19.5 -62v-1289q0 -34 -19.5 -62t-52.5 -41q-19 -8 -44 -8q-48 0 -83 32l-441 424l-441 -424q-36 -33 -83 -33q-23 0 -44 9q-33 13 -52.5 41t-19.5 62v1289q0 34 19.5 62t52.5 41q21 9 44 9h1048z" />
<glyph unicode="&#xf02f;" horiz-adv-x="1664" d="M384 0h896v256h-896v-256zM384 640h896v384h-160q-40 0 -68 28t-28 68v160h-640v-640zM1536 576q0 26 -19 45t-45 19t-45 -19t-19 -45t19 -45t45 -19t45 19t19 45zM1664 576v-416q0 -13 -9.5 -22.5t-22.5 -9.5h-224v-160q0 -40 -28 -68t-68 -28h-960q-40 0 -68 28t-28 68 v160h-224q-13 0 -22.5 9.5t-9.5 22.5v416q0 79 56.5 135.5t135.5 56.5h64v544q0 40 28 68t68 28h672q40 0 88 -20t76 -48l152 -152q28 -28 48 -76t20 -88v-256h64q79 0 135.5 -56.5t56.5 -135.5z" />
<glyph unicode="&#xf030;" horiz-adv-x="1920" d="M960 864q119 0 203.5 -84.5t84.5 -203.5t-84.5 -203.5t-203.5 -84.5t-203.5 84.5t-84.5 203.5t84.5 203.5t203.5 84.5zM1664 1280q106 0 181 -75t75 -181v-896q0 -106 -75 -181t-181 -75h-1408q-106 0 -181 75t-75 181v896q0 106 75 181t181 75h224l51 136 q19 49 69.5 84.5t103.5 35.5h512q53 0 103.5 -35.5t69.5 -84.5l51 -136h224zM960 128q185 0 316.5 131.5t131.5 316.5t-131.5 316.5t-316.5 131.5t-316.5 -131.5t-131.5 -316.5t131.5 -316.5t316.5 -131.5z" />
<glyph unicode="&#xf031;" horiz-adv-x="1664" d="M725 977l-170 -450q33 0 136.5 -2t160.5 -2q19 0 57 2q-87 253 -184 452zM0 -128l2 79q23 7 56 12.5t57 10.5t49.5 14.5t44.5 29t31 50.5l237 616l280 724h75h53q8 -14 11 -21l205 -480q33 -78 106 -257.5t114 -274.5q15 -34 58 -144.5t72 -168.5q20 -45 35 -57 q19 -15 88 -29.5t84 -20.5q6 -38 6 -57q0 -4 -0.5 -13t-0.5 -13q-63 0 -190 8t-191 8q-76 0 -215 -7t-178 -8q0 43 4 78l131 28q1 0 12.5 2.5t15.5 3.5t14.5 4.5t15 6.5t11 8t9 11t2.5 14q0 16 -31 96.5t-72 177.5t-42 100l-450 2q-26 -58 -76.5 -195.5t-50.5 -162.5 q0 -22 14 -37.5t43.5 -24.5t48.5 -13.5t57 -8.5t41 -4q1 -19 1 -58q0 -9 -2 -27q-58 0 -174.5 10t-174.5 10q-8 0 -26.5 -4t-21.5 -4q-80 -14 -188 -14z" />
<glyph unicode="&#xf032;" horiz-adv-x="1408" d="M555 15q74 -32 140 -32q376 0 376 335q0 114 -41 180q-27 44 -61.5 74t-67.5 46.5t-80.5 25t-84 10.5t-94.5 2q-73 0 -101 -10q0 -53 -0.5 -159t-0.5 -158q0 -8 -1 -67.5t-0.5 -96.5t4.5 -83.5t12 -66.5zM541 761q42 -7 109 -7q82 0 143 13t110 44.5t74.5 89.5t25.5 142 q0 70 -29 122.5t-79 82t-108 43.5t-124 14q-50 0 -130 -13q0 -50 4 -151t4 -152q0 -27 -0.5 -80t-0.5 -79q0 -46 1 -69zM0 -128l2 94q15 4 85 16t106 27q7 12 12.5 27t8.5 33.5t5.5 32.5t3 37.5t0.5 34v35.5v30q0 982 -22 1025q-4 8 -22 14.5t-44.5 11t-49.5 7t-48.5 4.5 t-30.5 3l-4 83q98 2 340 11.5t373 9.5q23 0 68.5 -0.5t67.5 -0.5q70 0 136.5 -13t128.5 -42t108 -71t74 -104.5t28 -137.5q0 -52 -16.5 -95.5t-39 -72t-64.5 -57.5t-73 -45t-84 -40q154 -35 256.5 -134t102.5 -248q0 -100 -35 -179.5t-93.5 -130.5t-138 -85.5t-163.5 -48.5 t-176 -14q-44 0 -132 3t-132 3q-106 0 -307 -11t-231 -12z" />
<glyph unicode="&#xf033;" horiz-adv-x="1024" d="M0 -126l17 85q6 2 81.5 21.5t111.5 37.5q28 35 41 101q1 7 62 289t114 543.5t52 296.5v25q-24 13 -54.5 18.5t-69.5 8t-58 5.5l19 103q33 -2 120 -6.5t149.5 -7t120.5 -2.5q48 0 98.5 2.5t121 7t98.5 6.5q-5 -39 -19 -89q-30 -10 -101.5 -28.5t-108.5 -33.5 q-8 -19 -14 -42.5t-9 -40t-7.5 -45.5t-6.5 -42q-27 -148 -87.5 -419.5t-77.5 -355.5q-2 -9 -13 -58t-20 -90t-16 -83.5t-6 -57.5l1 -18q17 -4 185 -31q-3 -44 -16 -99q-11 0 -32.5 -1.5t-32.5 -1.5q-29 0 -87 10t-86 10q-138 2 -206 2q-51 0 -143 -9t-121 -11z" />
<glyph unicode="&#xf034;" horiz-adv-x="1792" d="M1744 128q33 0 42 -18.5t-11 -44.5l-126 -162q-20 -26 -49 -26t-49 26l-126 162q-20 26 -11 44.5t42 18.5h80v1024h-80q-33 0 -42 18.5t11 44.5l126 162q20 26 49 26t49 -26l126 -162q20 -26 11 -44.5t-42 -18.5h-80v-1024h80zM81 1407l54 -27q12 -5 211 -5q44 0 132 2 t132 2q36 0 107.5 -0.5t107.5 -0.5h293q6 0 21 -0.5t20.5 0t16 3t17.5 9t15 17.5l42 1q4 0 14 -0.5t14 -0.5q2 -112 2 -336q0 -80 -5 -109q-39 -14 -68 -18q-25 44 -54 128q-3 9 -11 48t-14.5 73.5t-7.5 35.5q-6 8 -12 12.5t-15.5 6t-13 2.5t-18 0.5t-16.5 -0.5 q-17 0 -66.5 0.5t-74.5 0.5t-64 -2t-71 -6q-9 -81 -8 -136q0 -94 2 -388t2 -455q0 -16 -2.5 -71.5t0 -91.5t12.5 -69q40 -21 124 -42.5t120 -37.5q5 -40 5 -50q0 -14 -3 -29l-34 -1q-76 -2 -218 8t-207 10q-50 0 -151 -9t-152 -9q-3 51 -3 52v9q17 27 61.5 43t98.5 29t78 27 q19 42 19 383q0 101 -3 303t-3 303v117q0 2 0.5 15.5t0.5 25t-1 25.5t-3 24t-5 14q-11 12 -162 12q-33 0 -93 -12t-80 -26q-19 -13 -34 -72.5t-31.5 -111t-42.5 -53.5q-42 26 -56 44v383z" />
<glyph unicode="&#xf035;" d="M81 1407l54 -27q12 -5 211 -5q44 0 132 2t132 2q70 0 246.5 1t304.5 0.5t247 -4.5q33 -1 56 31l42 1q4 0 14 -0.5t14 -0.5q2 -112 2 -336q0 -80 -5 -109q-39 -14 -68 -18q-25 44 -54 128q-3 9 -11 47.5t-15 73.5t-7 36q-10 13 -27 19q-5 2 -66 2q-30 0 -93 1t-103 1 t-94 -2t-96 -7q-9 -81 -8 -136l1 -152v52q0 -55 1 -154t1.5 -180t0.5 -153q0 -16 -2.5 -71.5t0 -91.5t12.5 -69q40 -21 124 -42.5t120 -37.5q5 -40 5 -50q0 -14 -3 -29l-34 -1q-76 -2 -218 8t-207 10q-50 0 -151 -9t-152 -9q-3 51 -3 52v9q17 27 61.5 43t98.5 29t78 27 q7 16 11.5 74t6 145.5t1.5 155t-0.5 153.5t-0.5 89q0 7 -2.5 21.5t-2.5 22.5q0 7 0.5 44t1 73t0 76.5t-3 67.5t-6.5 32q-11 12 -162 12q-41 0 -163 -13.5t-138 -24.5q-19 -12 -34 -71.5t-31.5 -111.5t-42.5 -54q-42 26 -56 44v383zM1310 125q12 0 42 -19.5t57.5 -41.5 t59.5 -49t36 -30q26 -21 26 -49t-26 -49q-4 -3 -36 -30t-59.5 -49t-57.5 -41.5t-42 -19.5q-13 0 -20.5 10.5t-10 28.5t-2.5 33.5t1.5 33t1.5 19.5h-1024q0 -2 1.5 -19.5t1.5 -33t-2.5 -33.5t-10 -28.5t-20.5 -10.5q-12 0 -42 19.5t-57.5 41.5t-59.5 49t-36 30q-26 21 -26 49 t26 49q4 3 36 30t59.5 49t57.5 41.5t42 19.5q13 0 20.5 -10.5t10 -28.5t2.5 -33.5t-1.5 -33t-1.5 -19.5h1024q0 2 -1.5 19.5t-1.5 33t2.5 33.5t10 28.5t20.5 10.5z" />
<glyph unicode="&#xf036;" horiz-adv-x="1792" d="M1792 192v-128q0 -26 -19 -45t-45 -19h-1664q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h1664q26 0 45 -19t19 -45zM1408 576v-128q0 -26 -19 -45t-45 -19h-1280q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h1280q26 0 45 -19t19 -45zM1664 960v-128q0 -26 -19 -45 t-45 -19h-1536q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h1536q26 0 45 -19t19 -45zM1280 1344v-128q0 -26 -19 -45t-45 -19h-1152q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h1152q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf037;" horiz-adv-x="1792" d="M1792 192v-128q0 -26 -19 -45t-45 -19h-1664q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h1664q26 0 45 -19t19 -45zM1408 576v-128q0 -26 -19 -45t-45 -19h-896q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h896q26 0 45 -19t19 -45zM1664 960v-128q0 -26 -19 -45t-45 -19 h-1408q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h1408q26 0 45 -19t19 -45zM1280 1344v-128q0 -26 -19 -45t-45 -19h-640q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h640q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf038;" horiz-adv-x="1792" d="M1792 192v-128q0 -26 -19 -45t-45 -19h-1664q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h1664q26 0 45 -19t19 -45zM1792 576v-128q0 -26 -19 -45t-45 -19h-1280q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h1280q26 0 45 -19t19 -45zM1792 960v-128q0 -26 -19 -45 t-45 -19h-1536q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h1536q26 0 45 -19t19 -45zM1792 1344v-128q0 -26 -19 -45t-45 -19h-1152q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h1152q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf039;" horiz-adv-x="1792" d="M1792 192v-128q0 -26 -19 -45t-45 -19h-1664q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h1664q26 0 45 -19t19 -45zM1792 576v-128q0 -26 -19 -45t-45 -19h-1664q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h1664q26 0 45 -19t19 -45zM1792 960v-128q0 -26 -19 -45 t-45 -19h-1664q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h1664q26 0 45 -19t19 -45zM1792 1344v-128q0 -26 -19 -45t-45 -19h-1664q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h1664q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf03a;" horiz-adv-x="1792" d="M256 224v-192q0 -13 -9.5 -22.5t-22.5 -9.5h-192q-13 0 -22.5 9.5t-9.5 22.5v192q0 13 9.5 22.5t22.5 9.5h192q13 0 22.5 -9.5t9.5 -22.5zM256 608v-192q0 -13 -9.5 -22.5t-22.5 -9.5h-192q-13 0 -22.5 9.5t-9.5 22.5v192q0 13 9.5 22.5t22.5 9.5h192q13 0 22.5 -9.5 t9.5 -22.5zM256 992v-192q0 -13 -9.5 -22.5t-22.5 -9.5h-192q-13 0 -22.5 9.5t-9.5 22.5v192q0 13 9.5 22.5t22.5 9.5h192q13 0 22.5 -9.5t9.5 -22.5zM1792 224v-192q0 -13 -9.5 -22.5t-22.5 -9.5h-1344q-13 0 -22.5 9.5t-9.5 22.5v192q0 13 9.5 22.5t22.5 9.5h1344 q13 0 22.5 -9.5t9.5 -22.5zM256 1376v-192q0 -13 -9.5 -22.5t-22.5 -9.5h-192q-13 0 -22.5 9.5t-9.5 22.5v192q0 13 9.5 22.5t22.5 9.5h192q13 0 22.5 -9.5t9.5 -22.5zM1792 608v-192q0 -13 -9.5 -22.5t-22.5 -9.5h-1344q-13 0 -22.5 9.5t-9.5 22.5v192q0 13 9.5 22.5 t22.5 9.5h1344q13 0 22.5 -9.5t9.5 -22.5zM1792 992v-192q0 -13 -9.5 -22.5t-22.5 -9.5h-1344q-13 0 -22.5 9.5t-9.5 22.5v192q0 13 9.5 22.5t22.5 9.5h1344q13 0 22.5 -9.5t9.5 -22.5zM1792 1376v-192q0 -13 -9.5 -22.5t-22.5 -9.5h-1344q-13 0 -22.5 9.5t-9.5 22.5v192 q0 13 9.5 22.5t22.5 9.5h1344q13 0 22.5 -9.5t9.5 -22.5z" />
<glyph unicode="&#xf03b;" horiz-adv-x="1792" d="M384 992v-576q0 -13 -9.5 -22.5t-22.5 -9.5q-14 0 -23 9l-288 288q-9 9 -9 23t9 23l288 288q9 9 23 9q13 0 22.5 -9.5t9.5 -22.5zM1792 224v-192q0 -13 -9.5 -22.5t-22.5 -9.5h-1728q-13 0 -22.5 9.5t-9.5 22.5v192q0 13 9.5 22.5t22.5 9.5h1728q13 0 22.5 -9.5 t9.5 -22.5zM1792 608v-192q0 -13 -9.5 -22.5t-22.5 -9.5h-1088q-13 0 -22.5 9.5t-9.5 22.5v192q0 13 9.5 22.5t22.5 9.5h1088q13 0 22.5 -9.5t9.5 -22.5zM1792 992v-192q0 -13 -9.5 -22.5t-22.5 -9.5h-1088q-13 0 -22.5 9.5t-9.5 22.5v192q0 13 9.5 22.5t22.5 9.5h1088 q13 0 22.5 -9.5t9.5 -22.5zM1792 1376v-192q0 -13 -9.5 -22.5t-22.5 -9.5h-1728q-13 0 -22.5 9.5t-9.5 22.5v192q0 13 9.5 22.5t22.5 9.5h1728q13 0 22.5 -9.5t9.5 -22.5z" />
<glyph unicode="&#xf03c;" horiz-adv-x="1792" d="M352 704q0 -14 -9 -23l-288 -288q-9 -9 -23 -9q-13 0 -22.5 9.5t-9.5 22.5v576q0 13 9.5 22.5t22.5 9.5q14 0 23 -9l288 -288q9 -9 9 -23zM1792 224v-192q0 -13 -9.5 -22.5t-22.5 -9.5h-1728q-13 0 -22.5 9.5t-9.5 22.5v192q0 13 9.5 22.5t22.5 9.5h1728q13 0 22.5 -9.5 t9.5 -22.5zM1792 608v-192q0 -13 -9.5 -22.5t-22.5 -9.5h-1088q-13 0 -22.5 9.5t-9.5 22.5v192q0 13 9.5 22.5t22.5 9.5h1088q13 0 22.5 -9.5t9.5 -22.5zM1792 992v-192q0 -13 -9.5 -22.5t-22.5 -9.5h-1088q-13 0 -22.5 9.5t-9.5 22.5v192q0 13 9.5 22.5t22.5 9.5h1088 q13 0 22.5 -9.5t9.5 -22.5zM1792 1376v-192q0 -13 -9.5 -22.5t-22.5 -9.5h-1728q-13 0 -22.5 9.5t-9.5 22.5v192q0 13 9.5 22.5t22.5 9.5h1728q13 0 22.5 -9.5t9.5 -22.5z" />
<glyph unicode="&#xf03d;" horiz-adv-x="1792" d="M1792 1184v-1088q0 -42 -39 -59q-13 -5 -25 -5q-27 0 -45 19l-403 403v-166q0 -119 -84.5 -203.5t-203.5 -84.5h-704q-119 0 -203.5 84.5t-84.5 203.5v704q0 119 84.5 203.5t203.5 84.5h704q119 0 203.5 -84.5t84.5 -203.5v-165l403 402q18 19 45 19q12 0 25 -5 q39 -17 39 -59z" />
<glyph unicode="&#xf03e;" horiz-adv-x="1920" d="M640 960q0 -80 -56 -136t-136 -56t-136 56t-56 136t56 136t136 56t136 -56t56 -136zM1664 576v-448h-1408v192l320 320l160 -160l512 512zM1760 1280h-1600q-13 0 -22.5 -9.5t-9.5 -22.5v-1216q0 -13 9.5 -22.5t22.5 -9.5h1600q13 0 22.5 9.5t9.5 22.5v1216 q0 13 -9.5 22.5t-22.5 9.5zM1920 1248v-1216q0 -66 -47 -113t-113 -47h-1600q-66 0 -113 47t-47 113v1216q0 66 47 113t113 47h1600q66 0 113 -47t47 -113z" />
<glyph unicode="&#xf040;" d="M363 0l91 91l-235 235l-91 -91v-107h128v-128h107zM886 928q0 22 -22 22q-10 0 -17 -7l-542 -542q-7 -7 -7 -17q0 -22 22 -22q10 0 17 7l542 542q7 7 7 17zM832 1120l416 -416l-832 -832h-416v416zM1515 1024q0 -53 -37 -90l-166 -166l-416 416l166 165q36 38 90 38 q53 0 91 -38l235 -234q37 -39 37 -91z" />
<glyph unicode="&#xf041;" horiz-adv-x="1024" d="M768 896q0 106 -75 181t-181 75t-181 -75t-75 -181t75 -181t181 -75t181 75t75 181zM1024 896q0 -109 -33 -179l-364 -774q-16 -33 -47.5 -52t-67.5 -19t-67.5 19t-46.5 52l-365 774q-33 70 -33 179q0 212 150 362t362 150t362 -150t150 -362z" />
<glyph unicode="&#xf042;" d="M768 96v1088q-148 0 -273 -73t-198 -198t-73 -273t73 -273t198 -198t273 -73zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf043;" horiz-adv-x="1024" d="M512 384q0 36 -20 69q-1 1 -15.5 22.5t-25.5 38t-25 44t-21 50.5q-4 16 -21 16t-21 -16q-7 -23 -21 -50.5t-25 -44t-25.5 -38t-15.5 -22.5q-20 -33 -20 -69q0 -53 37.5 -90.5t90.5 -37.5t90.5 37.5t37.5 90.5zM1024 512q0 -212 -150 -362t-362 -150t-362 150t-150 362 q0 145 81 275q6 9 62.5 90.5t101 151t99.5 178t83 201.5q9 30 34 47t51 17t51.5 -17t33.5 -47q28 -93 83 -201.5t99.5 -178t101 -151t62.5 -90.5q81 -127 81 -275z" />
<glyph unicode="&#xf044;" horiz-adv-x="1792" d="M888 352l116 116l-152 152l-116 -116v-56h96v-96h56zM1328 1072q-16 16 -33 -1l-350 -350q-17 -17 -1 -33t33 1l350 350q17 17 1 33zM1408 478v-190q0 -119 -84.5 -203.5t-203.5 -84.5h-832q-119 0 -203.5 84.5t-84.5 203.5v832q0 119 84.5 203.5t203.5 84.5h832 q63 0 117 -25q15 -7 18 -23q3 -17 -9 -29l-49 -49q-14 -14 -32 -8q-23 6 -45 6h-832q-66 0 -113 -47t-47 -113v-832q0 -66 47 -113t113 -47h832q66 0 113 47t47 113v126q0 13 9 22l64 64q15 15 35 7t20 -29zM1312 1216l288 -288l-672 -672h-288v288zM1756 1084l-92 -92 l-288 288l92 92q28 28 68 28t68 -28l152 -152q28 -28 28 -68t-28 -68z" />
<glyph unicode="&#xf045;" horiz-adv-x="1664" d="M1408 547v-259q0 -119 -84.5 -203.5t-203.5 -84.5h-832q-119 0 -203.5 84.5t-84.5 203.5v832q0 119 84.5 203.5t203.5 84.5h255v0q13 0 22.5 -9.5t9.5 -22.5q0 -27 -26 -32q-77 -26 -133 -60q-10 -4 -16 -4h-112q-66 0 -113 -47t-47 -113v-832q0 -66 47 -113t113 -47h832 q66 0 113 47t47 113v214q0 19 18 29q28 13 54 37q16 16 35 8q21 -9 21 -29zM1645 1043l-384 -384q-18 -19 -45 -19q-12 0 -25 5q-39 17 -39 59v192h-160q-323 0 -438 -131q-119 -137 -74 -473q3 -23 -20 -34q-8 -2 -12 -2q-16 0 -26 13q-10 14 -21 31t-39.5 68.5t-49.5 99.5 t-38.5 114t-17.5 122q0 49 3.5 91t14 90t28 88t47 81.5t68.5 74t94.5 61.5t124.5 48.5t159.5 30.5t196.5 11h160v192q0 42 39 59q13 5 25 5q26 0 45 -19l384 -384q19 -19 19 -45t-19 -45z" />
<glyph unicode="&#xf046;" horiz-adv-x="1664" d="M1408 606v-318q0 -119 -84.5 -203.5t-203.5 -84.5h-832q-119 0 -203.5 84.5t-84.5 203.5v832q0 119 84.5 203.5t203.5 84.5h832q63 0 117 -25q15 -7 18 -23q3 -17 -9 -29l-49 -49q-10 -10 -23 -10q-3 0 -9 2q-23 6 -45 6h-832q-66 0 -113 -47t-47 -113v-832 q0 -66 47 -113t113 -47h832q66 0 113 47t47 113v254q0 13 9 22l64 64q10 10 23 10q6 0 12 -3q20 -8 20 -29zM1639 1095l-814 -814q-24 -24 -57 -24t-57 24l-430 430q-24 24 -24 57t24 57l110 110q24 24 57 24t57 -24l263 -263l647 647q24 24 57 24t57 -24l110 -110 q24 -24 24 -57t-24 -57z" />
<glyph unicode="&#xf047;" horiz-adv-x="1792" d="M1792 640q0 -26 -19 -45l-256 -256q-19 -19 -45 -19t-45 19t-19 45v128h-384v-384h128q26 0 45 -19t19 -45t-19 -45l-256 -256q-19 -19 -45 -19t-45 19l-256 256q-19 19 -19 45t19 45t45 19h128v384h-384v-128q0 -26 -19 -45t-45 -19t-45 19l-256 256q-19 19 -19 45 t19 45l256 256q19 19 45 19t45 -19t19 -45v-128h384v384h-128q-26 0 -45 19t-19 45t19 45l256 256q19 19 45 19t45 -19l256 -256q19 -19 19 -45t-19 -45t-45 -19h-128v-384h384v128q0 26 19 45t45 19t45 -19l256 -256q19 -19 19 -45z" />
<glyph unicode="&#xf048;" horiz-adv-x="1024" d="M979 1395q19 19 32 13t13 -32v-1472q0 -26 -13 -32t-32 13l-710 710q-9 9 -13 19v-678q0 -26 -19 -45t-45 -19h-128q-26 0 -45 19t-19 45v1408q0 26 19 45t45 19h128q26 0 45 -19t19 -45v-678q4 11 13 19z" />
<glyph unicode="&#xf049;" horiz-adv-x="1792" d="M1747 1395q19 19 32 13t13 -32v-1472q0 -26 -13 -32t-32 13l-710 710q-9 9 -13 19v-710q0 -26 -13 -32t-32 13l-710 710q-9 9 -13 19v-678q0 -26 -19 -45t-45 -19h-128q-26 0 -45 19t-19 45v1408q0 26 19 45t45 19h128q26 0 45 -19t19 -45v-678q4 11 13 19l710 710 q19 19 32 13t13 -32v-710q4 11 13 19z" />
<glyph unicode="&#xf04a;" horiz-adv-x="1664" d="M1619 1395q19 19 32 13t13 -32v-1472q0 -26 -13 -32t-32 13l-710 710q-8 9 -13 19v-710q0 -26 -13 -32t-32 13l-710 710q-19 19 -19 45t19 45l710 710q19 19 32 13t13 -32v-710q5 11 13 19z" />
<glyph unicode="&#xf04b;" horiz-adv-x="1408" d="M1384 609l-1328 -738q-23 -13 -39.5 -3t-16.5 36v1472q0 26 16.5 36t39.5 -3l1328 -738q23 -13 23 -31t-23 -31z" />
<glyph unicode="&#xf04c;" d="M1536 1344v-1408q0 -26 -19 -45t-45 -19h-512q-26 0 -45 19t-19 45v1408q0 26 19 45t45 19h512q26 0 45 -19t19 -45zM640 1344v-1408q0 -26 -19 -45t-45 -19h-512q-26 0 -45 19t-19 45v1408q0 26 19 45t45 19h512q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf04d;" d="M1536 1344v-1408q0 -26 -19 -45t-45 -19h-1408q-26 0 -45 19t-19 45v1408q0 26 19 45t45 19h1408q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf04e;" horiz-adv-x="1664" d="M45 -115q-19 -19 -32 -13t-13 32v1472q0 26 13 32t32 -13l710 -710q8 -8 13 -19v710q0 26 13 32t32 -13l710 -710q19 -19 19 -45t-19 -45l-710 -710q-19 -19 -32 -13t-13 32v710q-5 -10 -13 -19z" />
<glyph unicode="&#xf050;" horiz-adv-x="1792" d="M45 -115q-19 -19 -32 -13t-13 32v1472q0 26 13 32t32 -13l710 -710q8 -8 13 -19v710q0 26 13 32t32 -13l710 -710q8 -8 13 -19v678q0 26 19 45t45 19h128q26 0 45 -19t19 -45v-1408q0 -26 -19 -45t-45 -19h-128q-26 0 -45 19t-19 45v678q-5 -10 -13 -19l-710 -710 q-19 -19 -32 -13t-13 32v710q-5 -10 -13 -19z" />
<glyph unicode="&#xf051;" horiz-adv-x="1024" d="M45 -115q-19 -19 -32 -13t-13 32v1472q0 26 13 32t32 -13l710 -710q8 -8 13 -19v678q0 26 19 45t45 19h128q26 0 45 -19t19 -45v-1408q0 -26 -19 -45t-45 -19h-128q-26 0 -45 19t-19 45v678q-5 -10 -13 -19z" />
<glyph unicode="&#xf052;" horiz-adv-x="1538" d="M14 557l710 710q19 19 45 19t45 -19l710 -710q19 -19 13 -32t-32 -13h-1472q-26 0 -32 13t13 32zM1473 0h-1408q-26 0 -45 19t-19 45v256q0 26 19 45t45 19h1408q26 0 45 -19t19 -45v-256q0 -26 -19 -45t-45 -19z" />
<glyph unicode="&#xf053;" horiz-adv-x="1280" d="M1171 1235l-531 -531l531 -531q19 -19 19 -45t-19 -45l-166 -166q-19 -19 -45 -19t-45 19l-742 742q-19 19 -19 45t19 45l742 742q19 19 45 19t45 -19l166 -166q19 -19 19 -45t-19 -45z" />
<glyph unicode="&#xf054;" horiz-adv-x="1280" d="M1107 659l-742 -742q-19 -19 -45 -19t-45 19l-166 166q-19 19 -19 45t19 45l531 531l-531 531q-19 19 -19 45t19 45l166 166q19 19 45 19t45 -19l742 -742q19 -19 19 -45t-19 -45z" />
<glyph unicode="&#xf055;" d="M1216 576v128q0 26 -19 45t-45 19h-256v256q0 26 -19 45t-45 19h-128q-26 0 -45 -19t-19 -45v-256h-256q-26 0 -45 -19t-19 -45v-128q0 -26 19 -45t45 -19h256v-256q0 -26 19 -45t45 -19h128q26 0 45 19t19 45v256h256q26 0 45 19t19 45zM1536 640q0 -209 -103 -385.5 t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf056;" d="M1216 576v128q0 26 -19 45t-45 19h-768q-26 0 -45 -19t-19 -45v-128q0 -26 19 -45t45 -19h768q26 0 45 19t19 45zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5 t103 -385.5z" />
<glyph unicode="&#xf057;" d="M1149 414q0 26 -19 45l-181 181l181 181q19 19 19 45q0 27 -19 46l-90 90q-19 19 -46 19q-26 0 -45 -19l-181 -181l-181 181q-19 19 -45 19q-27 0 -46 -19l-90 -90q-19 -19 -19 -46q0 -26 19 -45l181 -181l-181 -181q-19 -19 -19 -45q0 -27 19 -46l90 -90q19 -19 46 -19 q26 0 45 19l181 181l181 -181q19 -19 45 -19q27 0 46 19l90 90q19 19 19 46zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf058;" d="M1284 802q0 28 -18 46l-91 90q-19 19 -45 19t-45 -19l-408 -407l-226 226q-19 19 -45 19t-45 -19l-91 -90q-18 -18 -18 -46q0 -27 18 -45l362 -362q19 -19 45 -19q27 0 46 19l543 543q18 18 18 45zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103 t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf059;" d="M896 160v192q0 14 -9 23t-23 9h-192q-14 0 -23 -9t-9 -23v-192q0 -14 9 -23t23 -9h192q14 0 23 9t9 23zM1152 832q0 88 -55.5 163t-138.5 116t-170 41q-243 0 -371 -213q-15 -24 8 -42l132 -100q7 -6 19 -6q16 0 25 12q53 68 86 92q34 24 86 24q48 0 85.5 -26t37.5 -59 q0 -38 -20 -61t-68 -45q-63 -28 -115.5 -86.5t-52.5 -125.5v-36q0 -14 9 -23t23 -9h192q14 0 23 9t9 23q0 19 21.5 49.5t54.5 49.5q32 18 49 28.5t46 35t44.5 48t28 60.5t12.5 81zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5 t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf05a;" d="M1024 160v160q0 14 -9 23t-23 9h-96v512q0 14 -9 23t-23 9h-320q-14 0 -23 -9t-9 -23v-160q0 -14 9 -23t23 -9h96v-320h-96q-14 0 -23 -9t-9 -23v-160q0 -14 9 -23t23 -9h448q14 0 23 9t9 23zM896 1056v160q0 14 -9 23t-23 9h-192q-14 0 -23 -9t-9 -23v-160q0 -14 9 -23 t23 -9h192q14 0 23 9t9 23zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf05b;" d="M1197 512h-109q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h109q-32 108 -112.5 188.5t-188.5 112.5v-109q0 -26 -19 -45t-45 -19h-128q-26 0 -45 19t-19 45v109q-108 -32 -188.5 -112.5t-112.5 -188.5h109q26 0 45 -19t19 -45v-128q0 -26 -19 -45t-45 -19h-109 q32 -108 112.5 -188.5t188.5 -112.5v109q0 26 19 45t45 19h128q26 0 45 -19t19 -45v-109q108 32 188.5 112.5t112.5 188.5zM1536 704v-128q0 -26 -19 -45t-45 -19h-143q-37 -161 -154.5 -278.5t-278.5 -154.5v-143q0 -26 -19 -45t-45 -19h-128q-26 0 -45 19t-19 45v143 q-161 37 -278.5 154.5t-154.5 278.5h-143q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h143q37 161 154.5 278.5t278.5 154.5v143q0 26 19 45t45 19h128q26 0 45 -19t19 -45v-143q161 -37 278.5 -154.5t154.5 -278.5h143q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf05c;" d="M1097 457l-146 -146q-10 -10 -23 -10t-23 10l-137 137l-137 -137q-10 -10 -23 -10t-23 10l-146 146q-10 10 -10 23t10 23l137 137l-137 137q-10 10 -10 23t10 23l146 146q10 10 23 10t23 -10l137 -137l137 137q10 10 23 10t23 -10l146 -146q10 -10 10 -23t-10 -23 l-137 -137l137 -137q10 -10 10 -23t-10 -23zM1312 640q0 148 -73 273t-198 198t-273 73t-273 -73t-198 -198t-73 -273t73 -273t198 -198t273 -73t273 73t198 198t73 273zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5 t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf05d;" d="M1171 723l-422 -422q-19 -19 -45 -19t-45 19l-294 294q-19 19 -19 45t19 45l102 102q19 19 45 19t45 -19l147 -147l275 275q19 19 45 19t45 -19l102 -102q19 -19 19 -45t-19 -45zM1312 640q0 148 -73 273t-198 198t-273 73t-273 -73t-198 -198t-73 -273t73 -273t198 -198 t273 -73t273 73t198 198t73 273zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf05e;" d="M1312 643q0 161 -87 295l-754 -753q137 -89 297 -89q111 0 211.5 43.5t173.5 116.5t116 174.5t43 212.5zM313 344l755 754q-135 91 -300 91q-148 0 -273 -73t-198 -199t-73 -274q0 -162 89 -299zM1536 643q0 -157 -61 -300t-163.5 -246t-245 -164t-298.5 -61t-298.5 61 t-245 164t-163.5 246t-61 300t61 299.5t163.5 245.5t245 164t298.5 61t298.5 -61t245 -164t163.5 -245.5t61 -299.5z" />
<glyph unicode="&#xf060;" d="M1536 640v-128q0 -53 -32.5 -90.5t-84.5 -37.5h-704l293 -294q38 -36 38 -90t-38 -90l-75 -76q-37 -37 -90 -37q-52 0 -91 37l-651 652q-37 37 -37 90q0 52 37 91l651 650q38 38 91 38q52 0 90 -38l75 -74q38 -38 38 -91t-38 -91l-293 -293h704q52 0 84.5 -37.5 t32.5 -90.5z" />
<glyph unicode="&#xf061;" d="M1472 576q0 -54 -37 -91l-651 -651q-39 -37 -91 -37q-51 0 -90 37l-75 75q-38 38 -38 91t38 91l293 293h-704q-52 0 -84.5 37.5t-32.5 90.5v128q0 53 32.5 90.5t84.5 37.5h704l-293 294q-38 36 -38 90t38 90l75 75q38 38 90 38q53 0 91 -38l651 -651q37 -35 37 -90z" />
<glyph unicode="&#xf062;" horiz-adv-x="1664" d="M1611 565q0 -51 -37 -90l-75 -75q-38 -38 -91 -38q-54 0 -90 38l-294 293v-704q0 -52 -37.5 -84.5t-90.5 -32.5h-128q-53 0 -90.5 32.5t-37.5 84.5v704l-294 -293q-36 -38 -90 -38t-90 38l-75 75q-38 38 -38 90q0 53 38 91l651 651q35 37 90 37q54 0 91 -37l651 -651 q37 -39 37 -91z" />
<glyph unicode="&#xf063;" horiz-adv-x="1664" d="M1611 704q0 -53 -37 -90l-651 -652q-39 -37 -91 -37q-53 0 -90 37l-651 652q-38 36 -38 90q0 53 38 91l74 75q39 37 91 37q53 0 90 -37l294 -294v704q0 52 38 90t90 38h128q52 0 90 -38t38 -90v-704l294 294q37 37 90 37q52 0 91 -37l75 -75q37 -39 37 -91z" />
<glyph unicode="&#xf064;" horiz-adv-x="1792" d="M1792 896q0 -26 -19 -45l-512 -512q-19 -19 -45 -19t-45 19t-19 45v256h-224q-98 0 -175.5 -6t-154 -21.5t-133 -42.5t-105.5 -69.5t-80 -101t-48.5 -138.5t-17.5 -181q0 -55 5 -123q0 -6 2.5 -23.5t2.5 -26.5q0 -15 -8.5 -25t-23.5 -10q-16 0 -28 17q-7 9 -13 22 t-13.5 30t-10.5 24q-127 285 -127 451q0 199 53 333q162 403 875 403h224v256q0 26 19 45t45 19t45 -19l512 -512q19 -19 19 -45z" />
<glyph unicode="&#xf065;" d="M755 480q0 -13 -10 -23l-332 -332l144 -144q19 -19 19 -45t-19 -45t-45 -19h-448q-26 0 -45 19t-19 45v448q0 26 19 45t45 19t45 -19l144 -144l332 332q10 10 23 10t23 -10l114 -114q10 -10 10 -23zM1536 1344v-448q0 -26 -19 -45t-45 -19t-45 19l-144 144l-332 -332 q-10 -10 -23 -10t-23 10l-114 114q-10 10 -10 23t10 23l332 332l-144 144q-19 19 -19 45t19 45t45 19h448q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf066;" d="M768 576v-448q0 -26 -19 -45t-45 -19t-45 19l-144 144l-332 -332q-10 -10 -23 -10t-23 10l-114 114q-10 10 -10 23t10 23l332 332l-144 144q-19 19 -19 45t19 45t45 19h448q26 0 45 -19t19 -45zM1523 1248q0 -13 -10 -23l-332 -332l144 -144q19 -19 19 -45t-19 -45 t-45 -19h-448q-26 0 -45 19t-19 45v448q0 26 19 45t45 19t45 -19l144 -144l332 332q10 10 23 10t23 -10l114 -114q10 -10 10 -23z" />
<glyph unicode="&#xf067;" horiz-adv-x="1408" d="M1408 800v-192q0 -40 -28 -68t-68 -28h-416v-416q0 -40 -28 -68t-68 -28h-192q-40 0 -68 28t-28 68v416h-416q-40 0 -68 28t-28 68v192q0 40 28 68t68 28h416v416q0 40 28 68t68 28h192q40 0 68 -28t28 -68v-416h416q40 0 68 -28t28 -68z" />
<glyph unicode="&#xf068;" horiz-adv-x="1408" d="M1408 800v-192q0 -40 -28 -68t-68 -28h-1216q-40 0 -68 28t-28 68v192q0 40 28 68t68 28h1216q40 0 68 -28t28 -68z" />
<glyph unicode="&#xf069;" horiz-adv-x="1664" d="M1482 486q46 -26 59.5 -77.5t-12.5 -97.5l-64 -110q-26 -46 -77.5 -59.5t-97.5 12.5l-266 153v-307q0 -52 -38 -90t-90 -38h-128q-52 0 -90 38t-38 90v307l-266 -153q-46 -26 -97.5 -12.5t-77.5 59.5l-64 110q-26 46 -12.5 97.5t59.5 77.5l266 154l-266 154 q-46 26 -59.5 77.5t12.5 97.5l64 110q26 46 77.5 59.5t97.5 -12.5l266 -153v307q0 52 38 90t90 38h128q52 0 90 -38t38 -90v-307l266 153q46 26 97.5 12.5t77.5 -59.5l64 -110q26 -46 12.5 -97.5t-59.5 -77.5l-266 -154z" />
<glyph unicode="&#xf06a;" d="M768 1408q209 0 385.5 -103t279.5 -279.5t103 -385.5t-103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103zM896 161v190q0 14 -9 23.5t-22 9.5h-192q-13 0 -23 -10t-10 -23v-190q0 -13 10 -23t23 -10h192 q13 0 22 9.5t9 23.5zM894 505l18 621q0 12 -10 18q-10 8 -24 8h-220q-14 0 -24 -8q-10 -6 -10 -18l17 -621q0 -10 10 -17.5t24 -7.5h185q14 0 23.5 7.5t10.5 17.5z" />
<glyph unicode="&#xf06b;" d="M928 180v56v468v192h-320v-192v-468v-56q0 -25 18 -38.5t46 -13.5h192q28 0 46 13.5t18 38.5zM472 1024h195l-126 161q-26 31 -69 31q-40 0 -68 -28t-28 -68t28 -68t68 -28zM1160 1120q0 40 -28 68t-68 28q-43 0 -69 -31l-125 -161h194q40 0 68 28t28 68zM1536 864v-320 q0 -14 -9 -23t-23 -9h-96v-416q0 -40 -28 -68t-68 -28h-1088q-40 0 -68 28t-28 68v416h-96q-14 0 -23 9t-9 23v320q0 14 9 23t23 9h440q-93 0 -158.5 65.5t-65.5 158.5t65.5 158.5t158.5 65.5q107 0 168 -77l128 -165l128 165q61 77 168 77q93 0 158.5 -65.5t65.5 -158.5 t-65.5 -158.5t-158.5 -65.5h440q14 0 23 -9t9 -23z" />
<glyph unicode="&#xf06c;" horiz-adv-x="1792" d="M1280 832q0 26 -19 45t-45 19q-172 0 -318 -49.5t-259.5 -134t-235.5 -219.5q-19 -21 -19 -45q0 -26 19 -45t45 -19q24 0 45 19q27 24 74 71t67 66q137 124 268.5 176t313.5 52q26 0 45 19t19 45zM1792 1030q0 -95 -20 -193q-46 -224 -184.5 -383t-357.5 -268 q-214 -108 -438 -108q-148 0 -286 47q-15 5 -88 42t-96 37q-16 0 -39.5 -32t-45 -70t-52.5 -70t-60 -32q-30 0 -51 11t-31 24t-27 42q-2 4 -6 11t-5.5 10t-3 9.5t-1.5 13.5q0 35 31 73.5t68 65.5t68 56t31 48q0 4 -14 38t-16 44q-9 51 -9 104q0 115 43.5 220t119 184.5 t170.5 139t204 95.5q55 18 145 25.5t179.5 9t178.5 6t163.5 24t113.5 56.5l29.5 29.5t29.5 28t27 20t36.5 16t43.5 4.5q39 0 70.5 -46t47.5 -112t24 -124t8 -96z" />
<glyph unicode="&#xf06d;" horiz-adv-x="1408" d="M1408 -160v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-1344q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h1344q13 0 22.5 -9.5t9.5 -22.5zM1152 896q0 -78 -24.5 -144t-64 -112.5t-87.5 -88t-96 -77.5t-87.5 -72t-64 -81.5t-24.5 -96.5q0 -96 67 -224l-4 1l1 -1 q-90 41 -160 83t-138.5 100t-113.5 122.5t-72.5 150.5t-27.5 184q0 78 24.5 144t64 112.5t87.5 88t96 77.5t87.5 72t64 81.5t24.5 96.5q0 94 -66 224l3 -1l-1 1q90 -41 160 -83t138.5 -100t113.5 -122.5t72.5 -150.5t27.5 -184z" />
<glyph unicode="&#xf06e;" horiz-adv-x="1792" d="M1664 576q-152 236 -381 353q61 -104 61 -225q0 -185 -131.5 -316.5t-316.5 -131.5t-316.5 131.5t-131.5 316.5q0 121 61 225q-229 -117 -381 -353q133 -205 333.5 -326.5t434.5 -121.5t434.5 121.5t333.5 326.5zM944 960q0 20 -14 34t-34 14q-125 0 -214.5 -89.5 t-89.5 -214.5q0 -20 14 -34t34 -14t34 14t14 34q0 86 61 147t147 61q20 0 34 14t14 34zM1792 576q0 -34 -20 -69q-140 -230 -376.5 -368.5t-499.5 -138.5t-499.5 139t-376.5 368q-20 35 -20 69t20 69q140 229 376.5 368t499.5 139t499.5 -139t376.5 -368q20 -35 20 -69z" />
<glyph unicode="&#xf070;" horiz-adv-x="1792" d="M555 201l78 141q-87 63 -136 159t-49 203q0 121 61 225q-229 -117 -381 -353q167 -258 427 -375zM944 960q0 20 -14 34t-34 14q-125 0 -214.5 -89.5t-89.5 -214.5q0 -20 14 -34t34 -14t34 14t14 34q0 86 61 147t147 61q20 0 34 14t14 34zM1307 1151q0 -7 -1 -9 q-105 -188 -315 -566t-316 -567l-49 -89q-10 -16 -28 -16q-12 0 -134 70q-16 10 -16 28q0 12 44 87q-143 65 -263.5 173t-208.5 245q-20 31 -20 69t20 69q153 235 380 371t496 136q89 0 180 -17l54 97q10 16 28 16q5 0 18 -6t31 -15.5t33 -18.5t31.5 -18.5t19.5 -11.5 q16 -10 16 -27zM1344 704q0 -139 -79 -253.5t-209 -164.5l280 502q8 -45 8 -84zM1792 576q0 -35 -20 -69q-39 -64 -109 -145q-150 -172 -347.5 -267t-419.5 -95l74 132q212 18 392.5 137t301.5 307q-115 179 -282 294l63 112q95 -64 182.5 -153t144.5 -184q20 -34 20 -69z " />
<glyph unicode="&#xf071;" horiz-adv-x="1792" d="M1024 161v190q0 14 -9.5 23.5t-22.5 9.5h-192q-13 0 -22.5 -9.5t-9.5 -23.5v-190q0 -14 9.5 -23.5t22.5 -9.5h192q13 0 22.5 9.5t9.5 23.5zM1022 535l18 459q0 12 -10 19q-13 11 -24 11h-220q-11 0 -24 -11q-10 -7 -10 -21l17 -457q0 -10 10 -16.5t24 -6.5h185 q14 0 23.5 6.5t10.5 16.5zM1008 1469l768 -1408q35 -63 -2 -126q-17 -29 -46.5 -46t-63.5 -17h-1536q-34 0 -63.5 17t-46.5 46q-37 63 -2 126l768 1408q17 31 47 49t65 18t65 -18t47 -49z" />
<glyph unicode="&#xf072;" horiz-adv-x="1408" d="M1376 1376q44 -52 12 -148t-108 -172l-161 -161l160 -696q5 -19 -12 -33l-128 -96q-7 -6 -19 -6q-4 0 -7 1q-15 3 -21 16l-279 508l-259 -259l53 -194q5 -17 -8 -31l-96 -96q-9 -9 -23 -9h-2q-15 2 -24 13l-189 252l-252 189q-11 7 -13 23q-1 13 9 25l96 97q9 9 23 9 q6 0 8 -1l194 -53l259 259l-508 279q-14 8 -17 24q-2 16 9 27l128 128q14 13 30 8l665 -159l160 160q76 76 172 108t148 -12z" />
<glyph unicode="&#xf073;" horiz-adv-x="1664" d="M128 -128h288v288h-288v-288zM480 -128h320v288h-320v-288zM128 224h288v320h-288v-320zM480 224h320v320h-320v-320zM128 608h288v288h-288v-288zM864 -128h320v288h-320v-288zM480 608h320v288h-320v-288zM1248 -128h288v288h-288v-288zM864 224h320v320h-320v-320z M512 1088v288q0 13 -9.5 22.5t-22.5 9.5h-64q-13 0 -22.5 -9.5t-9.5 -22.5v-288q0 -13 9.5 -22.5t22.5 -9.5h64q13 0 22.5 9.5t9.5 22.5zM1248 224h288v320h-288v-320zM864 608h320v288h-320v-288zM1248 608h288v288h-288v-288zM1280 1088v288q0 13 -9.5 22.5t-22.5 9.5h-64 q-13 0 -22.5 -9.5t-9.5 -22.5v-288q0 -13 9.5 -22.5t22.5 -9.5h64q13 0 22.5 9.5t9.5 22.5zM1664 1152v-1280q0 -52 -38 -90t-90 -38h-1408q-52 0 -90 38t-38 90v1280q0 52 38 90t90 38h128v96q0 66 47 113t113 47h64q66 0 113 -47t47 -113v-96h384v96q0 66 47 113t113 47 h64q66 0 113 -47t47 -113v-96h128q52 0 90 -38t38 -90z" />
<glyph unicode="&#xf074;" horiz-adv-x="1792" d="M666 1055q-60 -92 -137 -273q-22 45 -37 72.5t-40.5 63.5t-51 56.5t-63 35t-81.5 14.5h-224q-14 0 -23 9t-9 23v192q0 14 9 23t23 9h224q250 0 410 -225zM1792 256q0 -14 -9 -23l-320 -320q-9 -9 -23 -9q-13 0 -22.5 9.5t-9.5 22.5v192q-32 0 -85 -0.5t-81 -1t-73 1 t-71 5t-64 10.5t-63 18.5t-58 28.5t-59 40t-55 53.5t-56 69.5q59 93 136 273q22 -45 37 -72.5t40.5 -63.5t51 -56.5t63 -35t81.5 -14.5h256v192q0 14 9 23t23 9q12 0 24 -10l319 -319q9 -9 9 -23zM1792 1152q0 -14 -9 -23l-320 -320q-9 -9 -23 -9q-13 0 -22.5 9.5t-9.5 22.5 v192h-256q-48 0 -87 -15t-69 -45t-51 -61.5t-45 -77.5q-32 -62 -78 -171q-29 -66 -49.5 -111t-54 -105t-64 -100t-74 -83t-90 -68.5t-106.5 -42t-128 -16.5h-224q-14 0 -23 9t-9 23v192q0 14 9 23t23 9h224q48 0 87 15t69 45t51 61.5t45 77.5q32 62 78 171q29 66 49.5 111 t54 105t64 100t74 83t90 68.5t106.5 42t128 16.5h256v192q0 14 9 23t23 9q12 0 24 -10l319 -319q9 -9 9 -23z" />
<glyph unicode="&#xf075;" horiz-adv-x="1792" d="M1792 640q0 -174 -120 -321.5t-326 -233t-450 -85.5q-70 0 -145 8q-198 -175 -460 -242q-49 -14 -114 -22q-17 -2 -30.5 9t-17.5 29v1q-3 4 -0.5 12t2 10t4.5 9.5l6 9t7 8.5t8 9q7 8 31 34.5t34.5 38t31 39.5t32.5 51t27 59t26 76q-157 89 -247.5 220t-90.5 281 q0 130 71 248.5t191 204.5t286 136.5t348 50.5q244 0 450 -85.5t326 -233t120 -321.5z" />
<glyph unicode="&#xf076;" d="M1536 704v-128q0 -201 -98.5 -362t-274 -251.5t-395.5 -90.5t-395.5 90.5t-274 251.5t-98.5 362v128q0 26 19 45t45 19h384q26 0 45 -19t19 -45v-128q0 -52 23.5 -90t53.5 -57t71 -30t64 -13t44 -2t44 2t64 13t71 30t53.5 57t23.5 90v128q0 26 19 45t45 19h384 q26 0 45 -19t19 -45zM512 1344v-384q0 -26 -19 -45t-45 -19h-384q-26 0 -45 19t-19 45v384q0 26 19 45t45 19h384q26 0 45 -19t19 -45zM1536 1344v-384q0 -26 -19 -45t-45 -19h-384q-26 0 -45 19t-19 45v384q0 26 19 45t45 19h384q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf077;" horiz-adv-x="1792" d="M1683 205l-166 -165q-19 -19 -45 -19t-45 19l-531 531l-531 -531q-19 -19 -45 -19t-45 19l-166 165q-19 19 -19 45.5t19 45.5l742 741q19 19 45 19t45 -19l742 -741q19 -19 19 -45.5t-19 -45.5z" />
<glyph unicode="&#xf078;" horiz-adv-x="1792" d="M1683 728l-742 -741q-19 -19 -45 -19t-45 19l-742 741q-19 19 -19 45.5t19 45.5l166 165q19 19 45 19t45 -19l531 -531l531 531q19 19 45 19t45 -19l166 -165q19 -19 19 -45.5t-19 -45.5z" />
<glyph unicode="&#xf079;" horiz-adv-x="1920" d="M1280 32q0 -13 -9.5 -22.5t-22.5 -9.5h-960q-8 0 -13.5 2t-9 7t-5.5 8t-3 11.5t-1 11.5v13v11v160v416h-192q-26 0 -45 19t-19 45q0 24 15 41l320 384q19 22 49 22t49 -22l320 -384q15 -17 15 -41q0 -26 -19 -45t-45 -19h-192v-384h576q16 0 25 -11l160 -192q7 -11 7 -21 zM1920 448q0 -24 -15 -41l-320 -384q-20 -23 -49 -23t-49 23l-320 384q-15 17 -15 41q0 26 19 45t45 19h192v384h-576q-16 0 -25 12l-160 192q-7 9 -7 20q0 13 9.5 22.5t22.5 9.5h960q8 0 13.5 -2t9 -7t5.5 -8t3 -11.5t1 -11.5v-13v-11v-160v-416h192q26 0 45 -19t19 -45z " />
<glyph unicode="&#xf07a;" horiz-adv-x="1664" d="M640 0q0 -52 -38 -90t-90 -38t-90 38t-38 90t38 90t90 38t90 -38t38 -90zM1536 0q0 -52 -38 -90t-90 -38t-90 38t-38 90t38 90t90 38t90 -38t38 -90zM1664 1088v-512q0 -24 -16.5 -42.5t-40.5 -21.5l-1044 -122q13 -60 13 -70q0 -16 -24 -64h920q26 0 45 -19t19 -45 t-19 -45t-45 -19h-1024q-26 0 -45 19t-19 45q0 11 8 31.5t16 36t21.5 40t15.5 29.5l-177 823h-204q-26 0 -45 19t-19 45t19 45t45 19h256q16 0 28.5 -6.5t19.5 -15.5t13 -24.5t8 -26t5.5 -29.5t4.5 -26h1201q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf07b;" horiz-adv-x="1664" d="M1664 928v-704q0 -92 -66 -158t-158 -66h-1216q-92 0 -158 66t-66 158v960q0 92 66 158t158 66h320q92 0 158 -66t66 -158v-32h672q92 0 158 -66t66 -158z" />
<glyph unicode="&#xf07c;" horiz-adv-x="1920" d="M1879 584q0 -31 -31 -66l-336 -396q-43 -51 -120.5 -86.5t-143.5 -35.5h-1088q-34 0 -60.5 13t-26.5 43q0 31 31 66l336 396q43 51 120.5 86.5t143.5 35.5h1088q34 0 60.5 -13t26.5 -43zM1536 928v-160h-832q-94 0 -197 -47.5t-164 -119.5l-337 -396l-5 -6q0 4 -0.5 12.5 t-0.5 12.5v960q0 92 66 158t158 66h320q92 0 158 -66t66 -158v-32h544q92 0 158 -66t66 -158z" />
<glyph unicode="&#xf07d;" horiz-adv-x="768" d="M704 1216q0 -26 -19 -45t-45 -19h-128v-1024h128q26 0 45 -19t19 -45t-19 -45l-256 -256q-19 -19 -45 -19t-45 19l-256 256q-19 19 -19 45t19 45t45 19h128v1024h-128q-26 0 -45 19t-19 45t19 45l256 256q19 19 45 19t45 -19l256 -256q19 -19 19 -45z" />
<glyph unicode="&#xf07e;" horiz-adv-x="1792" d="M1792 640q0 -26 -19 -45l-256 -256q-19 -19 -45 -19t-45 19t-19 45v128h-1024v-128q0 -26 -19 -45t-45 -19t-45 19l-256 256q-19 19 -19 45t19 45l256 256q19 19 45 19t45 -19t19 -45v-128h1024v128q0 26 19 45t45 19t45 -19l256 -256q19 -19 19 -45z" />
<glyph unicode="&#xf080;" horiz-adv-x="2048" d="M640 640v-512h-256v512h256zM1024 1152v-1024h-256v1024h256zM2048 0v-128h-2048v1536h128v-1408h1920zM1408 896v-768h-256v768h256zM1792 1280v-1152h-256v1152h256z" />
<glyph unicode="&#xf081;" d="M1280 926q-56 -25 -121 -34q68 40 93 117q-65 -38 -134 -51q-61 66 -153 66q-87 0 -148.5 -61.5t-61.5 -148.5q0 -29 5 -48q-129 7 -242 65t-192 155q-29 -50 -29 -106q0 -114 91 -175q-47 1 -100 26v-2q0 -75 50 -133.5t123 -72.5q-29 -8 -51 -8q-13 0 -39 4 q21 -63 74.5 -104t121.5 -42q-116 -90 -261 -90q-26 0 -50 3q148 -94 322 -94q112 0 210 35.5t168 95t120.5 137t75 162t24.5 168.5q0 18 -1 27q63 45 105 109zM1536 1120v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5 t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf082;" d="M1248 1408q119 0 203.5 -84.5t84.5 -203.5v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-188v595h199l30 232h-229v148q0 56 23.5 84t91.5 28l122 1v207q-63 9 -178 9q-136 0 -217.5 -80t-81.5 -226v-171h-200v-232h200v-595h-532q-119 0 -203.5 84.5t-84.5 203.5v960 q0 119 84.5 203.5t203.5 84.5h960z" />
<glyph unicode="&#xf083;" horiz-adv-x="1792" d="M928 704q0 14 -9 23t-23 9q-66 0 -113 -47t-47 -113q0 -14 9 -23t23 -9t23 9t9 23q0 40 28 68t68 28q14 0 23 9t9 23zM1152 574q0 -106 -75 -181t-181 -75t-181 75t-75 181t75 181t181 75t181 -75t75 -181zM128 0h1536v128h-1536v-128zM1280 574q0 159 -112.5 271.5 t-271.5 112.5t-271.5 -112.5t-112.5 -271.5t112.5 -271.5t271.5 -112.5t271.5 112.5t112.5 271.5zM256 1216h384v128h-384v-128zM128 1024h1536v118v138h-828l-64 -128h-644v-128zM1792 1280v-1280q0 -53 -37.5 -90.5t-90.5 -37.5h-1536q-53 0 -90.5 37.5t-37.5 90.5v1280 q0 53 37.5 90.5t90.5 37.5h1536q53 0 90.5 -37.5t37.5 -90.5z" />
<glyph unicode="&#xf084;" horiz-adv-x="1792" d="M832 1024q0 80 -56 136t-136 56t-136 -56t-56 -136q0 -42 19 -83q-41 19 -83 19q-80 0 -136 -56t-56 -136t56 -136t136 -56t136 56t56 136q0 42 -19 83q41 -19 83 -19q80 0 136 56t56 136zM1683 320q0 -17 -49 -66t-66 -49q-9 0 -28.5 16t-36.5 33t-38.5 40t-24.5 26 l-96 -96l220 -220q28 -28 28 -68q0 -42 -39 -81t-81 -39q-40 0 -68 28l-671 671q-176 -131 -365 -131q-163 0 -265.5 102.5t-102.5 265.5q0 160 95 313t248 248t313 95q163 0 265.5 -102.5t102.5 -265.5q0 -189 -131 -365l355 -355l96 96q-3 3 -26 24.5t-40 38.5t-33 36.5 t-16 28.5q0 17 49 66t66 49q13 0 23 -10q6 -6 46 -44.5t82 -79.5t86.5 -86t73 -78t28.5 -41z" />
<glyph unicode="&#xf085;" horiz-adv-x="1920" d="M896 640q0 106 -75 181t-181 75t-181 -75t-75 -181t75 -181t181 -75t181 75t75 181zM1664 128q0 52 -38 90t-90 38t-90 -38t-38 -90q0 -53 37.5 -90.5t90.5 -37.5t90.5 37.5t37.5 90.5zM1664 1152q0 52 -38 90t-90 38t-90 -38t-38 -90q0 -53 37.5 -90.5t90.5 -37.5 t90.5 37.5t37.5 90.5zM1280 731v-185q0 -10 -7 -19.5t-16 -10.5l-155 -24q-11 -35 -32 -76q34 -48 90 -115q7 -10 7 -20q0 -12 -7 -19q-23 -30 -82.5 -89.5t-78.5 -59.5q-11 0 -21 7l-115 90q-37 -19 -77 -31q-11 -108 -23 -155q-7 -24 -30 -24h-186q-11 0 -20 7.5t-10 17.5 l-23 153q-34 10 -75 31l-118 -89q-7 -7 -20 -7q-11 0 -21 8q-144 133 -144 160q0 9 7 19q10 14 41 53t47 61q-23 44 -35 82l-152 24q-10 1 -17 9.5t-7 19.5v185q0 10 7 19.5t16 10.5l155 24q11 35 32 76q-34 48 -90 115q-7 11 -7 20q0 12 7 20q22 30 82 89t79 59q11 0 21 -7 l115 -90q34 18 77 32q11 108 23 154q7 24 30 24h186q11 0 20 -7.5t10 -17.5l23 -153q34 -10 75 -31l118 89q8 7 20 7q11 0 21 -8q144 -133 144 -160q0 -9 -7 -19q-12 -16 -42 -54t-45 -60q23 -48 34 -82l152 -23q10 -2 17 -10.5t7 -19.5zM1920 198v-140q0 -16 -149 -31 q-12 -27 -30 -52q51 -113 51 -138q0 -4 -4 -7q-122 -71 -124 -71q-8 0 -46 47t-52 68q-20 -2 -30 -2t-30 2q-14 -21 -52 -68t-46 -47q-2 0 -124 71q-4 3 -4 7q0 25 51 138q-18 25 -30 52q-149 15 -149 31v140q0 16 149 31q13 29 30 52q-51 113 -51 138q0 4 4 7q4 2 35 20 t59 34t30 16q8 0 46 -46.5t52 -67.5q20 2 30 2t30 -2q51 71 92 112l6 2q4 0 124 -70q4 -3 4 -7q0 -25 -51 -138q17 -23 30 -52q149 -15 149 -31zM1920 1222v-140q0 -16 -149 -31q-12 -27 -30 -52q51 -113 51 -138q0 -4 -4 -7q-122 -71 -124 -71q-8 0 -46 47t-52 68 q-20 -2 -30 -2t-30 2q-14 -21 -52 -68t-46 -47q-2 0 -124 71q-4 3 -4 7q0 25 51 138q-18 25 -30 52q-149 15 -149 31v140q0 16 149 31q13 29 30 52q-51 113 -51 138q0 4 4 7q4 2 35 20t59 34t30 16q8 0 46 -46.5t52 -67.5q20 2 30 2t30 -2q51 71 92 112l6 2q4 0 124 -70 q4 -3 4 -7q0 -25 -51 -138q17 -23 30 -52q149 -15 149 -31z" />
<glyph unicode="&#xf086;" horiz-adv-x="1792" d="M1408 768q0 -139 -94 -257t-256.5 -186.5t-353.5 -68.5q-86 0 -176 16q-124 -88 -278 -128q-36 -9 -86 -16h-3q-11 0 -20.5 8t-11.5 21q-1 3 -1 6.5t0.5 6.5t2 6l2.5 5t3.5 5.5t4 5t4.5 5t4 4.5q5 6 23 25t26 29.5t22.5 29t25 38.5t20.5 44q-124 72 -195 177t-71 224 q0 139 94 257t256.5 186.5t353.5 68.5t353.5 -68.5t256.5 -186.5t94 -257zM1792 512q0 -120 -71 -224.5t-195 -176.5q10 -24 20.5 -44t25 -38.5t22.5 -29t26 -29.5t23 -25q1 -1 4 -4.5t4.5 -5t4 -5t3.5 -5.5l2.5 -5t2 -6t0.5 -6.5t-1 -6.5q-3 -14 -13 -22t-22 -7 q-50 7 -86 16q-154 40 -278 128q-90 -16 -176 -16q-271 0 -472 132q58 -4 88 -4q161 0 309 45t264 129q125 92 192 212t67 254q0 77 -23 152q129 -71 204 -178t75 -230z" />
<glyph unicode="&#xf087;" d="M256 192q0 26 -19 45t-45 19t-45 -19t-19 -45t19 -45t45 -19t45 19t19 45zM1408 768q0 51 -39 89.5t-89 38.5h-352q0 58 48 159.5t48 160.5q0 98 -32 145t-128 47q-26 -26 -38 -85t-30.5 -125.5t-59.5 -109.5q-22 -23 -77 -91q-4 -5 -23 -30t-31.5 -41t-34.5 -42.5 t-40 -44t-38.5 -35.5t-40 -27t-35.5 -9h-32v-640h32q13 0 31.5 -3t33 -6.5t38 -11t35 -11.5t35.5 -12.5t29 -10.5q211 -73 342 -73h121q192 0 192 167q0 26 -5 56q30 16 47.5 52.5t17.5 73.5t-18 69q53 50 53 119q0 25 -10 55.5t-25 47.5q32 1 53.5 47t21.5 81zM1536 769 q0 -89 -49 -163q9 -33 9 -69q0 -77 -38 -144q3 -21 3 -43q0 -101 -60 -178q1 -139 -85 -219.5t-227 -80.5h-36h-93q-96 0 -189.5 22.5t-216.5 65.5q-116 40 -138 40h-288q-53 0 -90.5 37.5t-37.5 90.5v640q0 53 37.5 90.5t90.5 37.5h274q36 24 137 155q58 75 107 128 q24 25 35.5 85.5t30.5 126.5t62 108q39 37 90 37q84 0 151 -32.5t102 -101.5t35 -186q0 -93 -48 -192h176q104 0 180 -76t76 -179z" />
<glyph unicode="&#xf088;" d="M256 1088q0 26 -19 45t-45 19t-45 -19t-19 -45t19 -45t45 -19t45 19t19 45zM1408 512q0 35 -21.5 81t-53.5 47q15 17 25 47.5t10 55.5q0 69 -53 119q18 32 18 69t-17.5 73.5t-47.5 52.5q5 30 5 56q0 85 -49 126t-136 41h-128q-131 0 -342 -73q-5 -2 -29 -10.5 t-35.5 -12.5t-35 -11.5t-38 -11t-33 -6.5t-31.5 -3h-32v-640h32q16 0 35.5 -9t40 -27t38.5 -35.5t40 -44t34.5 -42.5t31.5 -41t23 -30q55 -68 77 -91q41 -43 59.5 -109.5t30.5 -125.5t38 -85q96 0 128 47t32 145q0 59 -48 160.5t-48 159.5h352q50 0 89 38.5t39 89.5z M1536 511q0 -103 -76 -179t-180 -76h-176q48 -99 48 -192q0 -118 -35 -186q-35 -69 -102 -101.5t-151 -32.5q-51 0 -90 37q-34 33 -54 82t-25.5 90.5t-17.5 84.5t-31 64q-48 50 -107 127q-101 131 -137 155h-274q-53 0 -90.5 37.5t-37.5 90.5v640q0 53 37.5 90.5t90.5 37.5 h288q22 0 138 40q128 44 223 66t200 22h112q140 0 226.5 -79t85.5 -216v-5q60 -77 60 -178q0 -22 -3 -43q38 -67 38 -144q0 -36 -9 -69q49 -74 49 -163z" />
<glyph unicode="&#xf089;" horiz-adv-x="896" d="M832 1504v-1339l-449 -236q-22 -12 -40 -12q-21 0 -31.5 14.5t-10.5 35.5q0 6 2 20l86 500l-364 354q-25 27 -25 48q0 37 56 46l502 73l225 455q19 41 49 41z" />
<glyph unicode="&#xf08a;" horiz-adv-x="1792" d="M1664 940q0 81 -21.5 143t-55 98.5t-81.5 59.5t-94 31t-98 8t-112 -25.5t-110.5 -64t-86.5 -72t-60 -61.5q-18 -22 -49 -22t-49 22q-24 28 -60 61.5t-86.5 72t-110.5 64t-112 25.5t-98 -8t-94 -31t-81.5 -59.5t-55 -98.5t-21.5 -143q0 -168 187 -355l581 -560l580 559 q188 188 188 356zM1792 940q0 -221 -229 -450l-623 -600q-18 -18 -44 -18t-44 18l-624 602q-10 8 -27.5 26t-55.5 65.5t-68 97.5t-53.5 121t-23.5 138q0 220 127 344t351 124q62 0 126.5 -21.5t120 -58t95.5 -68.5t76 -68q36 36 76 68t95.5 68.5t120 58t126.5 21.5 q224 0 351 -124t127 -344z" />
<glyph unicode="&#xf08b;" horiz-adv-x="1664" d="M640 96q0 -4 1 -20t0.5 -26.5t-3 -23.5t-10 -19.5t-20.5 -6.5h-320q-119 0 -203.5 84.5t-84.5 203.5v704q0 119 84.5 203.5t203.5 84.5h320q13 0 22.5 -9.5t9.5 -22.5q0 -4 1 -20t0.5 -26.5t-3 -23.5t-10 -19.5t-20.5 -6.5h-320q-66 0 -113 -47t-47 -113v-704 q0 -66 47 -113t113 -47h288h11h13t11.5 -1t11.5 -3t8 -5.5t7 -9t2 -13.5zM1568 640q0 -26 -19 -45l-544 -544q-19 -19 -45 -19t-45 19t-19 45v288h-448q-26 0 -45 19t-19 45v384q0 26 19 45t45 19h448v288q0 26 19 45t45 19t45 -19l544 -544q19 -19 19 -45z" />
<glyph unicode="&#xf08c;" d="M237 122h231v694h-231v-694zM483 1030q-1 52 -36 86t-93 34t-94.5 -34t-36.5 -86q0 -51 35.5 -85.5t92.5 -34.5h1q59 0 95 34.5t36 85.5zM1068 122h231v398q0 154 -73 233t-193 79q-136 0 -209 -117h2v101h-231q3 -66 0 -694h231v388q0 38 7 56q15 35 45 59.5t74 24.5 q116 0 116 -157v-371zM1536 1120v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf08d;" horiz-adv-x="1152" d="M480 672v448q0 14 -9 23t-23 9t-23 -9t-9 -23v-448q0 -14 9 -23t23 -9t23 9t9 23zM1152 320q0 -26 -19 -45t-45 -19h-429l-51 -483q-2 -12 -10.5 -20.5t-20.5 -8.5h-1q-27 0 -32 27l-76 485h-404q-26 0 -45 19t-19 45q0 123 78.5 221.5t177.5 98.5v512q-52 0 -90 38 t-38 90t38 90t90 38h640q52 0 90 -38t38 -90t-38 -90t-90 -38v-512q99 0 177.5 -98.5t78.5 -221.5z" />
<glyph unicode="&#xf08e;" horiz-adv-x="1792" d="M1408 608v-320q0 -119 -84.5 -203.5t-203.5 -84.5h-832q-119 0 -203.5 84.5t-84.5 203.5v832q0 119 84.5 203.5t203.5 84.5h704q14 0 23 -9t9 -23v-64q0 -14 -9 -23t-23 -9h-704q-66 0 -113 -47t-47 -113v-832q0 -66 47 -113t113 -47h832q66 0 113 47t47 113v320 q0 14 9 23t23 9h64q14 0 23 -9t9 -23zM1792 1472v-512q0 -26 -19 -45t-45 -19t-45 19l-176 176l-652 -652q-10 -10 -23 -10t-23 10l-114 114q-10 10 -10 23t10 23l652 652l-176 176q-19 19 -19 45t19 45t45 19h512q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf090;" d="M1184 640q0 -26 -19 -45l-544 -544q-19 -19 -45 -19t-45 19t-19 45v288h-448q-26 0 -45 19t-19 45v384q0 26 19 45t45 19h448v288q0 26 19 45t45 19t45 -19l544 -544q19 -19 19 -45zM1536 992v-704q0 -119 -84.5 -203.5t-203.5 -84.5h-320q-13 0 -22.5 9.5t-9.5 22.5 q0 4 -1 20t-0.5 26.5t3 23.5t10 19.5t20.5 6.5h320q66 0 113 47t47 113v704q0 66 -47 113t-113 47h-288h-11h-13t-11.5 1t-11.5 3t-8 5.5t-7 9t-2 13.5q0 4 -1 20t-0.5 26.5t3 23.5t10 19.5t20.5 6.5h320q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf091;" horiz-adv-x="1664" d="M458 653q-74 162 -74 371h-256v-96q0 -78 94.5 -162t235.5 -113zM1536 928v96h-256q0 -209 -74 -371q141 29 235.5 113t94.5 162zM1664 1056v-128q0 -71 -41.5 -143t-112 -130t-173 -97.5t-215.5 -44.5q-42 -54 -95 -95q-38 -34 -52.5 -72.5t-14.5 -89.5q0 -54 30.5 -91 t97.5 -37q75 0 133.5 -45.5t58.5 -114.5v-64q0 -14 -9 -23t-23 -9h-832q-14 0 -23 9t-9 23v64q0 69 58.5 114.5t133.5 45.5q67 0 97.5 37t30.5 91q0 51 -14.5 89.5t-52.5 72.5q-53 41 -95 95q-113 5 -215.5 44.5t-173 97.5t-112 130t-41.5 143v128q0 40 28 68t68 28h288v96 q0 66 47 113t113 47h576q66 0 113 -47t47 -113v-96h288q40 0 68 -28t28 -68z" />
<glyph unicode="&#xf092;" d="M394 184q-8 -9 -20 3q-13 11 -4 19q8 9 20 -3q12 -11 4 -19zM352 245q9 -12 0 -19q-8 -6 -17 7t0 18q9 7 17 -6zM291 305q-5 -7 -13 -2q-10 5 -7 12q3 5 13 2q10 -5 7 -12zM322 271q-6 -7 -16 3q-9 11 -2 16q6 6 16 -3q9 -11 2 -16zM451 159q-4 -12 -19 -6q-17 4 -13 15 t19 7q16 -5 13 -16zM514 154q0 -11 -16 -11q-17 -2 -17 11q0 11 16 11q17 2 17 -11zM572 164q2 -10 -14 -14t-18 8t14 15q16 2 18 -9zM1536 1120v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-224q-16 0 -24.5 1t-19.5 5t-16 14.5t-5 27.5v239q0 97 -52 142q57 6 102.5 18t94 39 t81 66.5t53 105t20.5 150.5q0 121 -79 206q37 91 -8 204q-28 9 -81 -11t-92 -44l-38 -24q-93 26 -192 26t-192 -26q-16 11 -42.5 27t-83.5 38.5t-86 13.5q-44 -113 -7 -204q-79 -85 -79 -206q0 -85 20.5 -150t52.5 -105t80.5 -67t94 -39t102.5 -18q-40 -36 -49 -103 q-21 -10 -45 -15t-57 -5t-65.5 21.5t-55.5 62.5q-19 32 -48.5 52t-49.5 24l-20 3q-21 0 -29 -4.5t-5 -11.5t9 -14t13 -12l7 -5q22 -10 43.5 -38t31.5 -51l10 -23q13 -38 44 -61.5t67 -30t69.5 -7t55.5 3.5l23 4q0 -38 0.5 -103t0.5 -68q0 -22 -11 -33.5t-22 -13t-33 -1.5 h-224q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf093;" horiz-adv-x="1664" d="M1280 64q0 26 -19 45t-45 19t-45 -19t-19 -45t19 -45t45 -19t45 19t19 45zM1536 64q0 26 -19 45t-45 19t-45 -19t-19 -45t19 -45t45 -19t45 19t19 45zM1664 288v-320q0 -40 -28 -68t-68 -28h-1472q-40 0 -68 28t-28 68v320q0 40 28 68t68 28h427q21 -56 70.5 -92 t110.5 -36h256q61 0 110.5 36t70.5 92h427q40 0 68 -28t28 -68zM1339 936q-17 -40 -59 -40h-256v-448q0 -26 -19 -45t-45 -19h-256q-26 0 -45 19t-19 45v448h-256q-42 0 -59 40q-17 39 14 69l448 448q18 19 45 19t45 -19l448 -448q31 -30 14 -69z" />
<glyph unicode="&#xf094;" d="M1407 710q0 44 -7 113.5t-18 96.5q-12 30 -17 44t-9 36.5t-4 48.5q0 23 5 68.5t5 67.5q0 37 -10 55q-4 1 -13 1q-19 0 -58 -4.5t-59 -4.5q-60 0 -176 24t-175 24q-43 0 -94.5 -11.5t-85 -23.5t-89.5 -34q-137 -54 -202 -103q-96 -73 -159.5 -189.5t-88 -236t-24.5 -248.5 q0 -40 12.5 -120t12.5 -121q0 -23 -11 -66.5t-11 -65.5t12 -36.5t34 -14.5q24 0 72.5 11t73.5 11q57 0 169.5 -15.5t169.5 -15.5q181 0 284 36q129 45 235.5 152.5t166 245.5t59.5 275zM1535 712q0 -165 -70 -327.5t-196 -288t-281 -180.5q-124 -44 -326 -44 q-57 0 -170 14.5t-169 14.5q-24 0 -72.5 -14.5t-73.5 -14.5q-73 0 -123.5 55.5t-50.5 128.5q0 24 11 68t11 67q0 40 -12.5 120.5t-12.5 121.5q0 111 18 217.5t54.5 209.5t100.5 194t150 156q78 59 232 120q194 78 316 78q60 0 175.5 -24t173.5 -24q19 0 57 5t58 5 q81 0 118 -50.5t37 -134.5q0 -23 -5 -68t-5 -68q0 -10 1 -18.5t3 -17t4 -13.5t6.5 -16t6.5 -17q16 -40 25 -118.5t9 -136.5z" />
<glyph unicode="&#xf095;" horiz-adv-x="1408" d="M1408 296q0 -27 -10 -70.5t-21 -68.5q-21 -50 -122 -106q-94 -51 -186 -51q-27 0 -52.5 3.5t-57.5 12.5t-47.5 14.5t-55.5 20.5t-49 18q-98 35 -175 83q-128 79 -264.5 215.5t-215.5 264.5q-48 77 -83 175q-3 9 -18 49t-20.5 55.5t-14.5 47.5t-12.5 57.5t-3.5 52.5 q0 92 51 186q56 101 106 122q25 11 68.5 21t70.5 10q14 0 21 -3q18 -6 53 -76q11 -19 30 -54t35 -63.5t31 -53.5q3 -4 17.5 -25t21.5 -35.5t7 -28.5q0 -20 -28.5 -50t-62 -55t-62 -53t-28.5 -46q0 -9 5 -22.5t8.5 -20.5t14 -24t11.5 -19q76 -137 174 -235t235 -174 q2 -1 19 -11.5t24 -14t20.5 -8.5t22.5 -5q18 0 46 28.5t53 62t55 62t50 28.5q14 0 28.5 -7t35.5 -21.5t25 -17.5q25 -15 53.5 -31t63.5 -35t54 -30q70 -35 76 -53q3 -7 3 -21z" />
<glyph unicode="&#xf096;" horiz-adv-x="1408" d="M1120 1280h-832q-66 0 -113 -47t-47 -113v-832q0 -66 47 -113t113 -47h832q66 0 113 47t47 113v832q0 66 -47 113t-113 47zM1408 1120v-832q0 -119 -84.5 -203.5t-203.5 -84.5h-832q-119 0 -203.5 84.5t-84.5 203.5v832q0 119 84.5 203.5t203.5 84.5h832 q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf097;" horiz-adv-x="1280" d="M1152 1280h-1024v-1242l423 406l89 85l89 -85l423 -406v1242zM1164 1408q23 0 44 -9q33 -13 52.5 -41t19.5 -62v-1289q0 -34 -19.5 -62t-52.5 -41q-19 -8 -44 -8q-48 0 -83 32l-441 424l-441 -424q-36 -33 -83 -33q-23 0 -44 9q-33 13 -52.5 41t-19.5 62v1289 q0 34 19.5 62t52.5 41q21 9 44 9h1048z" />
<glyph unicode="&#xf098;" d="M1280 343q0 11 -2 16q-3 8 -38.5 29.5t-88.5 49.5l-53 29q-5 3 -19 13t-25 15t-21 5q-18 0 -47 -32.5t-57 -65.5t-44 -33q-7 0 -16.5 3.5t-15.5 6.5t-17 9.5t-14 8.5q-99 55 -170.5 126.5t-126.5 170.5q-2 3 -8.5 14t-9.5 17t-6.5 15.5t-3.5 16.5q0 13 20.5 33.5t45 38.5 t45 39.5t20.5 36.5q0 10 -5 21t-15 25t-13 19q-3 6 -15 28.5t-25 45.5t-26.5 47.5t-25 40.5t-16.5 18t-16 2q-48 0 -101 -22q-46 -21 -80 -94.5t-34 -130.5q0 -16 2.5 -34t5 -30.5t9 -33t10 -29.5t12.5 -33t11 -30q60 -164 216.5 -320.5t320.5 -216.5q6 -2 30 -11t33 -12.5 t29.5 -10t33 -9t30.5 -5t34 -2.5q57 0 130.5 34t94.5 80q22 53 22 101zM1536 1120v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf099;" horiz-adv-x="1664" d="M1620 1128q-67 -98 -162 -167q1 -14 1 -42q0 -130 -38 -259.5t-115.5 -248.5t-184.5 -210.5t-258 -146t-323 -54.5q-271 0 -496 145q35 -4 78 -4q225 0 401 138q-105 2 -188 64.5t-114 159.5q33 -5 61 -5q43 0 85 11q-112 23 -185.5 111.5t-73.5 205.5v4q68 -38 146 -41 q-66 44 -105 115t-39 154q0 88 44 163q121 -149 294.5 -238.5t371.5 -99.5q-8 38 -8 74q0 134 94.5 228.5t228.5 94.5q140 0 236 -102q109 21 205 78q-37 -115 -142 -178q93 10 186 50z" />
<glyph unicode="&#xf09a;" horiz-adv-x="1024" d="M959 1524v-264h-157q-86 0 -116 -36t-30 -108v-189h293l-39 -296h-254v-759h-306v759h-255v296h255v218q0 186 104 288.5t277 102.5q147 0 228 -12z" />
<glyph unicode="&#xf09b;" d="M1536 640q0 -251 -146.5 -451.5t-378.5 -277.5q-27 -5 -39.5 7t-12.5 30v211q0 97 -52 142q57 6 102.5 18t94 39t81 66.5t53 105t20.5 150.5q0 121 -79 206q37 91 -8 204q-28 9 -81 -11t-92 -44l-38 -24q-93 26 -192 26t-192 -26q-16 11 -42.5 27t-83.5 38.5t-86 13.5 q-44 -113 -7 -204q-79 -85 -79 -206q0 -85 20.5 -150t52.5 -105t80.5 -67t94 -39t102.5 -18q-40 -36 -49 -103q-21 -10 -45 -15t-57 -5t-65.5 21.5t-55.5 62.5q-19 32 -48.5 52t-49.5 24l-20 3q-21 0 -29 -4.5t-5 -11.5t9 -14t13 -12l7 -5q22 -10 43.5 -38t31.5 -51l10 -23 q13 -38 44 -61.5t67 -30t69.5 -7t55.5 3.5l23 4q0 -38 0.5 -89t0.5 -54q0 -18 -13 -30t-40 -7q-232 77 -378.5 277.5t-146.5 451.5q0 209 103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf09c;" horiz-adv-x="1664" d="M1664 960v-256q0 -26 -19 -45t-45 -19h-64q-26 0 -45 19t-19 45v256q0 106 -75 181t-181 75t-181 -75t-75 -181v-192h96q40 0 68 -28t28 -68v-576q0 -40 -28 -68t-68 -28h-960q-40 0 -68 28t-28 68v576q0 40 28 68t68 28h672v192q0 185 131.5 316.5t316.5 131.5 t316.5 -131.5t131.5 -316.5z" />
<glyph unicode="&#xf09d;" horiz-adv-x="1920" d="M1760 1408q66 0 113 -47t47 -113v-1216q0 -66 -47 -113t-113 -47h-1600q-66 0 -113 47t-47 113v1216q0 66 47 113t113 47h1600zM160 1280q-13 0 -22.5 -9.5t-9.5 -22.5v-224h1664v224q0 13 -9.5 22.5t-22.5 9.5h-1600zM1760 0q13 0 22.5 9.5t9.5 22.5v608h-1664v-608 q0 -13 9.5 -22.5t22.5 -9.5h1600zM256 128v128h256v-128h-256zM640 128v128h384v-128h-384z" />
<glyph unicode="&#xf09e;" horiz-adv-x="1408" d="M384 192q0 -80 -56 -136t-136 -56t-136 56t-56 136t56 136t136 56t136 -56t56 -136zM896 69q2 -28 -17 -48q-18 -21 -47 -21h-135q-25 0 -43 16.5t-20 41.5q-22 229 -184.5 391.5t-391.5 184.5q-25 2 -41.5 20t-16.5 43v135q0 29 21 47q17 17 43 17h5q160 -13 306 -80.5 t259 -181.5q114 -113 181.5 -259t80.5 -306zM1408 67q2 -27 -18 -47q-18 -20 -46 -20h-143q-26 0 -44.5 17.5t-19.5 42.5q-12 215 -101 408.5t-231.5 336t-336 231.5t-408.5 102q-25 1 -42.5 19.5t-17.5 43.5v143q0 28 20 46q18 18 44 18h3q262 -13 501.5 -120t425.5 -294 q187 -186 294 -425.5t120 -501.5z" />
<glyph unicode="&#xf0a0;" d="M1040 320q0 -33 -23.5 -56.5t-56.5 -23.5t-56.5 23.5t-23.5 56.5t23.5 56.5t56.5 23.5t56.5 -23.5t23.5 -56.5zM1296 320q0 -33 -23.5 -56.5t-56.5 -23.5t-56.5 23.5t-23.5 56.5t23.5 56.5t56.5 23.5t56.5 -23.5t23.5 -56.5zM1408 160v320q0 13 -9.5 22.5t-22.5 9.5 h-1216q-13 0 -22.5 -9.5t-9.5 -22.5v-320q0 -13 9.5 -22.5t22.5 -9.5h1216q13 0 22.5 9.5t9.5 22.5zM178 640h1180l-157 482q-4 13 -16 21.5t-26 8.5h-782q-14 0 -26 -8.5t-16 -21.5zM1536 480v-320q0 -66 -47 -113t-113 -47h-1216q-66 0 -113 47t-47 113v320q0 25 16 75 l197 606q17 53 63 86t101 33h782q55 0 101 -33t63 -86l197 -606q16 -50 16 -75z" />
<glyph unicode="&#xf0a1;" horiz-adv-x="1792" d="M1664 896q53 0 90.5 -37.5t37.5 -90.5t-37.5 -90.5t-90.5 -37.5v-384q0 -52 -38 -90t-90 -38q-417 347 -812 380q-58 -19 -91 -66t-31 -100.5t40 -92.5q-20 -33 -23 -65.5t6 -58t33.5 -55t48 -50t61.5 -50.5q-29 -58 -111.5 -83t-168.5 -11.5t-132 55.5q-7 23 -29.5 87.5 t-32 94.5t-23 89t-15 101t3.5 98.5t22 110.5h-122q-66 0 -113 47t-47 113v192q0 66 47 113t113 47h480q435 0 896 384q52 0 90 -38t38 -90v-384zM1536 292v954q-394 -302 -768 -343v-270q377 -42 768 -341z" />
<glyph unicode="&#xf0a2;" horiz-adv-x="1792" d="M912 -160q0 16 -16 16q-59 0 -101.5 42.5t-42.5 101.5q0 16 -16 16t-16 -16q0 -73 51.5 -124.5t124.5 -51.5q16 0 16 16zM246 128h1300q-266 300 -266 832q0 51 -24 105t-69 103t-121.5 80.5t-169.5 31.5t-169.5 -31.5t-121.5 -80.5t-69 -103t-24 -105q0 -532 -266 -832z M1728 128q0 -52 -38 -90t-90 -38h-448q0 -106 -75 -181t-181 -75t-181 75t-75 181h-448q-52 0 -90 38t-38 90q50 42 91 88t85 119.5t74.5 158.5t50 206t19.5 260q0 152 117 282.5t307 158.5q-8 19 -8 39q0 40 28 68t68 28t68 -28t28 -68q0 -20 -8 -39q190 -28 307 -158.5 t117 -282.5q0 -139 19.5 -260t50 -206t74.5 -158.5t85 -119.5t91 -88z" />
<glyph unicode="&#xf0a3;" d="M1376 640l138 -135q30 -28 20 -70q-12 -41 -52 -51l-188 -48l53 -186q12 -41 -19 -70q-29 -31 -70 -19l-186 53l-48 -188q-10 -40 -51 -52q-12 -2 -19 -2q-31 0 -51 22l-135 138l-135 -138q-28 -30 -70 -20q-41 11 -51 52l-48 188l-186 -53q-41 -12 -70 19q-31 29 -19 70 l53 186l-188 48q-40 10 -52 51q-10 42 20 70l138 135l-138 135q-30 28 -20 70q12 41 52 51l188 48l-53 186q-12 41 19 70q29 31 70 19l186 -53l48 188q10 41 51 51q41 12 70 -19l135 -139l135 139q29 30 70 19q41 -10 51 -51l48 -188l186 53q41 12 70 -19q31 -29 19 -70 l-53 -186l188 -48q40 -10 52 -51q10 -42 -20 -70z" />
<glyph unicode="&#xf0a4;" horiz-adv-x="1792" d="M256 192q0 26 -19 45t-45 19t-45 -19t-19 -45t19 -45t45 -19t45 19t19 45zM1664 768q0 51 -39 89.5t-89 38.5h-576q0 20 15 48.5t33 55t33 68t15 84.5q0 67 -44.5 97.5t-115.5 30.5q-24 0 -90 -139q-24 -44 -37 -65q-40 -64 -112 -145q-71 -81 -101 -106 q-69 -57 -140 -57h-32v-640h32q72 0 167 -32t193.5 -64t179.5 -32q189 0 189 167q0 26 -5 56q30 16 47.5 52.5t17.5 73.5t-18 69q53 50 53 119q0 25 -10 55.5t-25 47.5h331q52 0 90 38t38 90zM1792 769q0 -105 -75.5 -181t-180.5 -76h-169q-4 -62 -37 -119q3 -21 3 -43 q0 -101 -60 -178q1 -139 -85 -219.5t-227 -80.5q-133 0 -322 69q-164 59 -223 59h-288q-53 0 -90.5 37.5t-37.5 90.5v640q0 53 37.5 90.5t90.5 37.5h288q10 0 21.5 4.5t23.5 14t22.5 18t24 22.5t20.5 21.5t19 21.5t14 17q65 74 100 129q13 21 33 62t37 72t40.5 63t55 49.5 t69.5 17.5q125 0 206.5 -67t81.5 -189q0 -68 -22 -128h374q104 0 180 -76t76 -179z" />
<glyph unicode="&#xf0a5;" horiz-adv-x="1792" d="M1376 128h32v640h-32q-35 0 -67.5 12t-62.5 37t-50 46t-49 54q-2 3 -3.5 4.5t-4 4.5t-4.5 5q-72 81 -112 145q-14 22 -38 68q-1 3 -10.5 22.5t-18.5 36t-20 35.5t-21.5 30.5t-18.5 11.5q-71 0 -115.5 -30.5t-44.5 -97.5q0 -43 15 -84.5t33 -68t33 -55t15 -48.5h-576 q-50 0 -89 -38.5t-39 -89.5q0 -52 38 -90t90 -38h331q-15 -17 -25 -47.5t-10 -55.5q0 -69 53 -119q-18 -32 -18 -69t17.5 -73.5t47.5 -52.5q-4 -24 -4 -56q0 -85 48.5 -126t135.5 -41q84 0 183 32t194 64t167 32zM1664 192q0 26 -19 45t-45 19t-45 -19t-19 -45t19 -45 t45 -19t45 19t19 45zM1792 768v-640q0 -53 -37.5 -90.5t-90.5 -37.5h-288q-59 0 -223 -59q-190 -69 -317 -69q-142 0 -230 77.5t-87 217.5l1 5q-61 76 -61 178q0 22 3 43q-33 57 -37 119h-169q-105 0 -180.5 76t-75.5 181q0 103 76 179t180 76h374q-22 60 -22 128 q0 122 81.5 189t206.5 67q38 0 69.5 -17.5t55 -49.5t40.5 -63t37 -72t33 -62q35 -55 100 -129q2 -3 14 -17t19 -21.5t20.5 -21.5t24 -22.5t22.5 -18t23.5 -14t21.5 -4.5h288q53 0 90.5 -37.5t37.5 -90.5z" />
<glyph unicode="&#xf0a6;" d="M1280 -64q0 26 -19 45t-45 19t-45 -19t-19 -45t19 -45t45 -19t45 19t19 45zM1408 700q0 189 -167 189q-26 0 -56 -5q-16 30 -52.5 47.5t-73.5 17.5t-69 -18q-50 53 -119 53q-25 0 -55.5 -10t-47.5 -25v331q0 52 -38 90t-90 38q-51 0 -89.5 -39t-38.5 -89v-576 q-20 0 -48.5 15t-55 33t-68 33t-84.5 15q-67 0 -97.5 -44.5t-30.5 -115.5q0 -24 139 -90q44 -24 65 -37q64 -40 145 -112q81 -71 106 -101q57 -69 57 -140v-32h640v32q0 72 32 167t64 193.5t32 179.5zM1536 705q0 -133 -69 -322q-59 -164 -59 -223v-288q0 -53 -37.5 -90.5 t-90.5 -37.5h-640q-53 0 -90.5 37.5t-37.5 90.5v288q0 10 -4.5 21.5t-14 23.5t-18 22.5t-22.5 24t-21.5 20.5t-21.5 19t-17 14q-74 65 -129 100q-21 13 -62 33t-72 37t-63 40.5t-49.5 55t-17.5 69.5q0 125 67 206.5t189 81.5q68 0 128 -22v374q0 104 76 180t179 76 q105 0 181 -75.5t76 -180.5v-169q62 -4 119 -37q21 3 43 3q101 0 178 -60q139 1 219.5 -85t80.5 -227z" />
<glyph unicode="&#xf0a7;" d="M1408 576q0 84 -32 183t-64 194t-32 167v32h-640v-32q0 -35 -12 -67.5t-37 -62.5t-46 -50t-54 -49q-9 -8 -14 -12q-81 -72 -145 -112q-22 -14 -68 -38q-3 -1 -22.5 -10.5t-36 -18.5t-35.5 -20t-30.5 -21.5t-11.5 -18.5q0 -71 30.5 -115.5t97.5 -44.5q43 0 84.5 15t68 33 t55 33t48.5 15v-576q0 -50 38.5 -89t89.5 -39q52 0 90 38t38 90v331q46 -35 103 -35q69 0 119 53q32 -18 69 -18t73.5 17.5t52.5 47.5q24 -4 56 -4q85 0 126 48.5t41 135.5zM1280 1344q0 26 -19 45t-45 19t-45 -19t-19 -45t19 -45t45 -19t45 19t19 45zM1536 580 q0 -142 -77.5 -230t-217.5 -87l-5 1q-76 -61 -178 -61q-22 0 -43 3q-54 -30 -119 -37v-169q0 -105 -76 -180.5t-181 -75.5q-103 0 -179 76t-76 180v374q-54 -22 -128 -22q-121 0 -188.5 81.5t-67.5 206.5q0 38 17.5 69.5t49.5 55t63 40.5t72 37t62 33q55 35 129 100 q3 2 17 14t21.5 19t21.5 20.5t22.5 24t18 22.5t14 23.5t4.5 21.5v288q0 53 37.5 90.5t90.5 37.5h640q53 0 90.5 -37.5t37.5 -90.5v-288q0 -59 59 -223q69 -190 69 -317z" />
<glyph unicode="&#xf0a8;" d="M1280 576v128q0 26 -19 45t-45 19h-502l189 189q19 19 19 45t-19 45l-91 91q-18 18 -45 18t-45 -18l-362 -362l-91 -91q-18 -18 -18 -45t18 -45l91 -91l362 -362q18 -18 45 -18t45 18l91 91q18 18 18 45t-18 45l-189 189h502q26 0 45 19t19 45zM1536 640 q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf0a9;" d="M1285 640q0 27 -18 45l-91 91l-362 362q-18 18 -45 18t-45 -18l-91 -91q-18 -18 -18 -45t18 -45l189 -189h-502q-26 0 -45 -19t-19 -45v-128q0 -26 19 -45t45 -19h502l-189 -189q-19 -19 -19 -45t19 -45l91 -91q18 -18 45 -18t45 18l362 362l91 91q18 18 18 45zM1536 640 q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf0aa;" d="M1284 641q0 27 -18 45l-362 362l-91 91q-18 18 -45 18t-45 -18l-91 -91l-362 -362q-18 -18 -18 -45t18 -45l91 -91q18 -18 45 -18t45 18l189 189v-502q0 -26 19 -45t45 -19h128q26 0 45 19t19 45v502l189 -189q19 -19 45 -19t45 19l91 91q18 18 18 45zM1536 640 q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf0ab;" d="M1284 639q0 27 -18 45l-91 91q-18 18 -45 18t-45 -18l-189 -189v502q0 26 -19 45t-45 19h-128q-26 0 -45 -19t-19 -45v-502l-189 189q-19 19 -45 19t-45 -19l-91 -91q-18 -18 -18 -45t18 -45l362 -362l91 -91q18 -18 45 -18t45 18l91 91l362 362q18 18 18 45zM1536 640 q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf0ac;" d="M768 1408q209 0 385.5 -103t279.5 -279.5t103 -385.5t-103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103zM1042 887q-2 -1 -9.5 -9.5t-13.5 -9.5q2 0 4.5 5t5 11t3.5 7q6 7 22 15q14 6 52 12q34 8 51 -11 q-2 2 9.5 13t14.5 12q3 2 15 4.5t15 7.5l2 22q-12 -1 -17.5 7t-6.5 21q0 -2 -6 -8q0 7 -4.5 8t-11.5 -1t-9 -1q-10 3 -15 7.5t-8 16.5t-4 15q-2 5 -9.5 10.5t-9.5 10.5q-1 2 -2.5 5.5t-3 6.5t-4 5.5t-5.5 2.5t-7 -5t-7.5 -10t-4.5 -5q-3 2 -6 1.5t-4.5 -1t-4.5 -3t-5 -3.5 q-3 -2 -8.5 -3t-8.5 -2q15 5 -1 11q-10 4 -16 3q9 4 7.5 12t-8.5 14h5q-1 4 -8.5 8.5t-17.5 8.5t-13 6q-8 5 -34 9.5t-33 0.5q-5 -6 -4.5 -10.5t4 -14t3.5 -12.5q1 -6 -5.5 -13t-6.5 -12q0 -7 14 -15.5t10 -21.5q-3 -8 -16 -16t-16 -12q-5 -8 -1.5 -18.5t10.5 -16.5 q2 -2 1.5 -4t-3.5 -4.5t-5.5 -4t-6.5 -3.5l-3 -2q-11 -5 -20.5 6t-13.5 26q-7 25 -16 30q-23 8 -29 -1q-5 13 -41 26q-25 9 -58 4q6 1 0 15q-7 15 -19 12q3 6 4 17.5t1 13.5q3 13 12 23q1 1 7 8.5t9.5 13.5t0.5 6q35 -4 50 11q5 5 11.5 17t10.5 17q9 6 14 5.5t14.5 -5.5 t14.5 -5q14 -1 15.5 11t-7.5 20q12 -1 3 17q-5 7 -8 9q-12 4 -27 -5q-8 -4 2 -8q-1 1 -9.5 -10.5t-16.5 -17.5t-16 5q-1 1 -5.5 13.5t-9.5 13.5q-8 0 -16 -15q3 8 -11 15t-24 8q19 12 -8 27q-7 4 -20.5 5t-19.5 -4q-5 -7 -5.5 -11.5t5 -8t10.5 -5.5t11.5 -4t8.5 -3 q14 -10 8 -14q-2 -1 -8.5 -3.5t-11.5 -4.5t-6 -4q-3 -4 0 -14t-2 -14q-5 5 -9 17.5t-7 16.5q7 -9 -25 -6l-10 1q-4 0 -16 -2t-20.5 -1t-13.5 8q-4 8 0 20q1 4 4 2q-4 3 -11 9.5t-10 8.5q-46 -15 -94 -41q6 -1 12 1q5 2 13 6.5t10 5.5q34 14 42 7l5 5q14 -16 20 -25 q-7 4 -30 1q-20 -6 -22 -12q7 -12 5 -18q-4 3 -11.5 10t-14.5 11t-15 5q-16 0 -22 -1q-146 -80 -235 -222q7 -7 12 -8q4 -1 5 -9t2.5 -11t11.5 3q9 -8 3 -19q1 1 44 -27q19 -17 21 -21q3 -11 -10 -18q-1 2 -9 9t-9 4q-3 -5 0.5 -18.5t10.5 -12.5q-7 0 -9.5 -16t-2.5 -35.5 t-1 -23.5l2 -1q-3 -12 5.5 -34.5t21.5 -19.5q-13 -3 20 -43q6 -8 8 -9q3 -2 12 -7.5t15 -10t10 -10.5q4 -5 10 -22.5t14 -23.5q-2 -6 9.5 -20t10.5 -23q-1 0 -2.5 -1t-2.5 -1q3 -7 15.5 -14t15.5 -13q1 -3 2 -10t3 -11t8 -2q2 20 -24 62q-15 25 -17 29q-3 5 -5.5 15.5 t-4.5 14.5q2 0 6 -1.5t8.5 -3.5t7.5 -4t2 -3q-3 -7 2 -17.5t12 -18.5t17 -19t12 -13q6 -6 14 -19.5t0 -13.5q9 0 20 -10t17 -20q5 -8 8 -26t5 -24q2 -7 8.5 -13.5t12.5 -9.5l16 -8t13 -7q5 -2 18.5 -10.5t21.5 -11.5q10 -4 16 -4t14.5 2.5t13.5 3.5q15 2 29 -15t21 -21 q36 -19 55 -11q-2 -1 0.5 -7.5t8 -15.5t9 -14.5t5.5 -8.5q5 -6 18 -15t18 -15q6 4 7 9q-3 -8 7 -20t18 -10q14 3 14 32q-31 -15 -49 18q0 1 -2.5 5.5t-4 8.5t-2.5 8.5t0 7.5t5 3q9 0 10 3.5t-2 12.5t-4 13q-1 8 -11 20t-12 15q-5 -9 -16 -8t-16 9q0 -1 -1.5 -5.5t-1.5 -6.5 q-13 0 -15 1q1 3 2.5 17.5t3.5 22.5q1 4 5.5 12t7.5 14.5t4 12.5t-4.5 9.5t-17.5 2.5q-19 -1 -26 -20q-1 -3 -3 -10.5t-5 -11.5t-9 -7q-7 -3 -24 -2t-24 5q-13 8 -22.5 29t-9.5 37q0 10 2.5 26.5t3 25t-5.5 24.5q3 2 9 9.5t10 10.5q2 1 4.5 1.5t4.5 0t4 1.5t3 6q-1 1 -4 3 q-3 3 -4 3q7 -3 28.5 1.5t27.5 -1.5q15 -11 22 2q0 1 -2.5 9.5t-0.5 13.5q5 -27 29 -9q3 -3 15.5 -5t17.5 -5q3 -2 7 -5.5t5.5 -4.5t5 0.5t8.5 6.5q10 -14 12 -24q11 -40 19 -44q7 -3 11 -2t4.5 9.5t0 14t-1.5 12.5l-1 8v18l-1 8q-15 3 -18.5 12t1.5 18.5t15 18.5q1 1 8 3.5 t15.5 6.5t12.5 8q21 19 15 35q7 0 11 9q-1 0 -5 3t-7.5 5t-4.5 2q9 5 2 16q5 3 7.5 11t7.5 10q9 -12 21 -2q7 8 1 16q5 7 20.5 10.5t18.5 9.5q7 -2 8 2t1 12t3 12q4 5 15 9t13 5l17 11q3 4 0 4q18 -2 31 11q10 11 -6 20q3 6 -3 9.5t-15 5.5q3 1 11.5 0.5t10.5 1.5 q15 10 -7 16q-17 5 -43 -12zM879 10q206 36 351 189q-3 3 -12.5 4.5t-12.5 3.5q-18 7 -24 8q1 7 -2.5 13t-8 9t-12.5 8t-11 7q-2 2 -7 6t-7 5.5t-7.5 4.5t-8.5 2t-10 -1l-3 -1q-3 -1 -5.5 -2.5t-5.5 -3t-4 -3t0 -2.5q-21 17 -36 22q-5 1 -11 5.5t-10.5 7t-10 1.5t-11.5 -7 q-5 -5 -6 -15t-2 -13q-7 5 0 17.5t2 18.5q-3 6 -10.5 4.5t-12 -4.5t-11.5 -8.5t-9 -6.5t-8.5 -5.5t-8.5 -7.5q-3 -4 -6 -12t-5 -11q-2 4 -11.5 6.5t-9.5 5.5q2 -10 4 -35t5 -38q7 -31 -12 -48q-27 -25 -29 -40q-4 -22 12 -26q0 -7 -8 -20.5t-7 -21.5q0 -6 2 -16z" />
<glyph unicode="&#xf0ad;" horiz-adv-x="1664" d="M384 64q0 26 -19 45t-45 19t-45 -19t-19 -45t19 -45t45 -19t45 19t19 45zM1028 484l-682 -682q-37 -37 -90 -37q-52 0 -91 37l-106 108q-38 36 -38 90q0 53 38 91l681 681q39 -98 114.5 -173.5t173.5 -114.5zM1662 919q0 -39 -23 -106q-47 -134 -164.5 -217.5 t-258.5 -83.5q-185 0 -316.5 131.5t-131.5 316.5t131.5 316.5t316.5 131.5q58 0 121.5 -16.5t107.5 -46.5q16 -11 16 -28t-16 -28l-293 -169v-224l193 -107q5 3 79 48.5t135.5 81t70.5 35.5q15 0 23.5 -10t8.5 -25z" />
<glyph unicode="&#xf0ae;" horiz-adv-x="1792" d="M1024 128h640v128h-640v-128zM640 640h1024v128h-1024v-128zM1280 1152h384v128h-384v-128zM1792 320v-256q0 -26 -19 -45t-45 -19h-1664q-26 0 -45 19t-19 45v256q0 26 19 45t45 19h1664q26 0 45 -19t19 -45zM1792 832v-256q0 -26 -19 -45t-45 -19h-1664q-26 0 -45 19 t-19 45v256q0 26 19 45t45 19h1664q26 0 45 -19t19 -45zM1792 1344v-256q0 -26 -19 -45t-45 -19h-1664q-26 0 -45 19t-19 45v256q0 26 19 45t45 19h1664q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf0b0;" horiz-adv-x="1408" d="M1403 1241q17 -41 -14 -70l-493 -493v-742q0 -42 -39 -59q-13 -5 -25 -5q-27 0 -45 19l-256 256q-19 19 -19 45v486l-493 493q-31 29 -14 70q17 39 59 39h1280q42 0 59 -39z" />
<glyph unicode="&#xf0b1;" horiz-adv-x="1792" d="M640 1280h512v128h-512v-128zM1792 640v-480q0 -66 -47 -113t-113 -47h-1472q-66 0 -113 47t-47 113v480h672v-160q0 -26 19 -45t45 -19h320q26 0 45 19t19 45v160h672zM1024 640v-128h-256v128h256zM1792 1120v-384h-1792v384q0 66 47 113t113 47h352v160q0 40 28 68 t68 28h576q40 0 68 -28t28 -68v-160h352q66 0 113 -47t47 -113z" />
<glyph unicode="&#xf0b2;" d="M1283 995l-355 -355l355 -355l144 144q29 31 70 14q39 -17 39 -59v-448q0 -26 -19 -45t-45 -19h-448q-42 0 -59 40q-17 39 14 69l144 144l-355 355l-355 -355l144 -144q31 -30 14 -69q-17 -40 -59 -40h-448q-26 0 -45 19t-19 45v448q0 42 40 59q39 17 69 -14l144 -144 l355 355l-355 355l-144 -144q-19 -19 -45 -19q-12 0 -24 5q-40 17 -40 59v448q0 26 19 45t45 19h448q42 0 59 -40q17 -39 -14 -69l-144 -144l355 -355l355 355l-144 144q-31 30 -14 69q17 40 59 40h448q26 0 45 -19t19 -45v-448q0 -42 -39 -59q-13 -5 -25 -5q-26 0 -45 19z " />
<glyph unicode="&#xf0c0;" horiz-adv-x="1920" d="M593 640q-162 -5 -265 -128h-134q-82 0 -138 40.5t-56 118.5q0 353 124 353q6 0 43.5 -21t97.5 -42.5t119 -21.5q67 0 133 23q-5 -37 -5 -66q0 -139 81 -256zM1664 3q0 -120 -73 -189.5t-194 -69.5h-874q-121 0 -194 69.5t-73 189.5q0 53 3.5 103.5t14 109t26.5 108.5 t43 97.5t62 81t85.5 53.5t111.5 20q10 0 43 -21.5t73 -48t107 -48t135 -21.5t135 21.5t107 48t73 48t43 21.5q61 0 111.5 -20t85.5 -53.5t62 -81t43 -97.5t26.5 -108.5t14 -109t3.5 -103.5zM640 1280q0 -106 -75 -181t-181 -75t-181 75t-75 181t75 181t181 75t181 -75 t75 -181zM1344 896q0 -159 -112.5 -271.5t-271.5 -112.5t-271.5 112.5t-112.5 271.5t112.5 271.5t271.5 112.5t271.5 -112.5t112.5 -271.5zM1920 671q0 -78 -56 -118.5t-138 -40.5h-134q-103 123 -265 128q81 117 81 256q0 29 -5 66q66 -23 133 -23q59 0 119 21.5t97.5 42.5 t43.5 21q124 0 124 -353zM1792 1280q0 -106 -75 -181t-181 -75t-181 75t-75 181t75 181t181 75t181 -75t75 -181z" />
<glyph unicode="&#xf0c1;" horiz-adv-x="1664" d="M1456 320q0 40 -28 68l-208 208q-28 28 -68 28q-42 0 -72 -32q3 -3 19 -18.5t21.5 -21.5t15 -19t13 -25.5t3.5 -27.5q0 -40 -28 -68t-68 -28q-15 0 -27.5 3.5t-25.5 13t-19 15t-21.5 21.5t-18.5 19q-33 -31 -33 -73q0 -40 28 -68l206 -207q27 -27 68 -27q40 0 68 26 l147 146q28 28 28 67zM753 1025q0 40 -28 68l-206 207q-28 28 -68 28q-39 0 -68 -27l-147 -146q-28 -28 -28 -67q0 -40 28 -68l208 -208q27 -27 68 -27q42 0 72 31q-3 3 -19 18.5t-21.5 21.5t-15 19t-13 25.5t-3.5 27.5q0 40 28 68t68 28q15 0 27.5 -3.5t25.5 -13t19 -15 t21.5 -21.5t18.5 -19q33 31 33 73zM1648 320q0 -120 -85 -203l-147 -146q-83 -83 -203 -83q-121 0 -204 85l-206 207q-83 83 -83 203q0 123 88 209l-88 88q-86 -88 -208 -88q-120 0 -204 84l-208 208q-84 84 -84 204t85 203l147 146q83 83 203 83q121 0 204 -85l206 -207 q83 -83 83 -203q0 -123 -88 -209l88 -88q86 88 208 88q120 0 204 -84l208 -208q84 -84 84 -204z" />
<glyph unicode="&#xf0c2;" horiz-adv-x="1920" d="M1920 384q0 -159 -112.5 -271.5t-271.5 -112.5h-1088q-185 0 -316.5 131.5t-131.5 316.5q0 132 71 241.5t187 163.5q-2 28 -2 43q0 212 150 362t362 150q158 0 286.5 -88t187.5 -230q70 62 166 62q106 0 181 -75t75 -181q0 -75 -41 -138q129 -30 213 -134.5t84 -239.5z " />
<glyph unicode="&#xf0c3;" horiz-adv-x="1664" d="M1527 88q56 -89 21.5 -152.5t-140.5 -63.5h-1152q-106 0 -140.5 63.5t21.5 152.5l503 793v399h-64q-26 0 -45 19t-19 45t19 45t45 19h512q26 0 45 -19t19 -45t-19 -45t-45 -19h-64v-399zM748 813l-272 -429h712l-272 429l-20 31v37v399h-128v-399v-37z" />
<glyph unicode="&#xf0c4;" horiz-adv-x="1792" d="M960 640q26 0 45 -19t19 -45t-19 -45t-45 -19t-45 19t-19 45t19 45t45 19zM1260 576l507 -398q28 -20 25 -56q-5 -35 -35 -51l-128 -64q-13 -7 -29 -7q-17 0 -31 8l-690 387l-110 -66q-8 -4 -12 -5q14 -49 10 -97q-7 -77 -56 -147.5t-132 -123.5q-132 -84 -277 -84 q-136 0 -222 78q-90 84 -79 207q7 76 56 147t131 124q132 84 278 84q83 0 151 -31q9 13 22 22l122 73l-122 73q-13 9 -22 22q-68 -31 -151 -31q-146 0 -278 84q-82 53 -131 124t-56 147q-5 59 15.5 113t63.5 93q85 79 222 79q145 0 277 -84q83 -52 132 -123t56 -148 q4 -48 -10 -97q4 -1 12 -5l110 -66l690 387q14 8 31 8q16 0 29 -7l128 -64q30 -16 35 -51q3 -36 -25 -56zM579 836q46 42 21 108t-106 117q-92 59 -192 59q-74 0 -113 -36q-46 -42 -21 -108t106 -117q92 -59 192 -59q74 0 113 36zM494 91q81 51 106 117t-21 108 q-39 36 -113 36q-100 0 -192 -59q-81 -51 -106 -117t21 -108q39 -36 113 -36q100 0 192 59zM672 704l96 -58v11q0 36 33 56l14 8l-79 47l-26 -26q-3 -3 -10 -11t-12 -12q-2 -2 -4 -3.5t-3 -2.5zM896 480l96 -32l736 576l-128 64l-768 -431v-113l-160 -96l9 -8q2 -2 7 -6 q4 -4 11 -12t11 -12l26 -26zM1600 64l128 64l-520 408l-177 -138q-2 -3 -13 -7z" />
<glyph unicode="&#xf0c5;" horiz-adv-x="1792" d="M1696 1152q40 0 68 -28t28 -68v-1216q0 -40 -28 -68t-68 -28h-960q-40 0 -68 28t-28 68v288h-544q-40 0 -68 28t-28 68v672q0 40 20 88t48 76l408 408q28 28 76 48t88 20h416q40 0 68 -28t28 -68v-328q68 40 128 40h416zM1152 939l-299 -299h299v299zM512 1323l-299 -299 h299v299zM708 676l316 316v416h-384v-416q0 -40 -28 -68t-68 -28h-416v-640h512v256q0 40 20 88t48 76zM1664 -128v1152h-384v-416q0 -40 -28 -68t-68 -28h-416v-640h896z" />
<glyph unicode="&#xf0c6;" horiz-adv-x="1408" d="M1404 151q0 -117 -79 -196t-196 -79q-135 0 -235 100l-777 776q-113 115 -113 271q0 159 110 270t269 111q158 0 273 -113l605 -606q10 -10 10 -22q0 -16 -30.5 -46.5t-46.5 -30.5q-13 0 -23 10l-606 607q-79 77 -181 77q-106 0 -179 -75t-73 -181q0 -105 76 -181 l776 -777q63 -63 145 -63q64 0 106 42t42 106q0 82 -63 145l-581 581q-26 24 -60 24q-29 0 -48 -19t-19 -48q0 -32 25 -59l410 -410q10 -10 10 -22q0 -16 -31 -47t-47 -31q-12 0 -22 10l-410 410q-63 61 -63 149q0 82 57 139t139 57q88 0 149 -63l581 -581q100 -98 100 -235 z" />
<glyph unicode="&#xf0c7;" d="M384 0h768v384h-768v-384zM1280 0h128v896q0 14 -10 38.5t-20 34.5l-281 281q-10 10 -34 20t-39 10v-416q0 -40 -28 -68t-68 -28h-576q-40 0 -68 28t-28 68v416h-128v-1280h128v416q0 40 28 68t68 28h832q40 0 68 -28t28 -68v-416zM896 928v320q0 13 -9.5 22.5t-22.5 9.5 h-192q-13 0 -22.5 -9.5t-9.5 -22.5v-320q0 -13 9.5 -22.5t22.5 -9.5h192q13 0 22.5 9.5t9.5 22.5zM1536 896v-928q0 -40 -28 -68t-68 -28h-1344q-40 0 -68 28t-28 68v1344q0 40 28 68t68 28h928q40 0 88 -20t76 -48l280 -280q28 -28 48 -76t20 -88z" />
<glyph unicode="&#xf0c8;" d="M1536 1120v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf0c9;" d="M1536 192v-128q0 -26 -19 -45t-45 -19h-1408q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h1408q26 0 45 -19t19 -45zM1536 704v-128q0 -26 -19 -45t-45 -19h-1408q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h1408q26 0 45 -19t19 -45zM1536 1216v-128q0 -26 -19 -45 t-45 -19h-1408q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h1408q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf0ca;" horiz-adv-x="1792" d="M384 128q0 -80 -56 -136t-136 -56t-136 56t-56 136t56 136t136 56t136 -56t56 -136zM384 640q0 -80 -56 -136t-136 -56t-136 56t-56 136t56 136t136 56t136 -56t56 -136zM1792 224v-192q0 -13 -9.5 -22.5t-22.5 -9.5h-1216q-13 0 -22.5 9.5t-9.5 22.5v192q0 13 9.5 22.5 t22.5 9.5h1216q13 0 22.5 -9.5t9.5 -22.5zM384 1152q0 -80 -56 -136t-136 -56t-136 56t-56 136t56 136t136 56t136 -56t56 -136zM1792 736v-192q0 -13 -9.5 -22.5t-22.5 -9.5h-1216q-13 0 -22.5 9.5t-9.5 22.5v192q0 13 9.5 22.5t22.5 9.5h1216q13 0 22.5 -9.5t9.5 -22.5z M1792 1248v-192q0 -13 -9.5 -22.5t-22.5 -9.5h-1216q-13 0 -22.5 9.5t-9.5 22.5v192q0 13 9.5 22.5t22.5 9.5h1216q13 0 22.5 -9.5t9.5 -22.5z" />
<glyph unicode="&#xf0cb;" horiz-adv-x="1792" d="M381 -84q0 -80 -54.5 -126t-135.5 -46q-106 0 -172 66l57 88q49 -45 106 -45q29 0 50.5 14.5t21.5 42.5q0 64 -105 56l-26 56q8 10 32.5 43.5t42.5 54t37 38.5v1q-16 0 -48.5 -1t-48.5 -1v-53h-106v152h333v-88l-95 -115q51 -12 81 -49t30 -88zM383 543v-159h-362 q-6 36 -6 54q0 51 23.5 93t56.5 68t66 47.5t56.5 43.5t23.5 45q0 25 -14.5 38.5t-39.5 13.5q-46 0 -81 -58l-85 59q24 51 71.5 79.5t105.5 28.5q73 0 123 -41.5t50 -112.5q0 -50 -34 -91.5t-75 -64.5t-75.5 -50.5t-35.5 -52.5h127v60h105zM1792 224v-192q0 -13 -9.5 -22.5 t-22.5 -9.5h-1216q-13 0 -22.5 9.5t-9.5 22.5v192q0 14 9 23t23 9h1216q13 0 22.5 -9.5t9.5 -22.5zM384 1123v-99h-335v99h107q0 41 0.5 122t0.5 121v12h-2q-8 -17 -50 -54l-71 76l136 127h106v-404h108zM1792 736v-192q0 -13 -9.5 -22.5t-22.5 -9.5h-1216q-13 0 -22.5 9.5 t-9.5 22.5v192q0 14 9 23t23 9h1216q13 0 22.5 -9.5t9.5 -22.5zM1792 1248v-192q0 -13 -9.5 -22.5t-22.5 -9.5h-1216q-13 0 -22.5 9.5t-9.5 22.5v192q0 13 9.5 22.5t22.5 9.5h1216q13 0 22.5 -9.5t9.5 -22.5z" />
<glyph unicode="&#xf0cc;" horiz-adv-x="1792" d="M1760 640q14 0 23 -9t9 -23v-64q0 -14 -9 -23t-23 -9h-1728q-14 0 -23 9t-9 23v64q0 14 9 23t23 9h1728zM483 704q-28 35 -51 80q-48 97 -48 188q0 181 134 309q133 127 393 127q50 0 167 -19q66 -12 177 -48q10 -38 21 -118q14 -123 14 -183q0 -18 -5 -45l-12 -3l-84 6 l-14 2q-50 149 -103 205q-88 91 -210 91q-114 0 -182 -59q-67 -58 -67 -146q0 -73 66 -140t279 -129q69 -20 173 -66q58 -28 95 -52h-743zM990 448h411q7 -39 7 -92q0 -111 -41 -212q-23 -55 -71 -104q-37 -35 -109 -81q-80 -48 -153 -66q-80 -21 -203 -21q-114 0 -195 23 l-140 40q-57 16 -72 28q-8 8 -8 22v13q0 108 -2 156q-1 30 0 68l2 37v44l102 2q15 -34 30 -71t22.5 -56t12.5 -27q35 -57 80 -94q43 -36 105 -57q59 -22 132 -22q64 0 139 27q77 26 122 86q47 61 47 129q0 84 -81 157q-34 29 -137 71z" />
<glyph unicode="&#xf0cd;" d="M48 1313q-37 2 -45 4l-3 88q13 1 40 1q60 0 112 -4q132 -7 166 -7q86 0 168 3q116 4 146 5q56 0 86 2l-1 -14l2 -64v-9q-60 -9 -124 -9q-60 0 -79 -25q-13 -14 -13 -132q0 -13 0.5 -32.5t0.5 -25.5l1 -229l14 -280q6 -124 51 -202q35 -59 96 -92q88 -47 177 -47 q104 0 191 28q56 18 99 51q48 36 65 64q36 56 53 114q21 73 21 229q0 79 -3.5 128t-11 122.5t-13.5 159.5l-4 59q-5 67 -24 88q-34 35 -77 34l-100 -2l-14 3l2 86h84l205 -10q76 -3 196 10l18 -2q6 -38 6 -51q0 -7 -4 -31q-45 -12 -84 -13q-73 -11 -79 -17q-15 -15 -15 -41 q0 -7 1.5 -27t1.5 -31q8 -19 22 -396q6 -195 -15 -304q-15 -76 -41 -122q-38 -65 -112 -123q-75 -57 -182 -89q-109 -33 -255 -33q-167 0 -284 46q-119 47 -179 122q-61 76 -83 195q-16 80 -16 237v333q0 188 -17 213q-25 36 -147 39zM1536 -96v64q0 14 -9 23t-23 9h-1472 q-14 0 -23 -9t-9 -23v-64q0 -14 9 -23t23 -9h1472q14 0 23 9t9 23z" />
<glyph unicode="&#xf0ce;" horiz-adv-x="1664" d="M512 160v192q0 14 -9 23t-23 9h-320q-14 0 -23 -9t-9 -23v-192q0 -14 9 -23t23 -9h320q14 0 23 9t9 23zM512 544v192q0 14 -9 23t-23 9h-320q-14 0 -23 -9t-9 -23v-192q0 -14 9 -23t23 -9h320q14 0 23 9t9 23zM1024 160v192q0 14 -9 23t-23 9h-320q-14 0 -23 -9t-9 -23 v-192q0 -14 9 -23t23 -9h320q14 0 23 9t9 23zM512 928v192q0 14 -9 23t-23 9h-320q-14 0 -23 -9t-9 -23v-192q0 -14 9 -23t23 -9h320q14 0 23 9t9 23zM1024 544v192q0 14 -9 23t-23 9h-320q-14 0 -23 -9t-9 -23v-192q0 -14 9 -23t23 -9h320q14 0 23 9t9 23zM1536 160v192 q0 14 -9 23t-23 9h-320q-14 0 -23 -9t-9 -23v-192q0 -14 9 -23t23 -9h320q14 0 23 9t9 23zM1024 928v192q0 14 -9 23t-23 9h-320q-14 0 -23 -9t-9 -23v-192q0 -14 9 -23t23 -9h320q14 0 23 9t9 23zM1536 544v192q0 14 -9 23t-23 9h-320q-14 0 -23 -9t-9 -23v-192 q0 -14 9 -23t23 -9h320q14 0 23 9t9 23zM1536 928v192q0 14 -9 23t-23 9h-320q-14 0 -23 -9t-9 -23v-192q0 -14 9 -23t23 -9h320q14 0 23 9t9 23zM1664 1248v-1088q0 -66 -47 -113t-113 -47h-1344q-66 0 -113 47t-47 113v1088q0 66 47 113t113 47h1344q66 0 113 -47t47 -113 z" />
<glyph unicode="&#xf0d0;" horiz-adv-x="1664" d="M1190 955l293 293l-107 107l-293 -293zM1637 1248q0 -27 -18 -45l-1286 -1286q-18 -18 -45 -18t-45 18l-198 198q-18 18 -18 45t18 45l1286 1286q18 18 45 18t45 -18l198 -198q18 -18 18 -45zM286 1438l98 -30l-98 -30l-30 -98l-30 98l-98 30l98 30l30 98zM636 1276 l196 -60l-196 -60l-60 -196l-60 196l-196 60l196 60l60 196zM1566 798l98 -30l-98 -30l-30 -98l-30 98l-98 30l98 30l30 98zM926 1438l98 -30l-98 -30l-30 -98l-30 98l-98 30l98 30l30 98z" />
<glyph unicode="&#xf0d1;" horiz-adv-x="1792" d="M640 128q0 52 -38 90t-90 38t-90 -38t-38 -90t38 -90t90 -38t90 38t38 90zM256 640h384v256h-158q-13 0 -22 -9l-195 -195q-9 -9 -9 -22v-30zM1536 128q0 52 -38 90t-90 38t-90 -38t-38 -90t38 -90t90 -38t90 38t38 90zM1792 1216v-1024q0 -15 -4 -26.5t-13.5 -18.5 t-16.5 -11.5t-23.5 -6t-22.5 -2t-25.5 0t-22.5 0.5q0 -106 -75 -181t-181 -75t-181 75t-75 181h-384q0 -106 -75 -181t-181 -75t-181 75t-75 181h-64q-3 0 -22.5 -0.5t-25.5 0t-22.5 2t-23.5 6t-16.5 11.5t-13.5 18.5t-4 26.5q0 26 19 45t45 19v320q0 8 -0.5 35t0 38 t2.5 34.5t6.5 37t14 30.5t22.5 30l198 198q19 19 50.5 32t58.5 13h160v192q0 26 19 45t45 19h1024q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf0d2;" d="M1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103q-111 0 -218 32q59 93 78 164q9 34 54 211q20 -39 73 -67.5t114 -28.5q121 0 216 68.5t147 188.5t52 270q0 114 -59.5 214t-172.5 163t-255 63q-105 0 -196 -29t-154.5 -77t-109 -110.5t-67 -129.5t-21.5 -134 q0 -104 40 -183t117 -111q30 -12 38 20q2 7 8 31t8 30q6 23 -11 43q-51 61 -51 151q0 151 104.5 259.5t273.5 108.5q151 0 235.5 -82t84.5 -213q0 -170 -68.5 -289t-175.5 -119q-61 0 -98 43.5t-23 104.5q8 35 26.5 93.5t30 103t11.5 75.5q0 50 -27 83t-77 33 q-62 0 -105 -57t-43 -142q0 -73 25 -122l-99 -418q-17 -70 -13 -177q-206 91 -333 281t-127 423q0 209 103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf0d3;" d="M1248 1408q119 0 203.5 -84.5t84.5 -203.5v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-725q85 122 108 210q9 34 53 209q21 -39 73.5 -67t112.5 -28q181 0 295.5 147.5t114.5 373.5q0 84 -35 162.5t-96.5 139t-152.5 97t-197 36.5q-104 0 -194.5 -28.5t-153 -76.5 t-107.5 -109.5t-66.5 -128t-21.5 -132.5q0 -102 39.5 -180t116.5 -110q13 -5 23.5 0t14.5 19q10 44 15 61q6 23 -11 42q-50 62 -50 150q0 150 103.5 256.5t270.5 106.5q149 0 232.5 -81t83.5 -210q0 -168 -67.5 -286t-173.5 -118q-60 0 -97 43.5t-23 103.5q8 34 26.5 92.5 t29.5 102t11 74.5q0 49 -26.5 81.5t-75.5 32.5q-61 0 -103.5 -56.5t-42.5 -139.5q0 -72 24 -121l-98 -414q-24 -100 -7 -254h-183q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960z" />
<glyph unicode="&#xf0d4;" d="M829 318q0 -76 -58.5 -112.5t-139.5 -36.5q-41 0 -80.5 9.5t-75.5 28.5t-58 53t-22 78q0 46 25 80t65.5 51.5t82 25t84.5 7.5q20 0 31 -2q2 -1 23 -16.5t26 -19t23 -18t24.5 -22t19 -22.5t17 -26t9 -26.5t4.5 -31.5zM755 863q0 -60 -33 -99.5t-92 -39.5q-53 0 -93 42.5 t-57.5 96.5t-17.5 106q0 61 32 104t92 43q53 0 93.5 -45t58 -101t17.5 -107zM861 1120l88 64h-265q-85 0 -161 -32t-127.5 -98t-51.5 -153q0 -93 64.5 -154.5t158.5 -61.5q22 0 43 3q-13 -29 -13 -54q0 -44 40 -94q-175 -12 -257 -63q-47 -29 -75.5 -73t-28.5 -95 q0 -43 18.5 -77.5t48.5 -56.5t69 -37t77.5 -21t76.5 -6q60 0 120.5 15.5t113.5 46t86 82.5t33 117q0 49 -20 89.5t-49 66.5t-58 47.5t-49 44t-20 44.5t15.5 42.5t37.5 39.5t44 42t37.5 59.5t15.5 82.5q0 60 -22.5 99.5t-72.5 90.5h83zM1152 672h128v64h-128v128h-64v-128 h-128v-64h128v-160h64v160zM1536 1120v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf0d5;" horiz-adv-x="1664" d="M735 740q0 -36 32 -70.5t77.5 -68t90.5 -73.5t77 -104t32 -142q0 -90 -48 -173q-72 -122 -211 -179.5t-298 -57.5q-132 0 -246.5 41.5t-171.5 137.5q-37 60 -37 131q0 81 44.5 150t118.5 115q131 82 404 100q-32 42 -47.5 74t-15.5 73q0 36 21 85q-46 -4 -68 -4 q-148 0 -249.5 96.5t-101.5 244.5q0 82 36 159t99 131q77 66 182.5 98t217.5 32h418l-138 -88h-131q74 -63 112 -133t38 -160q0 -72 -24.5 -129.5t-59 -93t-69.5 -65t-59.5 -61.5t-24.5 -66zM589 836q38 0 78 16.5t66 43.5q53 57 53 159q0 58 -17 125t-48.5 129.5 t-84.5 103.5t-117 41q-42 0 -82.5 -19.5t-65.5 -52.5q-47 -59 -47 -160q0 -46 10 -97.5t31.5 -103t52 -92.5t75 -67t96.5 -26zM591 -37q58 0 111.5 13t99 39t73 73t27.5 109q0 25 -7 49t-14.5 42t-27 41.5t-29.5 35t-38.5 34.5t-36.5 29t-41.5 30t-36.5 26q-16 2 -48 2 q-53 0 -105 -7t-107.5 -25t-97 -46t-68.5 -74.5t-27 -105.5q0 -70 35 -123.5t91.5 -83t119 -44t127.5 -14.5zM1401 839h213v-108h-213v-219h-105v219h-212v108h212v217h105v-217z" />
<glyph unicode="&#xf0d6;" horiz-adv-x="1920" d="M768 384h384v96h-128v448h-114l-148 -137l77 -80q42 37 55 57h2v-288h-128v-96zM1280 640q0 -70 -21 -142t-59.5 -134t-101.5 -101t-138 -39t-138 39t-101.5 101t-59.5 134t-21 142t21 142t59.5 134t101.5 101t138 39t138 -39t101.5 -101t59.5 -134t21 -142zM1792 384 v512q-106 0 -181 75t-75 181h-1152q0 -106 -75 -181t-181 -75v-512q106 0 181 -75t75 -181h1152q0 106 75 181t181 75zM1920 1216v-1152q0 -26 -19 -45t-45 -19h-1792q-26 0 -45 19t-19 45v1152q0 26 19 45t45 19h1792q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf0d7;" horiz-adv-x="1024" d="M1024 832q0 -26 -19 -45l-448 -448q-19 -19 -45 -19t-45 19l-448 448q-19 19 -19 45t19 45t45 19h896q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf0d8;" horiz-adv-x="1024" d="M1024 320q0 -26 -19 -45t-45 -19h-896q-26 0 -45 19t-19 45t19 45l448 448q19 19 45 19t45 -19l448 -448q19 -19 19 -45z" />
<glyph unicode="&#xf0d9;" horiz-adv-x="640" d="M640 1088v-896q0 -26 -19 -45t-45 -19t-45 19l-448 448q-19 19 -19 45t19 45l448 448q19 19 45 19t45 -19t19 -45z" />
<glyph unicode="&#xf0da;" horiz-adv-x="640" d="M576 640q0 -26 -19 -45l-448 -448q-19 -19 -45 -19t-45 19t-19 45v896q0 26 19 45t45 19t45 -19l448 -448q19 -19 19 -45z" />
<glyph unicode="&#xf0db;" horiz-adv-x="1664" d="M160 0h608v1152h-640v-1120q0 -13 9.5 -22.5t22.5 -9.5zM1536 32v1120h-640v-1152h608q13 0 22.5 9.5t9.5 22.5zM1664 1248v-1216q0 -66 -47 -113t-113 -47h-1344q-66 0 -113 47t-47 113v1216q0 66 47 113t113 47h1344q66 0 113 -47t47 -113z" />
<glyph unicode="&#xf0dc;" horiz-adv-x="1024" d="M1024 448q0 -26 -19 -45l-448 -448q-19 -19 -45 -19t-45 19l-448 448q-19 19 -19 45t19 45t45 19h896q26 0 45 -19t19 -45zM1024 832q0 -26 -19 -45t-45 -19h-896q-26 0 -45 19t-19 45t19 45l448 448q19 19 45 19t45 -19l448 -448q19 -19 19 -45z" />
<glyph unicode="&#xf0dd;" horiz-adv-x="1024" d="M1024 448q0 -26 -19 -45l-448 -448q-19 -19 -45 -19t-45 19l-448 448q-19 19 -19 45t19 45t45 19h896q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf0de;" horiz-adv-x="1024" d="M1024 832q0 -26 -19 -45t-45 -19h-896q-26 0 -45 19t-19 45t19 45l448 448q19 19 45 19t45 -19l448 -448q19 -19 19 -45z" />
<glyph unicode="&#xf0e0;" horiz-adv-x="1792" d="M1792 826v-794q0 -66 -47 -113t-113 -47h-1472q-66 0 -113 47t-47 113v794q44 -49 101 -87q362 -246 497 -345q57 -42 92.5 -65.5t94.5 -48t110 -24.5h1h1q51 0 110 24.5t94.5 48t92.5 65.5q170 123 498 345q57 39 100 87zM1792 1120q0 -79 -49 -151t-122 -123 q-376 -261 -468 -325q-10 -7 -42.5 -30.5t-54 -38t-52 -32.5t-57.5 -27t-50 -9h-1h-1q-23 0 -50 9t-57.5 27t-52 32.5t-54 38t-42.5 30.5q-91 64 -262 182.5t-205 142.5q-62 42 -117 115.5t-55 136.5q0 78 41.5 130t118.5 52h1472q65 0 112.5 -47t47.5 -113z" />
<glyph unicode="&#xf0e1;" d="M349 911v-991h-330v991h330zM370 1217q1 -73 -50.5 -122t-135.5 -49h-2q-82 0 -132 49t-50 122q0 74 51.5 122.5t134.5 48.5t133 -48.5t51 -122.5zM1536 488v-568h-329v530q0 105 -40.5 164.5t-126.5 59.5q-63 0 -105.5 -34.5t-63.5 -85.5q-11 -30 -11 -81v-553h-329 q2 399 2 647t-1 296l-1 48h329v-144h-2q20 32 41 56t56.5 52t87 43.5t114.5 15.5q171 0 275 -113.5t104 -332.5z" />
<glyph unicode="&#xf0e2;" d="M1536 640q0 -156 -61 -298t-164 -245t-245 -164t-298 -61q-172 0 -327 72.5t-264 204.5q-7 10 -6.5 22.5t8.5 20.5l137 138q10 9 25 9q16 -2 23 -12q73 -95 179 -147t225 -52q104 0 198.5 40.5t163.5 109.5t109.5 163.5t40.5 198.5t-40.5 198.5t-109.5 163.5 t-163.5 109.5t-198.5 40.5q-98 0 -188 -35.5t-160 -101.5l137 -138q31 -30 14 -69q-17 -40 -59 -40h-448q-26 0 -45 19t-19 45v448q0 42 40 59q39 17 69 -14l130 -129q107 101 244.5 156.5t284.5 55.5q156 0 298 -61t245 -164t164 -245t61 -298z" />
<glyph unicode="&#xf0e3;" horiz-adv-x="1792" d="M1771 0q0 -53 -37 -90l-107 -108q-39 -37 -91 -37q-53 0 -90 37l-363 364q-38 36 -38 90q0 53 43 96l-256 256l-126 -126q-14 -14 -34 -14t-34 14q2 -2 12.5 -12t12.5 -13t10 -11.5t10 -13.5t6 -13.5t5.5 -16.5t1.5 -18q0 -38 -28 -68q-3 -3 -16.5 -18t-19 -20.5 t-18.5 -16.5t-22 -15.5t-22 -9t-26 -4.5q-40 0 -68 28l-408 408q-28 28 -28 68q0 13 4.5 26t9 22t15.5 22t16.5 18.5t20.5 19t18 16.5q30 28 68 28q10 0 18 -1.5t16.5 -5.5t13.5 -6t13.5 -10t11.5 -10t13 -12.5t12 -12.5q-14 14 -14 34t14 34l348 348q14 14 34 14t34 -14 q-2 2 -12.5 12t-12.5 13t-10 11.5t-10 13.5t-6 13.5t-5.5 16.5t-1.5 18q0 38 28 68q3 3 16.5 18t19 20.5t18.5 16.5t22 15.5t22 9t26 4.5q40 0 68 -28l408 -408q28 -28 28 -68q0 -13 -4.5 -26t-9 -22t-15.5 -22t-16.5 -18.5t-20.5 -19t-18 -16.5q-30 -28 -68 -28 q-10 0 -18 1.5t-16.5 5.5t-13.5 6t-13.5 10t-11.5 10t-13 12.5t-12 12.5q14 -14 14 -34t-14 -34l-126 -126l256 -256q43 43 96 43q52 0 91 -37l363 -363q37 -39 37 -91z" />
<glyph unicode="&#xf0e4;" horiz-adv-x="1792" d="M384 384q0 53 -37.5 90.5t-90.5 37.5t-90.5 -37.5t-37.5 -90.5t37.5 -90.5t90.5 -37.5t90.5 37.5t37.5 90.5zM576 832q0 53 -37.5 90.5t-90.5 37.5t-90.5 -37.5t-37.5 -90.5t37.5 -90.5t90.5 -37.5t90.5 37.5t37.5 90.5zM1004 351l101 382q6 26 -7.5 48.5t-38.5 29.5 t-48 -6.5t-30 -39.5l-101 -382q-60 -5 -107 -43.5t-63 -98.5q-20 -77 20 -146t117 -89t146 20t89 117q16 60 -6 117t-72 91zM1664 384q0 53 -37.5 90.5t-90.5 37.5t-90.5 -37.5t-37.5 -90.5t37.5 -90.5t90.5 -37.5t90.5 37.5t37.5 90.5zM1024 1024q0 53 -37.5 90.5 t-90.5 37.5t-90.5 -37.5t-37.5 -90.5t37.5 -90.5t90.5 -37.5t90.5 37.5t37.5 90.5zM1472 832q0 53 -37.5 90.5t-90.5 37.5t-90.5 -37.5t-37.5 -90.5t37.5 -90.5t90.5 -37.5t90.5 37.5t37.5 90.5zM1792 384q0 -261 -141 -483q-19 -29 -54 -29h-1402q-35 0 -54 29 q-141 221 -141 483q0 182 71 348t191 286t286 191t348 71t348 -71t286 -191t191 -286t71 -348z" />
<glyph unicode="&#xf0e5;" horiz-adv-x="1792" d="M896 1152q-204 0 -381.5 -69.5t-282 -187.5t-104.5 -255q0 -112 71.5 -213.5t201.5 -175.5l87 -50l-27 -96q-24 -91 -70 -172q152 63 275 171l43 38l57 -6q69 -8 130 -8q204 0 381.5 69.5t282 187.5t104.5 255t-104.5 255t-282 187.5t-381.5 69.5zM1792 640 q0 -174 -120 -321.5t-326 -233t-450 -85.5q-70 0 -145 8q-198 -175 -460 -242q-49 -14 -114 -22h-5q-15 0 -27 10.5t-16 27.5v1q-3 4 -0.5 12t2 10t4.5 9.5l6 9t7 8.5t8 9q7 8 31 34.5t34.5 38t31 39.5t32.5 51t27 59t26 76q-157 89 -247.5 220t-90.5 281q0 174 120 321.5 t326 233t450 85.5t450 -85.5t326 -233t120 -321.5z" />
<glyph unicode="&#xf0e6;" horiz-adv-x="1792" d="M704 1152q-153 0 -286 -52t-211.5 -141t-78.5 -191q0 -82 53 -158t149 -132l97 -56l-35 -84q34 20 62 39l44 31l53 -10q78 -14 153 -14q153 0 286 52t211.5 141t78.5 191t-78.5 191t-211.5 141t-286 52zM704 1280q191 0 353.5 -68.5t256.5 -186.5t94 -257t-94 -257 t-256.5 -186.5t-353.5 -68.5q-86 0 -176 16q-124 -88 -278 -128q-36 -9 -86 -16h-3q-11 0 -20.5 8t-11.5 21q-1 3 -1 6.5t0.5 6.5t2 6l2.5 5t3.5 5.5t4 5t4.5 5t4 4.5q5 6 23 25t26 29.5t22.5 29t25 38.5t20.5 44q-124 72 -195 177t-71 224q0 139 94 257t256.5 186.5 t353.5 68.5zM1526 111q10 -24 20.5 -44t25 -38.5t22.5 -29t26 -29.5t23 -25q1 -1 4 -4.5t4.5 -5t4 -5t3.5 -5.5l2.5 -5t2 -6t0.5 -6.5t-1 -6.5q-3 -14 -13 -22t-22 -7q-50 7 -86 16q-154 40 -278 128q-90 -16 -176 -16q-271 0 -472 132q58 -4 88 -4q161 0 309 45t264 129 q125 92 192 212t67 254q0 77 -23 152q129 -71 204 -178t75 -230q0 -120 -71 -224.5t-195 -176.5z" />
<glyph unicode="&#xf0e7;" horiz-adv-x="896" d="M885 970q18 -20 7 -44l-540 -1157q-13 -25 -42 -25q-4 0 -14 2q-17 5 -25.5 19t-4.5 30l197 808l-406 -101q-4 -1 -12 -1q-18 0 -31 11q-18 15 -13 39l201 825q4 14 16 23t28 9h328q19 0 32 -12.5t13 -29.5q0 -8 -5 -18l-171 -463l396 98q8 2 12 2q19 0 34 -15z" />
<glyph unicode="&#xf0e8;" horiz-adv-x="1792" d="M1792 288v-320q0 -40 -28 -68t-68 -28h-320q-40 0 -68 28t-28 68v320q0 40 28 68t68 28h96v192h-512v-192h96q40 0 68 -28t28 -68v-320q0 -40 -28 -68t-68 -28h-320q-40 0 -68 28t-28 68v320q0 40 28 68t68 28h96v192h-512v-192h96q40 0 68 -28t28 -68v-320 q0 -40 -28 -68t-68 -28h-320q-40 0 -68 28t-28 68v320q0 40 28 68t68 28h96v192q0 52 38 90t90 38h512v192h-96q-40 0 -68 28t-28 68v320q0 40 28 68t68 28h320q40 0 68 -28t28 -68v-320q0 -40 -28 -68t-68 -28h-96v-192h512q52 0 90 -38t38 -90v-192h96q40 0 68 -28t28 -68 z" />
<glyph unicode="&#xf0e9;" horiz-adv-x="1664" d="M896 708v-580q0 -104 -76 -180t-180 -76t-180 76t-76 180q0 26 19 45t45 19t45 -19t19 -45q0 -50 39 -89t89 -39t89 39t39 89v580q33 11 64 11t64 -11zM1664 681q0 -13 -9.5 -22.5t-22.5 -9.5q-11 0 -23 10q-49 46 -93 69t-102 23q-68 0 -128 -37t-103 -97 q-7 -10 -17.5 -28t-14.5 -24q-11 -17 -28 -17q-18 0 -29 17q-4 6 -14.5 24t-17.5 28q-43 60 -102.5 97t-127.5 37t-127.5 -37t-102.5 -97q-7 -10 -17.5 -28t-14.5 -24q-11 -17 -29 -17q-17 0 -28 17q-4 6 -14.5 24t-17.5 28q-43 60 -103 97t-128 37q-58 0 -102 -23t-93 -69 q-12 -10 -23 -10q-13 0 -22.5 9.5t-9.5 22.5q0 5 1 7q45 183 172.5 319.5t298 204.5t360.5 68q140 0 274.5 -40t246.5 -113.5t194.5 -187t115.5 -251.5q1 -2 1 -7zM896 1408v-98q-42 2 -64 2t-64 -2v98q0 26 19 45t45 19t45 -19t19 -45z" />
<glyph unicode="&#xf0ea;" horiz-adv-x="1792" d="M768 -128h896v640h-416q-40 0 -68 28t-28 68v416h-384v-1152zM1024 1312v64q0 13 -9.5 22.5t-22.5 9.5h-704q-13 0 -22.5 -9.5t-9.5 -22.5v-64q0 -13 9.5 -22.5t22.5 -9.5h704q13 0 22.5 9.5t9.5 22.5zM1280 640h299l-299 299v-299zM1792 512v-672q0 -40 -28 -68t-68 -28 h-960q-40 0 -68 28t-28 68v160h-544q-40 0 -68 28t-28 68v1344q0 40 28 68t68 28h1088q40 0 68 -28t28 -68v-328q21 -13 36 -28l408 -408q28 -28 48 -76t20 -88z" />
<glyph unicode="&#xf0eb;" horiz-adv-x="1024" d="M736 960q0 -13 -9.5 -22.5t-22.5 -9.5t-22.5 9.5t-9.5 22.5q0 46 -54 71t-106 25q-13 0 -22.5 9.5t-9.5 22.5t9.5 22.5t22.5 9.5q50 0 99.5 -16t87 -54t37.5 -90zM896 960q0 72 -34.5 134t-90 101.5t-123 62t-136.5 22.5t-136.5 -22.5t-123 -62t-90 -101.5t-34.5 -134 q0 -101 68 -180q10 -11 30.5 -33t30.5 -33q128 -153 141 -298h228q13 145 141 298q10 11 30.5 33t30.5 33q68 79 68 180zM1024 960q0 -155 -103 -268q-45 -49 -74.5 -87t-59.5 -95.5t-34 -107.5q47 -28 47 -82q0 -37 -25 -64q25 -27 25 -64q0 -52 -45 -81q13 -23 13 -47 q0 -46 -31.5 -71t-77.5 -25q-20 -44 -60 -70t-87 -26t-87 26t-60 70q-46 0 -77.5 25t-31.5 71q0 24 13 47q-45 29 -45 81q0 37 25 64q-25 27 -25 64q0 54 47 82q-4 50 -34 107.5t-59.5 95.5t-74.5 87q-103 113 -103 268q0 99 44.5 184.5t117 142t164 89t186.5 32.5 t186.5 -32.5t164 -89t117 -142t44.5 -184.5z" />
<glyph unicode="&#xf0ec;" horiz-adv-x="1792" d="M1792 352v-192q0 -13 -9.5 -22.5t-22.5 -9.5h-1376v-192q0 -13 -9.5 -22.5t-22.5 -9.5q-12 0 -24 10l-319 320q-9 9 -9 22q0 14 9 23l320 320q9 9 23 9q13 0 22.5 -9.5t9.5 -22.5v-192h1376q13 0 22.5 -9.5t9.5 -22.5zM1792 896q0 -14 -9 -23l-320 -320q-9 -9 -23 -9 q-13 0 -22.5 9.5t-9.5 22.5v192h-1376q-13 0 -22.5 9.5t-9.5 22.5v192q0 13 9.5 22.5t22.5 9.5h1376v192q0 14 9 23t23 9q12 0 24 -10l319 -319q9 -9 9 -23z" />
<glyph unicode="&#xf0ed;" horiz-adv-x="1920" d="M1280 608q0 14 -9 23t-23 9h-224v352q0 13 -9.5 22.5t-22.5 9.5h-192q-13 0 -22.5 -9.5t-9.5 -22.5v-352h-224q-13 0 -22.5 -9.5t-9.5 -22.5q0 -14 9 -23l352 -352q9 -9 23 -9t23 9l351 351q10 12 10 24zM1920 384q0 -159 -112.5 -271.5t-271.5 -112.5h-1088 q-185 0 -316.5 131.5t-131.5 316.5q0 130 70 240t188 165q-2 30 -2 43q0 212 150 362t362 150q156 0 285.5 -87t188.5 -231q71 62 166 62q106 0 181 -75t75 -181q0 -76 -41 -138q130 -31 213.5 -135.5t83.5 -238.5z" />
<glyph unicode="&#xf0ee;" horiz-adv-x="1920" d="M1280 672q0 14 -9 23l-352 352q-9 9 -23 9t-23 -9l-351 -351q-10 -12 -10 -24q0 -14 9 -23t23 -9h224v-352q0 -13 9.5 -22.5t22.5 -9.5h192q13 0 22.5 9.5t9.5 22.5v352h224q13 0 22.5 9.5t9.5 22.5zM1920 384q0 -159 -112.5 -271.5t-271.5 -112.5h-1088 q-185 0 -316.5 131.5t-131.5 316.5q0 130 70 240t188 165q-2 30 -2 43q0 212 150 362t362 150q156 0 285.5 -87t188.5 -231q71 62 166 62q106 0 181 -75t75 -181q0 -76 -41 -138q130 -31 213.5 -135.5t83.5 -238.5z" />
<glyph unicode="&#xf0f0;" horiz-adv-x="1408" d="M384 192q0 -26 -19 -45t-45 -19t-45 19t-19 45t19 45t45 19t45 -19t19 -45zM1408 131q0 -121 -73 -190t-194 -69h-874q-121 0 -194 69t-73 190q0 68 5.5 131t24 138t47.5 132.5t81 103t120 60.5q-22 -52 -22 -120v-203q-58 -20 -93 -70t-35 -111q0 -80 56 -136t136 -56 t136 56t56 136q0 61 -35.5 111t-92.5 70v203q0 62 25 93q132 -104 295 -104t295 104q25 -31 25 -93v-64q-106 0 -181 -75t-75 -181v-89q-32 -29 -32 -71q0 -40 28 -68t68 -28t68 28t28 68q0 42 -32 71v89q0 52 38 90t90 38t90 -38t38 -90v-89q-32 -29 -32 -71q0 -40 28 -68 t68 -28t68 28t28 68q0 42 -32 71v89q0 68 -34.5 127.5t-93.5 93.5q0 10 0.5 42.5t0 48t-2.5 41.5t-7 47t-13 40q68 -15 120 -60.5t81 -103t47.5 -132.5t24 -138t5.5 -131zM1088 1024q0 -159 -112.5 -271.5t-271.5 -112.5t-271.5 112.5t-112.5 271.5t112.5 271.5t271.5 112.5 t271.5 -112.5t112.5 -271.5z" />
<glyph unicode="&#xf0f1;" horiz-adv-x="1408" d="M1280 832q0 26 -19 45t-45 19t-45 -19t-19 -45t19 -45t45 -19t45 19t19 45zM1408 832q0 -62 -35.5 -111t-92.5 -70v-395q0 -159 -131.5 -271.5t-316.5 -112.5t-316.5 112.5t-131.5 271.5v132q-164 20 -274 128t-110 252v512q0 26 19 45t45 19q6 0 16 -2q17 30 47 48 t65 18q53 0 90.5 -37.5t37.5 -90.5t-37.5 -90.5t-90.5 -37.5q-33 0 -64 18v-402q0 -106 94 -181t226 -75t226 75t94 181v402q-31 -18 -64 -18q-53 0 -90.5 37.5t-37.5 90.5t37.5 90.5t90.5 37.5q35 0 65 -18t47 -48q10 2 16 2q26 0 45 -19t19 -45v-512q0 -144 -110 -252 t-274 -128v-132q0 -106 94 -181t226 -75t226 75t94 181v395q-57 21 -92.5 70t-35.5 111q0 80 56 136t136 56t136 -56t56 -136z" />
<glyph unicode="&#xf0f2;" horiz-adv-x="1792" d="M640 1152h512v128h-512v-128zM288 1152v-1280h-64q-92 0 -158 66t-66 158v832q0 92 66 158t158 66h64zM1408 1152v-1280h-1024v1280h128v160q0 40 28 68t68 28h576q40 0 68 -28t28 -68v-160h128zM1792 928v-832q0 -92 -66 -158t-158 -66h-64v1280h64q92 0 158 -66 t66 -158z" />
<glyph unicode="&#xf0f3;" horiz-adv-x="1792" d="M912 -160q0 16 -16 16q-59 0 -101.5 42.5t-42.5 101.5q0 16 -16 16t-16 -16q0 -73 51.5 -124.5t124.5 -51.5q16 0 16 16zM1728 128q0 -52 -38 -90t-90 -38h-448q0 -106 -75 -181t-181 -75t-181 75t-75 181h-448q-52 0 -90 38t-38 90q50 42 91 88t85 119.5t74.5 158.5 t50 206t19.5 260q0 152 117 282.5t307 158.5q-8 19 -8 39q0 40 28 68t68 28t68 -28t28 -68q0 -20 -8 -39q190 -28 307 -158.5t117 -282.5q0 -139 19.5 -260t50 -206t74.5 -158.5t85 -119.5t91 -88z" />
<glyph unicode="&#xf0f4;" horiz-adv-x="1920" d="M1664 896q0 80 -56 136t-136 56h-64v-384h64q80 0 136 56t56 136zM0 128h1792q0 -106 -75 -181t-181 -75h-1280q-106 0 -181 75t-75 181zM1856 896q0 -159 -112.5 -271.5t-271.5 -112.5h-64v-32q0 -92 -66 -158t-158 -66h-704q-92 0 -158 66t-66 158v736q0 26 19 45 t45 19h1152q159 0 271.5 -112.5t112.5 -271.5z" />
<glyph unicode="&#xf0f5;" horiz-adv-x="1408" d="M640 1472v-640q0 -61 -35.5 -111t-92.5 -70v-779q0 -52 -38 -90t-90 -38h-128q-52 0 -90 38t-38 90v779q-57 20 -92.5 70t-35.5 111v640q0 26 19 45t45 19t45 -19t19 -45v-416q0 -26 19 -45t45 -19t45 19t19 45v416q0 26 19 45t45 19t45 -19t19 -45v-416q0 -26 19 -45 t45 -19t45 19t19 45v416q0 26 19 45t45 19t45 -19t19 -45zM1408 1472v-1600q0 -52 -38 -90t-90 -38h-128q-52 0 -90 38t-38 90v512h-224q-13 0 -22.5 9.5t-9.5 22.5v800q0 132 94 226t226 94h256q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf0f6;" d="M1468 1156q28 -28 48 -76t20 -88v-1152q0 -40 -28 -68t-68 -28h-1344q-40 0 -68 28t-28 68v1600q0 40 28 68t68 28h896q40 0 88 -20t76 -48zM1024 1400v-376h376q-10 29 -22 41l-313 313q-12 12 -41 22zM1408 -128v1024h-416q-40 0 -68 28t-28 68v416h-768v-1536h1280z M384 736q0 14 9 23t23 9h704q14 0 23 -9t9 -23v-64q0 -14 -9 -23t-23 -9h-704q-14 0 -23 9t-9 23v64zM1120 512q14 0 23 -9t9 -23v-64q0 -14 -9 -23t-23 -9h-704q-14 0 -23 9t-9 23v64q0 14 9 23t23 9h704zM1120 256q14 0 23 -9t9 -23v-64q0 -14 -9 -23t-23 -9h-704 q-14 0 -23 9t-9 23v64q0 14 9 23t23 9h704z" />
<glyph unicode="&#xf0f7;" horiz-adv-x="1408" d="M384 224v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5zM384 480v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5z M640 480v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5zM384 736v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5z M1152 224v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5zM896 480v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5z M640 736v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5zM384 992v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5z M1152 480v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5zM896 736v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5z M640 992v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5zM384 1248v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5z M1152 736v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5zM896 992v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5z M640 1248v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5zM1152 992v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5z M896 1248v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5zM1152 1248v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5z M896 -128h384v1536h-1152v-1536h384v224q0 13 9.5 22.5t22.5 9.5h320q13 0 22.5 -9.5t9.5 -22.5v-224zM1408 1472v-1664q0 -26 -19 -45t-45 -19h-1280q-26 0 -45 19t-19 45v1664q0 26 19 45t45 19h1280q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf0f8;" horiz-adv-x="1408" d="M384 224v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5zM384 480v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5z M640 480v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5zM384 736v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5z M1152 224v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5zM896 480v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5z M640 736v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5zM1152 480v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5z M896 736v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5zM1152 736v-64q0 -13 -9.5 -22.5t-22.5 -9.5h-64q-13 0 -22.5 9.5t-9.5 22.5v64q0 13 9.5 22.5t22.5 9.5h64q13 0 22.5 -9.5t9.5 -22.5z M896 -128h384v1152h-256v-32q0 -40 -28 -68t-68 -28h-448q-40 0 -68 28t-28 68v32h-256v-1152h384v224q0 13 9.5 22.5t22.5 9.5h320q13 0 22.5 -9.5t9.5 -22.5v-224zM896 1056v320q0 13 -9.5 22.5t-22.5 9.5h-64q-13 0 -22.5 -9.5t-9.5 -22.5v-96h-128v96q0 13 -9.5 22.5 t-22.5 9.5h-64q-13 0 -22.5 -9.5t-9.5 -22.5v-320q0 -13 9.5 -22.5t22.5 -9.5h64q13 0 22.5 9.5t9.5 22.5v96h128v-96q0 -13 9.5 -22.5t22.5 -9.5h64q13 0 22.5 9.5t9.5 22.5zM1408 1088v-1280q0 -26 -19 -45t-45 -19h-1280q-26 0 -45 19t-19 45v1280q0 26 19 45t45 19h320 v288q0 40 28 68t68 28h448q40 0 68 -28t28 -68v-288h320q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf0f9;" horiz-adv-x="1920" d="M640 128q0 53 -37.5 90.5t-90.5 37.5t-90.5 -37.5t-37.5 -90.5t37.5 -90.5t90.5 -37.5t90.5 37.5t37.5 90.5zM256 640h384v256h-158q-14 -2 -22 -9l-195 -195q-7 -12 -9 -22v-30zM1536 128q0 53 -37.5 90.5t-90.5 37.5t-90.5 -37.5t-37.5 -90.5t37.5 -90.5t90.5 -37.5 t90.5 37.5t37.5 90.5zM1664 800v192q0 14 -9 23t-23 9h-224v224q0 14 -9 23t-23 9h-192q-14 0 -23 -9t-9 -23v-224h-224q-14 0 -23 -9t-9 -23v-192q0 -14 9 -23t23 -9h224v-224q0 -14 9 -23t23 -9h192q14 0 23 9t9 23v224h224q14 0 23 9t9 23zM1920 1344v-1152 q0 -26 -19 -45t-45 -19h-192q0 -106 -75 -181t-181 -75t-181 75t-75 181h-384q0 -106 -75 -181t-181 -75t-181 75t-75 181h-128q-26 0 -45 19t-19 45t19 45t45 19v416q0 26 13 58t32 51l198 198q19 19 51 32t58 13h160v320q0 26 19 45t45 19h1152q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf0fa;" horiz-adv-x="1792" d="M1280 416v192q0 14 -9 23t-23 9h-224v224q0 14 -9 23t-23 9h-192q-14 0 -23 -9t-9 -23v-224h-224q-14 0 -23 -9t-9 -23v-192q0 -14 9 -23t23 -9h224v-224q0 -14 9 -23t23 -9h192q14 0 23 9t9 23v224h224q14 0 23 9t9 23zM640 1152h512v128h-512v-128zM256 1152v-1280h-32 q-92 0 -158 66t-66 158v832q0 92 66 158t158 66h32zM1440 1152v-1280h-1088v1280h160v160q0 40 28 68t68 28h576q40 0 68 -28t28 -68v-160h160zM1792 928v-832q0 -92 -66 -158t-158 -66h-32v1280h32q92 0 158 -66t66 -158z" />
<glyph unicode="&#xf0fb;" horiz-adv-x="1920" d="M1920 576q-1 -32 -288 -96l-352 -32l-224 -64h-64l-293 -352h69q26 0 45 -4.5t19 -11.5t-19 -11.5t-45 -4.5h-96h-160h-64v32h64v416h-160l-192 -224h-96l-32 32v192h32v32h128v8l-192 24v128l192 24v8h-128v32h-32v192l32 32h96l192 -224h160v416h-64v32h64h160h96 q26 0 45 -4.5t19 -11.5t-19 -11.5t-45 -4.5h-69l293 -352h64l224 -64l352 -32q261 -58 287 -93z" />
<glyph unicode="&#xf0fc;" horiz-adv-x="1664" d="M640 640v384h-256v-256q0 -53 37.5 -90.5t90.5 -37.5h128zM1664 192v-192h-1152v192l128 192h-128q-159 0 -271.5 112.5t-112.5 271.5v320l-64 64l32 128h480l32 128h960l32 -192l-64 -32v-800z" />
<glyph unicode="&#xf0fd;" d="M1280 192v896q0 26 -19 45t-45 19h-128q-26 0 -45 -19t-19 -45v-320h-512v320q0 26 -19 45t-45 19h-128q-26 0 -45 -19t-19 -45v-896q0 -26 19 -45t45 -19h128q26 0 45 19t19 45v320h512v-320q0 -26 19 -45t45 -19h128q26 0 45 19t19 45zM1536 1120v-960 q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf0fe;" d="M1280 576v128q0 26 -19 45t-45 19h-320v320q0 26 -19 45t-45 19h-128q-26 0 -45 -19t-19 -45v-320h-320q-26 0 -45 -19t-19 -45v-128q0 -26 19 -45t45 -19h320v-320q0 -26 19 -45t45 -19h128q26 0 45 19t19 45v320h320q26 0 45 19t19 45zM1536 1120v-960 q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf100;" horiz-adv-x="1024" d="M627 160q0 -13 -10 -23l-50 -50q-10 -10 -23 -10t-23 10l-466 466q-10 10 -10 23t10 23l466 466q10 10 23 10t23 -10l50 -50q10 -10 10 -23t-10 -23l-393 -393l393 -393q10 -10 10 -23zM1011 160q0 -13 -10 -23l-50 -50q-10 -10 -23 -10t-23 10l-466 466q-10 10 -10 23 t10 23l466 466q10 10 23 10t23 -10l50 -50q10 -10 10 -23t-10 -23l-393 -393l393 -393q10 -10 10 -23z" />
<glyph unicode="&#xf101;" horiz-adv-x="1024" d="M595 576q0 -13 -10 -23l-466 -466q-10 -10 -23 -10t-23 10l-50 50q-10 10 -10 23t10 23l393 393l-393 393q-10 10 -10 23t10 23l50 50q10 10 23 10t23 -10l466 -466q10 -10 10 -23zM979 576q0 -13 -10 -23l-466 -466q-10 -10 -23 -10t-23 10l-50 50q-10 10 -10 23t10 23 l393 393l-393 393q-10 10 -10 23t10 23l50 50q10 10 23 10t23 -10l466 -466q10 -10 10 -23z" />
<glyph unicode="&#xf102;" horiz-adv-x="1152" d="M1075 224q0 -13 -10 -23l-50 -50q-10 -10 -23 -10t-23 10l-393 393l-393 -393q-10 -10 -23 -10t-23 10l-50 50q-10 10 -10 23t10 23l466 466q10 10 23 10t23 -10l466 -466q10 -10 10 -23zM1075 608q0 -13 -10 -23l-50 -50q-10 -10 -23 -10t-23 10l-393 393l-393 -393 q-10 -10 -23 -10t-23 10l-50 50q-10 10 -10 23t10 23l466 466q10 10 23 10t23 -10l466 -466q10 -10 10 -23z" />
<glyph unicode="&#xf103;" horiz-adv-x="1152" d="M1075 672q0 -13 -10 -23l-466 -466q-10 -10 -23 -10t-23 10l-466 466q-10 10 -10 23t10 23l50 50q10 10 23 10t23 -10l393 -393l393 393q10 10 23 10t23 -10l50 -50q10 -10 10 -23zM1075 1056q0 -13 -10 -23l-466 -466q-10 -10 -23 -10t-23 10l-466 466q-10 10 -10 23 t10 23l50 50q10 10 23 10t23 -10l393 -393l393 393q10 10 23 10t23 -10l50 -50q10 -10 10 -23z" />
<glyph unicode="&#xf104;" horiz-adv-x="640" d="M627 992q0 -13 -10 -23l-393 -393l393 -393q10 -10 10 -23t-10 -23l-50 -50q-10 -10 -23 -10t-23 10l-466 466q-10 10 -10 23t10 23l466 466q10 10 23 10t23 -10l50 -50q10 -10 10 -23z" />
<glyph unicode="&#xf105;" horiz-adv-x="640" d="M595 576q0 -13 -10 -23l-466 -466q-10 -10 -23 -10t-23 10l-50 50q-10 10 -10 23t10 23l393 393l-393 393q-10 10 -10 23t10 23l50 50q10 10 23 10t23 -10l466 -466q10 -10 10 -23z" />
<glyph unicode="&#xf106;" horiz-adv-x="1152" d="M1075 352q0 -13 -10 -23l-50 -50q-10 -10 -23 -10t-23 10l-393 393l-393 -393q-10 -10 -23 -10t-23 10l-50 50q-10 10 -10 23t10 23l466 466q10 10 23 10t23 -10l466 -466q10 -10 10 -23z" />
<glyph unicode="&#xf107;" horiz-adv-x="1152" d="M1075 800q0 -13 -10 -23l-466 -466q-10 -10 -23 -10t-23 10l-466 466q-10 10 -10 23t10 23l50 50q10 10 23 10t23 -10l393 -393l393 393q10 10 23 10t23 -10l50 -50q10 -10 10 -23z" />
<glyph unicode="&#xf108;" horiz-adv-x="1920" d="M1792 544v832q0 13 -9.5 22.5t-22.5 9.5h-1600q-13 0 -22.5 -9.5t-9.5 -22.5v-832q0 -13 9.5 -22.5t22.5 -9.5h1600q13 0 22.5 9.5t9.5 22.5zM1920 1376v-1088q0 -66 -47 -113t-113 -47h-544q0 -37 16 -77.5t32 -71t16 -43.5q0 -26 -19 -45t-45 -19h-512q-26 0 -45 19 t-19 45q0 14 16 44t32 70t16 78h-544q-66 0 -113 47t-47 113v1088q0 66 47 113t113 47h1600q66 0 113 -47t47 -113z" />
<glyph unicode="&#xf109;" horiz-adv-x="1920" d="M416 256q-66 0 -113 47t-47 113v704q0 66 47 113t113 47h1088q66 0 113 -47t47 -113v-704q0 -66 -47 -113t-113 -47h-1088zM384 1120v-704q0 -13 9.5 -22.5t22.5 -9.5h1088q13 0 22.5 9.5t9.5 22.5v704q0 13 -9.5 22.5t-22.5 9.5h-1088q-13 0 -22.5 -9.5t-9.5 -22.5z M1760 192h160v-96q0 -40 -47 -68t-113 -28h-1600q-66 0 -113 28t-47 68v96h160h1600zM1040 96q16 0 16 16t-16 16h-160q-16 0 -16 -16t16 -16h160z" />
<glyph unicode="&#xf10a;" horiz-adv-x="1152" d="M640 128q0 26 -19 45t-45 19t-45 -19t-19 -45t19 -45t45 -19t45 19t19 45zM1024 288v960q0 13 -9.5 22.5t-22.5 9.5h-832q-13 0 -22.5 -9.5t-9.5 -22.5v-960q0 -13 9.5 -22.5t22.5 -9.5h832q13 0 22.5 9.5t9.5 22.5zM1152 1248v-1088q0 -66 -47 -113t-113 -47h-832 q-66 0 -113 47t-47 113v1088q0 66 47 113t113 47h832q66 0 113 -47t47 -113z" />
<glyph unicode="&#xf10b;" horiz-adv-x="768" d="M464 128q0 33 -23.5 56.5t-56.5 23.5t-56.5 -23.5t-23.5 -56.5t23.5 -56.5t56.5 -23.5t56.5 23.5t23.5 56.5zM672 288v704q0 13 -9.5 22.5t-22.5 9.5h-512q-13 0 -22.5 -9.5t-9.5 -22.5v-704q0 -13 9.5 -22.5t22.5 -9.5h512q13 0 22.5 9.5t9.5 22.5zM480 1136 q0 16 -16 16h-160q-16 0 -16 -16t16 -16h160q16 0 16 16zM768 1152v-1024q0 -52 -38 -90t-90 -38h-512q-52 0 -90 38t-38 90v1024q0 52 38 90t90 38h512q52 0 90 -38t38 -90z" />
<glyph unicode="&#xf10c;" d="M768 1184q-148 0 -273 -73t-198 -198t-73 -273t73 -273t198 -198t273 -73t273 73t198 198t73 273t-73 273t-198 198t-273 73zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103 t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf10d;" horiz-adv-x="1664" d="M768 576v-384q0 -80 -56 -136t-136 -56h-384q-80 0 -136 56t-56 136v704q0 104 40.5 198.5t109.5 163.5t163.5 109.5t198.5 40.5h64q26 0 45 -19t19 -45v-128q0 -26 -19 -45t-45 -19h-64q-106 0 -181 -75t-75 -181v-32q0 -40 28 -68t68 -28h224q80 0 136 -56t56 -136z M1664 576v-384q0 -80 -56 -136t-136 -56h-384q-80 0 -136 56t-56 136v704q0 104 40.5 198.5t109.5 163.5t163.5 109.5t198.5 40.5h64q26 0 45 -19t19 -45v-128q0 -26 -19 -45t-45 -19h-64q-106 0 -181 -75t-75 -181v-32q0 -40 28 -68t68 -28h224q80 0 136 -56t56 -136z" />
<glyph unicode="&#xf10e;" horiz-adv-x="1664" d="M768 1216v-704q0 -104 -40.5 -198.5t-109.5 -163.5t-163.5 -109.5t-198.5 -40.5h-64q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h64q106 0 181 75t75 181v32q0 40 -28 68t-68 28h-224q-80 0 -136 56t-56 136v384q0 80 56 136t136 56h384q80 0 136 -56t56 -136zM1664 1216 v-704q0 -104 -40.5 -198.5t-109.5 -163.5t-163.5 -109.5t-198.5 -40.5h-64q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h64q106 0 181 75t75 181v32q0 40 -28 68t-68 28h-224q-80 0 -136 56t-56 136v384q0 80 56 136t136 56h384q80 0 136 -56t56 -136z" />
<glyph unicode="&#xf110;" horiz-adv-x="1792" d="M526 142q0 -53 -37.5 -90.5t-90.5 -37.5q-52 0 -90 38t-38 90q0 53 37.5 90.5t90.5 37.5t90.5 -37.5t37.5 -90.5zM1024 -64q0 -53 -37.5 -90.5t-90.5 -37.5t-90.5 37.5t-37.5 90.5t37.5 90.5t90.5 37.5t90.5 -37.5t37.5 -90.5zM320 640q0 -53 -37.5 -90.5t-90.5 -37.5 t-90.5 37.5t-37.5 90.5t37.5 90.5t90.5 37.5t90.5 -37.5t37.5 -90.5zM1522 142q0 -52 -38 -90t-90 -38q-53 0 -90.5 37.5t-37.5 90.5t37.5 90.5t90.5 37.5t90.5 -37.5t37.5 -90.5zM558 1138q0 -66 -47 -113t-113 -47t-113 47t-47 113t47 113t113 47t113 -47t47 -113z M1728 640q0 -53 -37.5 -90.5t-90.5 -37.5t-90.5 37.5t-37.5 90.5t37.5 90.5t90.5 37.5t90.5 -37.5t37.5 -90.5zM1088 1344q0 -80 -56 -136t-136 -56t-136 56t-56 136t56 136t136 56t136 -56t56 -136zM1618 1138q0 -93 -66 -158.5t-158 -65.5q-93 0 -158.5 65.5t-65.5 158.5 q0 92 65.5 158t158.5 66q92 0 158 -66t66 -158z" />
<glyph unicode="&#xf111;" d="M1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf112;" horiz-adv-x="1792" d="M1792 416q0 -166 -127 -451q-3 -7 -10.5 -24t-13.5 -30t-13 -22q-12 -17 -28 -17q-15 0 -23.5 10t-8.5 25q0 9 2.5 26.5t2.5 23.5q5 68 5 123q0 101 -17.5 181t-48.5 138.5t-80 101t-105.5 69.5t-133 42.5t-154 21.5t-175.5 6h-224v-256q0 -26 -19 -45t-45 -19t-45 19 l-512 512q-19 19 -19 45t19 45l512 512q19 19 45 19t45 -19t19 -45v-256h224q713 0 875 -403q53 -134 53 -333z" />
<glyph unicode="&#xf113;" horiz-adv-x="1664" d="M640 320q0 -40 -12.5 -82t-43 -76t-72.5 -34t-72.5 34t-43 76t-12.5 82t12.5 82t43 76t72.5 34t72.5 -34t43 -76t12.5 -82zM1280 320q0 -40 -12.5 -82t-43 -76t-72.5 -34t-72.5 34t-43 76t-12.5 82t12.5 82t43 76t72.5 34t72.5 -34t43 -76t12.5 -82zM1440 320 q0 120 -69 204t-187 84q-41 0 -195 -21q-71 -11 -157 -11t-157 11q-152 21 -195 21q-118 0 -187 -84t-69 -204q0 -88 32 -153.5t81 -103t122 -60t140 -29.5t149 -7h168q82 0 149 7t140 29.5t122 60t81 103t32 153.5zM1664 496q0 -207 -61 -331q-38 -77 -105.5 -133t-141 -86 t-170 -47.5t-171.5 -22t-167 -4.5q-78 0 -142 3t-147.5 12.5t-152.5 30t-137 51.5t-121 81t-86 115q-62 123 -62 331q0 237 136 396q-27 82 -27 170q0 116 51 218q108 0 190 -39.5t189 -123.5q147 35 309 35q148 0 280 -32q105 82 187 121t189 39q51 -102 51 -218 q0 -87 -27 -168q136 -160 136 -398z" />
<glyph unicode="&#xf114;" horiz-adv-x="1664" d="M1536 224v704q0 40 -28 68t-68 28h-704q-40 0 -68 28t-28 68v64q0 40 -28 68t-68 28h-320q-40 0 -68 -28t-28 -68v-960q0 -40 28 -68t68 -28h1216q40 0 68 28t28 68zM1664 928v-704q0 -92 -66 -158t-158 -66h-1216q-92 0 -158 66t-66 158v960q0 92 66 158t158 66h320 q92 0 158 -66t66 -158v-32h672q92 0 158 -66t66 -158z" />
<glyph unicode="&#xf115;" horiz-adv-x="1920" d="M1781 605q0 35 -53 35h-1088q-40 0 -85.5 -21.5t-71.5 -52.5l-294 -363q-18 -24 -18 -40q0 -35 53 -35h1088q40 0 86 22t71 53l294 363q18 22 18 39zM640 768h768v160q0 40 -28 68t-68 28h-576q-40 0 -68 28t-28 68v64q0 40 -28 68t-68 28h-320q-40 0 -68 -28t-28 -68 v-853l256 315q44 53 116 87.5t140 34.5zM1909 605q0 -62 -46 -120l-295 -363q-43 -53 -116 -87.5t-140 -34.5h-1088q-92 0 -158 66t-66 158v960q0 92 66 158t158 66h320q92 0 158 -66t66 -158v-32h544q92 0 158 -66t66 -158v-160h192q54 0 99 -24.5t67 -70.5q15 -32 15 -68z " />
<glyph unicode="&#xf116;" horiz-adv-x="1792" />
<glyph unicode="&#xf117;" horiz-adv-x="1792" />
<glyph unicode="&#xf118;" d="M1134 461q-37 -121 -138 -195t-228 -74t-228 74t-138 195q-8 25 4 48.5t38 31.5q25 8 48.5 -4t31.5 -38q25 -80 92.5 -129.5t151.5 -49.5t151.5 49.5t92.5 129.5q8 26 32 38t49 4t37 -31.5t4 -48.5zM640 896q0 -53 -37.5 -90.5t-90.5 -37.5t-90.5 37.5t-37.5 90.5 t37.5 90.5t90.5 37.5t90.5 -37.5t37.5 -90.5zM1152 896q0 -53 -37.5 -90.5t-90.5 -37.5t-90.5 37.5t-37.5 90.5t37.5 90.5t90.5 37.5t90.5 -37.5t37.5 -90.5zM1408 640q0 130 -51 248.5t-136.5 204t-204 136.5t-248.5 51t-248.5 -51t-204 -136.5t-136.5 -204t-51 -248.5 t51 -248.5t136.5 -204t204 -136.5t248.5 -51t248.5 51t204 136.5t136.5 204t51 248.5zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf119;" d="M1134 307q8 -25 -4 -48.5t-37 -31.5t-49 4t-32 38q-25 80 -92.5 129.5t-151.5 49.5t-151.5 -49.5t-92.5 -129.5q-8 -26 -31.5 -38t-48.5 -4q-26 8 -38 31.5t-4 48.5q37 121 138 195t228 74t228 -74t138 -195zM640 896q0 -53 -37.5 -90.5t-90.5 -37.5t-90.5 37.5 t-37.5 90.5t37.5 90.5t90.5 37.5t90.5 -37.5t37.5 -90.5zM1152 896q0 -53 -37.5 -90.5t-90.5 -37.5t-90.5 37.5t-37.5 90.5t37.5 90.5t90.5 37.5t90.5 -37.5t37.5 -90.5zM1408 640q0 130 -51 248.5t-136.5 204t-204 136.5t-248.5 51t-248.5 -51t-204 -136.5t-136.5 -204 t-51 -248.5t51 -248.5t136.5 -204t204 -136.5t248.5 -51t248.5 51t204 136.5t136.5 204t51 248.5zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf11a;" d="M1152 448q0 -26 -19 -45t-45 -19h-640q-26 0 -45 19t-19 45t19 45t45 19h640q26 0 45 -19t19 -45zM640 896q0 -53 -37.5 -90.5t-90.5 -37.5t-90.5 37.5t-37.5 90.5t37.5 90.5t90.5 37.5t90.5 -37.5t37.5 -90.5zM1152 896q0 -53 -37.5 -90.5t-90.5 -37.5t-90.5 37.5 t-37.5 90.5t37.5 90.5t90.5 37.5t90.5 -37.5t37.5 -90.5zM1408 640q0 130 -51 248.5t-136.5 204t-204 136.5t-248.5 51t-248.5 -51t-204 -136.5t-136.5 -204t-51 -248.5t51 -248.5t136.5 -204t204 -136.5t248.5 -51t248.5 51t204 136.5t136.5 204t51 248.5zM1536 640 q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf11b;" horiz-adv-x="1920" d="M832 448v128q0 14 -9 23t-23 9h-192v192q0 14 -9 23t-23 9h-128q-14 0 -23 -9t-9 -23v-192h-192q-14 0 -23 -9t-9 -23v-128q0 -14 9 -23t23 -9h192v-192q0 -14 9 -23t23 -9h128q14 0 23 9t9 23v192h192q14 0 23 9t9 23zM1408 384q0 53 -37.5 90.5t-90.5 37.5t-90.5 -37.5 t-37.5 -90.5t37.5 -90.5t90.5 -37.5t90.5 37.5t37.5 90.5zM1664 640q0 53 -37.5 90.5t-90.5 37.5t-90.5 -37.5t-37.5 -90.5t37.5 -90.5t90.5 -37.5t90.5 37.5t37.5 90.5zM1920 512q0 -212 -150 -362t-362 -150q-192 0 -338 128h-220q-146 -128 -338 -128q-212 0 -362 150 t-150 362t150 362t362 150h896q212 0 362 -150t150 -362z" />
<glyph unicode="&#xf11c;" horiz-adv-x="1920" d="M384 368v-96q0 -16 -16 -16h-96q-16 0 -16 16v96q0 16 16 16h96q16 0 16 -16zM512 624v-96q0 -16 -16 -16h-224q-16 0 -16 16v96q0 16 16 16h224q16 0 16 -16zM384 880v-96q0 -16 -16 -16h-96q-16 0 -16 16v96q0 16 16 16h96q16 0 16 -16zM1408 368v-96q0 -16 -16 -16 h-864q-16 0 -16 16v96q0 16 16 16h864q16 0 16 -16zM768 624v-96q0 -16 -16 -16h-96q-16 0 -16 16v96q0 16 16 16h96q16 0 16 -16zM640 880v-96q0 -16 -16 -16h-96q-16 0 -16 16v96q0 16 16 16h96q16 0 16 -16zM1024 624v-96q0 -16 -16 -16h-96q-16 0 -16 16v96q0 16 16 16 h96q16 0 16 -16zM896 880v-96q0 -16 -16 -16h-96q-16 0 -16 16v96q0 16 16 16h96q16 0 16 -16zM1280 624v-96q0 -16 -16 -16h-96q-16 0 -16 16v96q0 16 16 16h96q16 0 16 -16zM1664 368v-96q0 -16 -16 -16h-96q-16 0 -16 16v96q0 16 16 16h96q16 0 16 -16zM1152 880v-96 q0 -16 -16 -16h-96q-16 0 -16 16v96q0 16 16 16h96q16 0 16 -16zM1408 880v-96q0 -16 -16 -16h-96q-16 0 -16 16v96q0 16 16 16h96q16 0 16 -16zM1664 880v-352q0 -16 -16 -16h-224q-16 0 -16 16v96q0 16 16 16h112v240q0 16 16 16h96q16 0 16 -16zM1792 128v896h-1664v-896 h1664zM1920 1024v-896q0 -53 -37.5 -90.5t-90.5 -37.5h-1664q-53 0 -90.5 37.5t-37.5 90.5v896q0 53 37.5 90.5t90.5 37.5h1664q53 0 90.5 -37.5t37.5 -90.5z" />
<glyph unicode="&#xf11d;" horiz-adv-x="1792" d="M1664 491v616q-169 -91 -306 -91q-82 0 -145 32q-100 49 -184 76.5t-178 27.5q-173 0 -403 -127v-599q245 113 433 113q55 0 103.5 -7.5t98 -26t77 -31t82.5 -39.5l28 -14q44 -22 101 -22q120 0 293 92zM320 1280q0 -35 -17.5 -64t-46.5 -46v-1266q0 -14 -9 -23t-23 -9 h-64q-14 0 -23 9t-9 23v1266q-29 17 -46.5 46t-17.5 64q0 53 37.5 90.5t90.5 37.5t90.5 -37.5t37.5 -90.5zM1792 1216v-763q0 -39 -35 -57q-10 -5 -17 -9q-218 -116 -369 -116q-88 0 -158 35l-28 14q-64 33 -99 48t-91 29t-114 14q-102 0 -235.5 -44t-228.5 -102 q-15 -9 -33 -9q-16 0 -32 8q-32 19 -32 56v742q0 35 31 55q35 21 78.5 42.5t114 52t152.5 49.5t155 19q112 0 209 -31t209 -86q38 -19 89 -19q122 0 310 112q22 12 31 17q31 16 62 -2q31 -20 31 -55z" />
<glyph unicode="&#xf11e;" horiz-adv-x="1792" d="M832 536v192q-181 -16 -384 -117v-185q205 96 384 110zM832 954v197q-172 -8 -384 -126v-189q215 111 384 118zM1664 491v184q-235 -116 -384 -71v224q-20 6 -39 15q-5 3 -33 17t-34.5 17t-31.5 15t-34.5 15.5t-32.5 13t-36 12.5t-35 8.5t-39.5 7.5t-39.5 4t-44 2 q-23 0 -49 -3v-222h19q102 0 192.5 -29t197.5 -82q19 -9 39 -15v-188q42 -17 91 -17q120 0 293 92zM1664 918v189q-169 -91 -306 -91q-45 0 -78 8v-196q148 -42 384 90zM320 1280q0 -35 -17.5 -64t-46.5 -46v-1266q0 -14 -9 -23t-23 -9h-64q-14 0 -23 9t-9 23v1266 q-29 17 -46.5 46t-17.5 64q0 53 37.5 90.5t90.5 37.5t90.5 -37.5t37.5 -90.5zM1792 1216v-763q0 -39 -35 -57q-10 -5 -17 -9q-218 -116 -369 -116q-88 0 -158 35l-28 14q-64 33 -99 48t-91 29t-114 14q-102 0 -235.5 -44t-228.5 -102q-15 -9 -33 -9q-16 0 -32 8 q-32 19 -32 56v742q0 35 31 55q35 21 78.5 42.5t114 52t152.5 49.5t155 19q112 0 209 -31t209 -86q38 -19 89 -19q122 0 310 112q22 12 31 17q31 16 62 -2q31 -20 31 -55z" />
<glyph unicode="&#xf120;" horiz-adv-x="1664" d="M585 553l-466 -466q-10 -10 -23 -10t-23 10l-50 50q-10 10 -10 23t10 23l393 393l-393 393q-10 10 -10 23t10 23l50 50q10 10 23 10t23 -10l466 -466q10 -10 10 -23t-10 -23zM1664 96v-64q0 -14 -9 -23t-23 -9h-960q-14 0 -23 9t-9 23v64q0 14 9 23t23 9h960q14 0 23 -9 t9 -23z" />
<glyph unicode="&#xf121;" horiz-adv-x="1920" d="M617 137l-50 -50q-10 -10 -23 -10t-23 10l-466 466q-10 10 -10 23t10 23l466 466q10 10 23 10t23 -10l50 -50q10 -10 10 -23t-10 -23l-393 -393l393 -393q10 -10 10 -23t-10 -23zM1208 1204l-373 -1291q-4 -13 -15.5 -19.5t-23.5 -2.5l-62 17q-13 4 -19.5 15.5t-2.5 24.5 l373 1291q4 13 15.5 19.5t23.5 2.5l62 -17q13 -4 19.5 -15.5t2.5 -24.5zM1865 553l-466 -466q-10 -10 -23 -10t-23 10l-50 50q-10 10 -10 23t10 23l393 393l-393 393q-10 10 -10 23t10 23l50 50q10 10 23 10t23 -10l466 -466q10 -10 10 -23t-10 -23z" />
<glyph unicode="&#xf122;" horiz-adv-x="1792" d="M640 454v-70q0 -42 -39 -59q-13 -5 -25 -5q-27 0 -45 19l-512 512q-19 19 -19 45t19 45l512 512q29 31 70 14q39 -17 39 -59v-69l-397 -398q-19 -19 -19 -45t19 -45zM1792 416q0 -58 -17 -133.5t-38.5 -138t-48 -125t-40.5 -90.5l-20 -40q-8 -17 -28 -17q-6 0 -9 1 q-25 8 -23 34q43 400 -106 565q-64 71 -170.5 110.5t-267.5 52.5v-251q0 -42 -39 -59q-13 -5 -25 -5q-27 0 -45 19l-512 512q-19 19 -19 45t19 45l512 512q29 31 70 14q39 -17 39 -59v-262q411 -28 599 -221q169 -173 169 -509z" />
<glyph unicode="&#xf123;" horiz-adv-x="1664" d="M1186 579l257 250l-356 52l-66 10l-30 60l-159 322v-963l59 -31l318 -168l-60 355l-12 66zM1638 841l-363 -354l86 -500q5 -33 -6 -51.5t-34 -18.5q-17 0 -40 12l-449 236l-449 -236q-23 -12 -40 -12q-23 0 -34 18.5t-6 51.5l86 500l-364 354q-32 32 -23 59.5t54 34.5 l502 73l225 455q20 41 49 41q28 0 49 -41l225 -455l502 -73q45 -7 54 -34.5t-24 -59.5z" />
<glyph unicode="&#xf124;" horiz-adv-x="1408" d="M1401 1187l-640 -1280q-17 -35 -57 -35q-5 0 -15 2q-22 5 -35.5 22.5t-13.5 39.5v576h-576q-22 0 -39.5 13.5t-22.5 35.5t4 42t29 30l1280 640q13 7 29 7q27 0 45 -19q15 -14 18.5 -34.5t-6.5 -39.5z" />
<glyph unicode="&#xf125;" horiz-adv-x="1664" d="M557 256h595v595zM512 301l595 595h-595v-595zM1664 224v-192q0 -14 -9 -23t-23 -9h-224v-224q0 -14 -9 -23t-23 -9h-192q-14 0 -23 9t-9 23v224h-864q-14 0 -23 9t-9 23v864h-224q-14 0 -23 9t-9 23v192q0 14 9 23t23 9h224v224q0 14 9 23t23 9h192q14 0 23 -9t9 -23 v-224h851l246 247q10 9 23 9t23 -9q9 -10 9 -23t-9 -23l-247 -246v-851h224q14 0 23 -9t9 -23z" />
<glyph unicode="&#xf126;" horiz-adv-x="1024" d="M288 64q0 40 -28 68t-68 28t-68 -28t-28 -68t28 -68t68 -28t68 28t28 68zM288 1216q0 40 -28 68t-68 28t-68 -28t-28 -68t28 -68t68 -28t68 28t28 68zM928 1088q0 40 -28 68t-68 28t-68 -28t-28 -68t28 -68t68 -28t68 28t28 68zM1024 1088q0 -52 -26 -96.5t-70 -69.5 q-2 -287 -226 -414q-68 -38 -203 -81q-128 -40 -169.5 -71t-41.5 -100v-26q44 -25 70 -69.5t26 -96.5q0 -80 -56 -136t-136 -56t-136 56t-56 136q0 52 26 96.5t70 69.5v820q-44 25 -70 69.5t-26 96.5q0 80 56 136t136 56t136 -56t56 -136q0 -52 -26 -96.5t-70 -69.5v-497 q54 26 154 57q55 17 87.5 29.5t70.5 31t59 39.5t40.5 51t28 69.5t8.5 91.5q-44 25 -70 69.5t-26 96.5q0 80 56 136t136 56t136 -56t56 -136z" />
<glyph unicode="&#xf127;" horiz-adv-x="1664" d="M439 265l-256 -256q-10 -9 -23 -9q-12 0 -23 9q-9 10 -9 23t9 23l256 256q10 9 23 9t23 -9q9 -10 9 -23t-9 -23zM608 224v-320q0 -14 -9 -23t-23 -9t-23 9t-9 23v320q0 14 9 23t23 9t23 -9t9 -23zM384 448q0 -14 -9 -23t-23 -9h-320q-14 0 -23 9t-9 23t9 23t23 9h320 q14 0 23 -9t9 -23zM1648 320q0 -120 -85 -203l-147 -146q-83 -83 -203 -83q-121 0 -204 85l-334 335q-21 21 -42 56l239 18l273 -274q27 -27 68 -27.5t68 26.5l147 146q28 28 28 67q0 40 -28 68l-274 275l18 239q35 -21 56 -42l336 -336q84 -86 84 -204zM1031 1044l-239 -18 l-273 274q-28 28 -68 28q-39 0 -68 -27l-147 -146q-28 -28 -28 -67q0 -40 28 -68l274 -274l-18 -240q-35 21 -56 42l-336 336q-84 86 -84 204q0 120 85 203l147 146q83 83 203 83q121 0 204 -85l334 -335q21 -21 42 -56zM1664 960q0 -14 -9 -23t-23 -9h-320q-14 0 -23 9 t-9 23t9 23t23 9h320q14 0 23 -9t9 -23zM1120 1504v-320q0 -14 -9 -23t-23 -9t-23 9t-9 23v320q0 14 9 23t23 9t23 -9t9 -23zM1527 1353l-256 -256q-11 -9 -23 -9t-23 9q-9 10 -9 23t9 23l256 256q10 9 23 9t23 -9q9 -10 9 -23t-9 -23z" />
<glyph unicode="&#xf128;" horiz-adv-x="1024" d="M704 280v-240q0 -16 -12 -28t-28 -12h-240q-16 0 -28 12t-12 28v240q0 16 12 28t28 12h240q16 0 28 -12t12 -28zM1020 880q0 -54 -15.5 -101t-35 -76.5t-55 -59.5t-57.5 -43.5t-61 -35.5q-41 -23 -68.5 -65t-27.5 -67q0 -17 -12 -32.5t-28 -15.5h-240q-15 0 -25.5 18.5 t-10.5 37.5v45q0 83 65 156.5t143 108.5q59 27 84 56t25 76q0 42 -46.5 74t-107.5 32q-65 0 -108 -29q-35 -25 -107 -115q-13 -16 -31 -16q-12 0 -25 8l-164 125q-13 10 -15.5 25t5.5 28q160 266 464 266q80 0 161 -31t146 -83t106 -127.5t41 -158.5z" />
<glyph unicode="&#xf129;" horiz-adv-x="640" d="M640 192v-128q0 -26 -19 -45t-45 -19h-512q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h64v384h-64q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h384q26 0 45 -19t19 -45v-576h64q26 0 45 -19t19 -45zM512 1344v-192q0 -26 -19 -45t-45 -19h-256q-26 0 -45 19t-19 45v192 q0 26 19 45t45 19h256q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf12a;" horiz-adv-x="640" d="M512 288v-224q0 -26 -19 -45t-45 -19h-256q-26 0 -45 19t-19 45v224q0 26 19 45t45 19h256q26 0 45 -19t19 -45zM542 1344l-28 -768q-1 -26 -20.5 -45t-45.5 -19h-256q-26 0 -45.5 19t-20.5 45l-28 768q-1 26 17.5 45t44.5 19h320q26 0 44.5 -19t17.5 -45z" />
<glyph unicode="&#xf12b;" d="M897 167v-167h-248l-159 252l-24 42q-8 9 -11 21h-3l-9 -21q-10 -20 -25 -44l-155 -250h-258v167h128l197 291l-185 272h-137v168h276l139 -228q2 -4 23 -42q8 -9 11 -21h3q3 9 11 21l25 42l140 228h257v-168h-125l-184 -267l204 -296h109zM1534 846v-206h-514l-3 27 q-4 28 -4 46q0 64 26 117t65 86.5t84 65t84 54.5t65 54t26 64q0 38 -29.5 62.5t-70.5 24.5q-51 0 -97 -39q-14 -11 -36 -38l-105 92q26 37 63 66q83 65 188 65q110 0 178 -59.5t68 -158.5q0 -56 -24.5 -103t-62 -76.5t-81.5 -58.5t-82 -50.5t-65.5 -51.5t-30.5 -63h232v80 h126z" />
<glyph unicode="&#xf12c;" d="M897 167v-167h-248l-159 252l-24 42q-8 9 -11 21h-3l-9 -21q-10 -20 -25 -44l-155 -250h-258v167h128l197 291l-185 272h-137v168h276l139 -228q2 -4 23 -42q8 -9 11 -21h3q3 9 11 21l25 42l140 228h257v-168h-125l-184 -267l204 -296h109zM1536 -50v-206h-514l-4 27 q-3 45 -3 46q0 64 26 117t65 86.5t84 65t84 54.5t65 54t26 64q0 38 -29.5 62.5t-70.5 24.5q-51 0 -97 -39q-14 -11 -36 -38l-105 92q26 37 63 66q80 65 188 65q110 0 178 -59.5t68 -158.5q0 -66 -34.5 -118.5t-84 -86t-99.5 -62.5t-87 -63t-41 -73h232v80h126z" />
<glyph unicode="&#xf12d;" horiz-adv-x="1920" d="M896 128l336 384h-768l-336 -384h768zM1909 1205q15 -34 9.5 -71.5t-30.5 -65.5l-896 -1024q-38 -44 -96 -44h-768q-38 0 -69.5 20.5t-47.5 54.5q-15 34 -9.5 71.5t30.5 65.5l896 1024q38 44 96 44h768q38 0 69.5 -20.5t47.5 -54.5z" />
<glyph unicode="&#xf12e;" horiz-adv-x="1664" d="M1664 438q0 -81 -44.5 -135t-123.5 -54q-41 0 -77.5 17.5t-59 38t-56.5 38t-71 17.5q-110 0 -110 -124q0 -39 16 -115t15 -115v-5q-22 0 -33 -1q-34 -3 -97.5 -11.5t-115.5 -13.5t-98 -5q-61 0 -103 26.5t-42 83.5q0 37 17.5 71t38 56.5t38 59t17.5 77.5q0 79 -54 123.5 t-135 44.5q-84 0 -143 -45.5t-59 -127.5q0 -43 15 -83t33.5 -64.5t33.5 -53t15 -50.5q0 -45 -46 -89q-37 -35 -117 -35q-95 0 -245 24q-9 2 -27.5 4t-27.5 4l-13 2q-1 0 -3 1q-2 0 -2 1v1024q2 -1 17.5 -3.5t34 -5t21.5 -3.5q150 -24 245 -24q80 0 117 35q46 44 46 89 q0 22 -15 50.5t-33.5 53t-33.5 64.5t-15 83q0 82 59 127.5t144 45.5q80 0 134 -44.5t54 -123.5q0 -41 -17.5 -77.5t-38 -59t-38 -56.5t-17.5 -71q0 -57 42 -83.5t103 -26.5q64 0 180 15t163 17v-2q-1 -2 -3.5 -17.5t-5 -34t-3.5 -21.5q-24 -150 -24 -245q0 -80 35 -117 q44 -46 89 -46q22 0 50.5 15t53 33.5t64.5 33.5t83 15q82 0 127.5 -59t45.5 -143z" />
<glyph unicode="&#xf130;" horiz-adv-x="1152" d="M1152 832v-128q0 -221 -147.5 -384.5t-364.5 -187.5v-132h256q26 0 45 -19t19 -45t-19 -45t-45 -19h-640q-26 0 -45 19t-19 45t19 45t45 19h256v132q-217 24 -364.5 187.5t-147.5 384.5v128q0 26 19 45t45 19t45 -19t19 -45v-128q0 -185 131.5 -316.5t316.5 -131.5 t316.5 131.5t131.5 316.5v128q0 26 19 45t45 19t45 -19t19 -45zM896 1216v-512q0 -132 -94 -226t-226 -94t-226 94t-94 226v512q0 132 94 226t226 94t226 -94t94 -226z" />
<glyph unicode="&#xf131;" horiz-adv-x="1408" d="M271 591l-101 -101q-42 103 -42 214v128q0 26 19 45t45 19t45 -19t19 -45v-128q0 -53 15 -113zM1385 1193l-361 -361v-128q0 -132 -94 -226t-226 -94q-55 0 -109 19l-96 -96q97 -51 205 -51q185 0 316.5 131.5t131.5 316.5v128q0 26 19 45t45 19t45 -19t19 -45v-128 q0 -221 -147.5 -384.5t-364.5 -187.5v-132h256q26 0 45 -19t19 -45t-19 -45t-45 -19h-640q-26 0 -45 19t-19 45t19 45t45 19h256v132q-125 13 -235 81l-254 -254q-10 -10 -23 -10t-23 10l-82 82q-10 10 -10 23t10 23l1234 1234q10 10 23 10t23 -10l82 -82q10 -10 10 -23 t-10 -23zM1005 1325l-621 -621v512q0 132 94 226t226 94q102 0 184.5 -59t116.5 -152z" />
<glyph unicode="&#xf132;" horiz-adv-x="1280" d="M1088 576v640h-448v-1137q119 63 213 137q235 184 235 360zM1280 1344v-768q0 -86 -33.5 -170.5t-83 -150t-118 -127.5t-126.5 -103t-121 -77.5t-89.5 -49.5t-42.5 -20q-12 -6 -26 -6t-26 6q-16 7 -42.5 20t-89.5 49.5t-121 77.5t-126.5 103t-118 127.5t-83 150 t-33.5 170.5v768q0 26 19 45t45 19h1152q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf133;" horiz-adv-x="1664" d="M128 -128h1408v1024h-1408v-1024zM512 1088v288q0 14 -9 23t-23 9h-64q-14 0 -23 -9t-9 -23v-288q0 -14 9 -23t23 -9h64q14 0 23 9t9 23zM1280 1088v288q0 14 -9 23t-23 9h-64q-14 0 -23 -9t-9 -23v-288q0 -14 9 -23t23 -9h64q14 0 23 9t9 23zM1664 1152v-1280 q0 -52 -38 -90t-90 -38h-1408q-52 0 -90 38t-38 90v1280q0 52 38 90t90 38h128v96q0 66 47 113t113 47h64q66 0 113 -47t47 -113v-96h384v96q0 66 47 113t113 47h64q66 0 113 -47t47 -113v-96h128q52 0 90 -38t38 -90z" />
<glyph unicode="&#xf134;" horiz-adv-x="1408" d="M512 1344q0 26 -19 45t-45 19t-45 -19t-19 -45t19 -45t45 -19t45 19t19 45zM1408 1376v-320q0 -16 -12 -25q-8 -7 -20 -7q-4 0 -7 1l-448 96q-11 2 -18 11t-7 20h-256v-102q111 -23 183.5 -111t72.5 -203v-800q0 -26 -19 -45t-45 -19h-512q-26 0 -45 19t-19 45v800 q0 106 62.5 190.5t161.5 114.5v111h-32q-59 0 -115 -23.5t-91.5 -53t-66 -66.5t-40.5 -53.5t-14 -24.5q-17 -35 -57 -35q-16 0 -29 7q-23 12 -31.5 37t3.5 49q5 10 14.5 26t37.5 53.5t60.5 70t85 67t108.5 52.5q-25 42 -25 86q0 66 47 113t113 47t113 -47t47 -113 q0 -33 -14 -64h302q0 11 7 20t18 11l448 96q3 1 7 1q12 0 20 -7q12 -9 12 -25z" />
<glyph unicode="&#xf135;" horiz-adv-x="1664" d="M1440 1088q0 40 -28 68t-68 28t-68 -28t-28 -68t28 -68t68 -28t68 28t28 68zM1664 1376q0 -249 -75.5 -430.5t-253.5 -360.5q-81 -80 -195 -176l-20 -379q-2 -16 -16 -26l-384 -224q-7 -4 -16 -4q-12 0 -23 9l-64 64q-13 14 -8 32l85 276l-281 281l-276 -85q-3 -1 -9 -1 q-14 0 -23 9l-64 64q-17 19 -5 39l224 384q10 14 26 16l379 20q96 114 176 195q188 187 358 258t431 71q14 0 24 -9.5t10 -22.5z" />
<glyph unicode="&#xf136;" horiz-adv-x="1792" d="M1745 763l-164 -763h-334l178 832q13 56 -15 88q-27 33 -83 33h-169l-204 -953h-334l204 953h-286l-204 -953h-334l204 953l-153 327h1276q101 0 189.5 -40.5t147.5 -113.5q60 -73 81 -168.5t0 -194.5z" />
<glyph unicode="&#xf137;" d="M909 141l102 102q19 19 19 45t-19 45l-307 307l307 307q19 19 19 45t-19 45l-102 102q-19 19 -45 19t-45 -19l-454 -454q-19 -19 -19 -45t19 -45l454 -454q19 -19 45 -19t45 19zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5 t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf138;" d="M717 141l454 454q19 19 19 45t-19 45l-454 454q-19 19 -45 19t-45 -19l-102 -102q-19 -19 -19 -45t19 -45l307 -307l-307 -307q-19 -19 -19 -45t19 -45l102 -102q19 -19 45 -19t45 19zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5 t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf139;" d="M1165 397l102 102q19 19 19 45t-19 45l-454 454q-19 19 -45 19t-45 -19l-454 -454q-19 -19 -19 -45t19 -45l102 -102q19 -19 45 -19t45 19l307 307l307 -307q19 -19 45 -19t45 19zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5 t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf13a;" d="M813 237l454 454q19 19 19 45t-19 45l-102 102q-19 19 -45 19t-45 -19l-307 -307l-307 307q-19 19 -45 19t-45 -19l-102 -102q-19 -19 -19 -45t19 -45l454 -454q19 -19 45 -19t45 19zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5 t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf13b;" horiz-adv-x="1408" d="M1130 939l16 175h-884l47 -534h612l-22 -228l-197 -53l-196 53l-13 140h-175l22 -278l362 -100h4v1l359 99l50 544h-644l-15 181h674zM0 1408h1408l-128 -1438l-578 -162l-574 162z" />
<glyph unicode="&#xf13c;" horiz-adv-x="1792" d="M275 1408h1505l-266 -1333l-804 -267l-698 267l71 356h297l-29 -147l422 -161l486 161l68 339h-1208l58 297h1209l38 191h-1208z" />
<glyph unicode="&#xf13d;" horiz-adv-x="1792" d="M960 1280q0 26 -19 45t-45 19t-45 -19t-19 -45t19 -45t45 -19t45 19t19 45zM1792 352v-352q0 -22 -20 -30q-8 -2 -12 -2q-13 0 -23 9l-93 93q-119 -143 -318.5 -226.5t-429.5 -83.5t-429.5 83.5t-318.5 226.5l-93 -93q-9 -9 -23 -9q-4 0 -12 2q-20 8 -20 30v352 q0 14 9 23t23 9h352q22 0 30 -20q8 -19 -7 -35l-100 -100q67 -91 189.5 -153.5t271.5 -82.5v647h-192q-26 0 -45 19t-19 45v128q0 26 19 45t45 19h192v163q-58 34 -93 92.5t-35 128.5q0 106 75 181t181 75t181 -75t75 -181q0 -70 -35 -128.5t-93 -92.5v-163h192q26 0 45 -19 t19 -45v-128q0 -26 -19 -45t-45 -19h-192v-647q149 20 271.5 82.5t189.5 153.5l-100 100q-15 16 -7 35q8 20 30 20h352q14 0 23 -9t9 -23z" />
<glyph unicode="&#xf13e;" horiz-adv-x="1152" d="M1056 768q40 0 68 -28t28 -68v-576q0 -40 -28 -68t-68 -28h-960q-40 0 -68 28t-28 68v576q0 40 28 68t68 28h32v320q0 185 131.5 316.5t316.5 131.5t316.5 -131.5t131.5 -316.5q0 -26 -19 -45t-45 -19h-64q-26 0 -45 19t-19 45q0 106 -75 181t-181 75t-181 -75t-75 -181 v-320h736z" />
<glyph unicode="&#xf140;" d="M1024 640q0 -106 -75 -181t-181 -75t-181 75t-75 181t75 181t181 75t181 -75t75 -181zM1152 640q0 159 -112.5 271.5t-271.5 112.5t-271.5 -112.5t-112.5 -271.5t112.5 -271.5t271.5 -112.5t271.5 112.5t112.5 271.5zM1280 640q0 -212 -150 -362t-362 -150t-362 150 t-150 362t150 362t362 150t362 -150t150 -362zM1408 640q0 130 -51 248.5t-136.5 204t-204 136.5t-248.5 51t-248.5 -51t-204 -136.5t-136.5 -204t-51 -248.5t51 -248.5t136.5 -204t204 -136.5t248.5 -51t248.5 51t204 136.5t136.5 204t51 248.5zM1536 640 q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf141;" horiz-adv-x="1408" d="M384 800v-192q0 -40 -28 -68t-68 -28h-192q-40 0 -68 28t-28 68v192q0 40 28 68t68 28h192q40 0 68 -28t28 -68zM896 800v-192q0 -40 -28 -68t-68 -28h-192q-40 0 -68 28t-28 68v192q0 40 28 68t68 28h192q40 0 68 -28t28 -68zM1408 800v-192q0 -40 -28 -68t-68 -28h-192 q-40 0 -68 28t-28 68v192q0 40 28 68t68 28h192q40 0 68 -28t28 -68z" />
<glyph unicode="&#xf142;" horiz-adv-x="384" d="M384 288v-192q0 -40 -28 -68t-68 -28h-192q-40 0 -68 28t-28 68v192q0 40 28 68t68 28h192q40 0 68 -28t28 -68zM384 800v-192q0 -40 -28 -68t-68 -28h-192q-40 0 -68 28t-28 68v192q0 40 28 68t68 28h192q40 0 68 -28t28 -68zM384 1312v-192q0 -40 -28 -68t-68 -28h-192 q-40 0 -68 28t-28 68v192q0 40 28 68t68 28h192q40 0 68 -28t28 -68z" />
<glyph unicode="&#xf143;" d="M512 256q0 53 -37.5 90.5t-90.5 37.5t-90.5 -37.5t-37.5 -90.5t37.5 -90.5t90.5 -37.5t90.5 37.5t37.5 90.5zM863 162q-13 232 -177 396t-396 177q-14 1 -24 -9t-10 -23v-128q0 -13 8.5 -22t21.5 -10q154 -11 264 -121t121 -264q1 -13 10 -21.5t22 -8.5h128q13 0 23 10 t9 24zM1247 161q-5 154 -56 297.5t-139.5 260t-205 205t-260 139.5t-297.5 56q-14 1 -23 -9q-10 -10 -10 -23v-128q0 -13 9 -22t22 -10q204 -7 378 -111.5t278.5 -278.5t111.5 -378q1 -13 10 -22t22 -9h128q13 0 23 10q11 9 9 23zM1536 1120v-960q0 -119 -84.5 -203.5 t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf144;" d="M768 1408q209 0 385.5 -103t279.5 -279.5t103 -385.5t-103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103zM1152 585q32 18 32 55t-32 55l-544 320q-31 19 -64 1q-32 -19 -32 -56v-640q0 -37 32 -56 q16 -8 32 -8q17 0 32 9z" />
<glyph unicode="&#xf145;" horiz-adv-x="1792" d="M1024 1084l316 -316l-572 -572l-316 316zM813 105l618 618q19 19 19 45t-19 45l-362 362q-18 18 -45 18t-45 -18l-618 -618q-19 -19 -19 -45t19 -45l362 -362q18 -18 45 -18t45 18zM1702 742l-907 -908q-37 -37 -90.5 -37t-90.5 37l-126 126q56 56 56 136t-56 136 t-136 56t-136 -56l-125 126q-37 37 -37 90.5t37 90.5l907 906q37 37 90.5 37t90.5 -37l125 -125q-56 -56 -56 -136t56 -136t136 -56t136 56l126 -125q37 -37 37 -90.5t-37 -90.5z" />
<glyph unicode="&#xf146;" d="M1280 576v128q0 26 -19 45t-45 19h-896q-26 0 -45 -19t-19 -45v-128q0 -26 19 -45t45 -19h896q26 0 45 19t19 45zM1536 1120v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5 t84.5 -203.5z" />
<glyph unicode="&#xf147;" horiz-adv-x="1408" d="M1152 736v-64q0 -14 -9 -23t-23 -9h-832q-14 0 -23 9t-9 23v64q0 14 9 23t23 9h832q14 0 23 -9t9 -23zM1280 288v832q0 66 -47 113t-113 47h-832q-66 0 -113 -47t-47 -113v-832q0 -66 47 -113t113 -47h832q66 0 113 47t47 113zM1408 1120v-832q0 -119 -84.5 -203.5 t-203.5 -84.5h-832q-119 0 -203.5 84.5t-84.5 203.5v832q0 119 84.5 203.5t203.5 84.5h832q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf148;" horiz-adv-x="1024" d="M1018 933q-18 -37 -58 -37h-192v-864q0 -14 -9 -23t-23 -9h-704q-21 0 -29 18q-8 20 4 35l160 192q9 11 25 11h320v640h-192q-40 0 -58 37q-17 37 9 68l320 384q18 22 49 22t49 -22l320 -384q27 -32 9 -68z" />
<glyph unicode="&#xf149;" horiz-adv-x="1024" d="M32 1280h704q13 0 22.5 -9.5t9.5 -23.5v-863h192q40 0 58 -37t-9 -69l-320 -384q-18 -22 -49 -22t-49 22l-320 384q-26 31 -9 69q18 37 58 37h192v640h-320q-14 0 -25 11l-160 192q-13 14 -4 34q9 19 29 19z" />
<glyph unicode="&#xf14a;" d="M685 237l614 614q19 19 19 45t-19 45l-102 102q-19 19 -45 19t-45 -19l-467 -467l-211 211q-19 19 -45 19t-45 -19l-102 -102q-19 -19 -19 -45t19 -45l358 -358q19 -19 45 -19t45 19zM1536 1120v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5 t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf14b;" d="M404 428l152 -152l-52 -52h-56v96h-96v56zM818 818q14 -13 -3 -30l-291 -291q-17 -17 -30 -3q-14 13 3 30l291 291q17 17 30 3zM544 128l544 544l-288 288l-544 -544v-288h288zM1152 736l92 92q28 28 28 68t-28 68l-152 152q-28 28 -68 28t-68 -28l-92 -92zM1536 1120 v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf14c;" d="M1280 608v480q0 26 -19 45t-45 19h-480q-42 0 -59 -39q-17 -41 14 -70l144 -144l-534 -534q-19 -19 -19 -45t19 -45l102 -102q19 -19 45 -19t45 19l534 534l144 -144q18 -19 45 -19q12 0 25 5q39 17 39 59zM1536 1120v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960 q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf14d;" d="M1005 435l352 352q19 19 19 45t-19 45l-352 352q-30 31 -69 14q-40 -17 -40 -59v-160q-119 0 -216 -19.5t-162.5 -51t-114 -79t-76.5 -95.5t-44.5 -109t-21.5 -111.5t-5 -110.5q0 -181 167 -404q10 -12 25 -12q7 0 13 3q22 9 19 33q-44 354 62 473q46 52 130 75.5 t224 23.5v-160q0 -42 40 -59q12 -5 24 -5q26 0 45 19zM1536 1120v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf14e;" d="M640 448l256 128l-256 128v-256zM1024 1039v-542l-512 -256v542zM1312 640q0 148 -73 273t-198 198t-273 73t-273 -73t-198 -198t-73 -273t73 -273t198 -198t273 -73t273 73t198 198t73 273zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103 t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf150;" d="M1145 861q18 -35 -5 -66l-320 -448q-19 -27 -52 -27t-52 27l-320 448q-23 31 -5 66q17 35 57 35h640q40 0 57 -35zM1280 160v960q0 13 -9.5 22.5t-22.5 9.5h-960q-13 0 -22.5 -9.5t-9.5 -22.5v-960q0 -13 9.5 -22.5t22.5 -9.5h960q13 0 22.5 9.5t9.5 22.5zM1536 1120 v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf151;" d="M1145 419q-17 -35 -57 -35h-640q-40 0 -57 35q-18 35 5 66l320 448q19 27 52 27t52 -27l320 -448q23 -31 5 -66zM1280 160v960q0 13 -9.5 22.5t-22.5 9.5h-960q-13 0 -22.5 -9.5t-9.5 -22.5v-960q0 -13 9.5 -22.5t22.5 -9.5h960q13 0 22.5 9.5t9.5 22.5zM1536 1120v-960 q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf152;" d="M1088 640q0 -33 -27 -52l-448 -320q-31 -23 -66 -5q-35 17 -35 57v640q0 40 35 57q35 18 66 -5l448 -320q27 -19 27 -52zM1280 160v960q0 14 -9 23t-23 9h-960q-14 0 -23 -9t-9 -23v-960q0 -14 9 -23t23 -9h960q14 0 23 9t9 23zM1536 1120v-960q0 -119 -84.5 -203.5 t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf153;" horiz-adv-x="1024" d="M976 229l35 -159q3 -12 -3 -22.5t-17 -14.5l-5 -1q-4 -2 -10.5 -3.5t-16 -4.5t-21.5 -5.5t-25.5 -5t-30 -5t-33.5 -4.5t-36.5 -3t-38.5 -1q-234 0 -409 130.5t-238 351.5h-95q-13 0 -22.5 9.5t-9.5 22.5v113q0 13 9.5 22.5t22.5 9.5h66q-2 57 1 105h-67q-14 0 -23 9 t-9 23v114q0 14 9 23t23 9h98q67 210 243.5 338t400.5 128q102 0 194 -23q11 -3 20 -15q6 -11 3 -24l-43 -159q-3 -13 -14 -19.5t-24 -2.5l-4 1q-4 1 -11.5 2.5l-17.5 3.5t-22.5 3.5t-26 3t-29 2.5t-29.5 1q-126 0 -226 -64t-150 -176h468q16 0 25 -12q10 -12 7 -26 l-24 -114q-5 -26 -32 -26h-488q-3 -37 0 -105h459q15 0 25 -12q9 -12 6 -27l-24 -112q-2 -11 -11 -18.5t-20 -7.5h-387q48 -117 149.5 -185.5t228.5 -68.5q18 0 36 1.5t33.5 3.5t29.5 4.5t24.5 5t18.5 4.5l12 3l5 2q13 5 26 -2q12 -7 15 -21z" />
<glyph unicode="&#xf154;" horiz-adv-x="1024" d="M1020 399v-367q0 -14 -9 -23t-23 -9h-956q-14 0 -23 9t-9 23v150q0 13 9.5 22.5t22.5 9.5h97v383h-95q-14 0 -23 9.5t-9 22.5v131q0 14 9 23t23 9h95v223q0 171 123.5 282t314.5 111q185 0 335 -125q9 -8 10 -20.5t-7 -22.5l-103 -127q-9 -11 -22 -12q-13 -2 -23 7 q-5 5 -26 19t-69 32t-93 18q-85 0 -137 -47t-52 -123v-215h305q13 0 22.5 -9t9.5 -23v-131q0 -13 -9.5 -22.5t-22.5 -9.5h-305v-379h414v181q0 13 9 22.5t23 9.5h162q14 0 23 -9.5t9 -22.5z" />
<glyph unicode="&#xf155;" horiz-adv-x="1024" d="M978 351q0 -153 -99.5 -263.5t-258.5 -136.5v-175q0 -14 -9 -23t-23 -9h-135q-13 0 -22.5 9.5t-9.5 22.5v175q-66 9 -127.5 31t-101.5 44.5t-74 48t-46.5 37.5t-17.5 18q-17 21 -2 41l103 135q7 10 23 12q15 2 24 -9l2 -2q113 -99 243 -125q37 -8 74 -8q81 0 142.5 43 t61.5 122q0 28 -15 53t-33.5 42t-58.5 37.5t-66 32t-80 32.5q-39 16 -61.5 25t-61.5 26.5t-62.5 31t-56.5 35.5t-53.5 42.5t-43.5 49t-35.5 58t-21 66.5t-8.5 78q0 138 98 242t255 134v180q0 13 9.5 22.5t22.5 9.5h135q14 0 23 -9t9 -23v-176q57 -6 110.5 -23t87 -33.5 t63.5 -37.5t39 -29t15 -14q17 -18 5 -38l-81 -146q-8 -15 -23 -16q-14 -3 -27 7q-3 3 -14.5 12t-39 26.5t-58.5 32t-74.5 26t-85.5 11.5q-95 0 -155 -43t-60 -111q0 -26 8.5 -48t29.5 -41.5t39.5 -33t56 -31t60.5 -27t70 -27.5q53 -20 81 -31.5t76 -35t75.5 -42.5t62 -50 t53 -63.5t31.5 -76.5t13 -94z" />
<glyph unicode="&#xf156;" horiz-adv-x="898" d="M898 1066v-102q0 -14 -9 -23t-23 -9h-168q-23 -144 -129 -234t-276 -110q167 -178 459 -536q14 -16 4 -34q-8 -18 -29 -18h-195q-16 0 -25 12q-306 367 -498 571q-9 9 -9 22v127q0 13 9.5 22.5t22.5 9.5h112q132 0 212.5 43t102.5 125h-427q-14 0 -23 9t-9 23v102 q0 14 9 23t23 9h413q-57 113 -268 113h-145q-13 0 -22.5 9.5t-9.5 22.5v133q0 14 9 23t23 9h832q14 0 23 -9t9 -23v-102q0 -14 -9 -23t-23 -9h-233q47 -61 64 -144h171q14 0 23 -9t9 -23z" />
<glyph unicode="&#xf157;" horiz-adv-x="1027" d="M603 0h-172q-13 0 -22.5 9t-9.5 23v330h-288q-13 0 -22.5 9t-9.5 23v103q0 13 9.5 22.5t22.5 9.5h288v85h-288q-13 0 -22.5 9t-9.5 23v104q0 13 9.5 22.5t22.5 9.5h214l-321 578q-8 16 0 32q10 16 28 16h194q19 0 29 -18l215 -425q19 -38 56 -125q10 24 30.5 68t27.5 61 l191 420q8 19 29 19h191q17 0 27 -16q9 -14 1 -31l-313 -579h215q13 0 22.5 -9.5t9.5 -22.5v-104q0 -14 -9.5 -23t-22.5 -9h-290v-85h290q13 0 22.5 -9.5t9.5 -22.5v-103q0 -14 -9.5 -23t-22.5 -9h-290v-330q0 -13 -9.5 -22.5t-22.5 -9.5z" />
<glyph unicode="&#xf158;" horiz-adv-x="1280" d="M1043 971q0 100 -65 162t-171 62h-320v-448h320q106 0 171 62t65 162zM1280 971q0 -193 -126.5 -315t-326.5 -122h-340v-118h505q14 0 23 -9t9 -23v-128q0 -14 -9 -23t-23 -9h-505v-192q0 -14 -9.5 -23t-22.5 -9h-167q-14 0 -23 9t-9 23v192h-224q-14 0 -23 9t-9 23v128 q0 14 9 23t23 9h224v118h-224q-14 0 -23 9t-9 23v149q0 13 9 22.5t23 9.5h224v629q0 14 9 23t23 9h539q200 0 326.5 -122t126.5 -315z" />
<glyph unicode="&#xf159;" horiz-adv-x="1792" d="M514 341l81 299h-159l75 -300q1 -1 1 -3t1 -3q0 1 0.5 3.5t0.5 3.5zM630 768l35 128h-292l32 -128h225zM822 768h139l-35 128h-70zM1271 340l78 300h-162l81 -299q0 -1 0.5 -3.5t1.5 -3.5q0 1 0.5 3t0.5 3zM1382 768l33 128h-297l34 -128h230zM1792 736v-64q0 -14 -9 -23 t-23 -9h-213l-164 -616q-7 -24 -31 -24h-159q-24 0 -31 24l-166 616h-209l-167 -616q-7 -24 -31 -24h-159q-11 0 -19.5 7t-10.5 17l-160 616h-208q-14 0 -23 9t-9 23v64q0 14 9 23t23 9h175l-33 128h-142q-14 0 -23 9t-9 23v64q0 14 9 23t23 9h109l-89 344q-5 15 5 28 q10 12 26 12h137q26 0 31 -24l90 -360h359l97 360q7 24 31 24h126q24 0 31 -24l98 -360h365l93 360q5 24 31 24h137q16 0 26 -12q10 -13 5 -28l-91 -344h111q14 0 23 -9t9 -23v-64q0 -14 -9 -23t-23 -9h-145l-34 -128h179q14 0 23 -9t9 -23z" />
<glyph unicode="&#xf15a;" horiz-adv-x="1280" d="M1167 896q18 -182 -131 -258q117 -28 175 -103t45 -214q-7 -71 -32.5 -125t-64.5 -89t-97 -58.5t-121.5 -34.5t-145.5 -15v-255h-154v251q-80 0 -122 1v-252h-154v255q-18 0 -54 0.5t-55 0.5h-200l31 183h111q50 0 58 51v402h16q-6 1 -16 1v287q-13 68 -89 68h-111v164 l212 -1q64 0 97 1v252h154v-247q82 2 122 2v245h154v-252q79 -7 140 -22.5t113 -45t82.5 -78t36.5 -114.5zM952 351q0 36 -15 64t-37 46t-57.5 30.5t-65.5 18.5t-74 9t-69 3t-64.5 -1t-47.5 -1v-338q8 0 37 -0.5t48 -0.5t53 1.5t58.5 4t57 8.5t55.5 14t47.5 21t39.5 30 t24.5 40t9.5 51zM881 827q0 33 -12.5 58.5t-30.5 42t-48 28t-55 16.5t-61.5 8t-58 2.5t-54 -1t-39.5 -0.5v-307q5 0 34.5 -0.5t46.5 0t50 2t55 5.5t51.5 11t48.5 18.5t37 27t27 38.5t9 51z" />
<glyph unicode="&#xf15b;" d="M1024 1024v472q22 -14 36 -28l408 -408q14 -14 28 -36h-472zM896 992q0 -40 28 -68t68 -28h544v-1056q0 -40 -28 -68t-68 -28h-1344q-40 0 -68 28t-28 68v1600q0 40 28 68t68 28h800v-544z" />
<glyph unicode="&#xf15c;" d="M1468 1060q14 -14 28 -36h-472v472q22 -14 36 -28zM992 896h544v-1056q0 -40 -28 -68t-68 -28h-1344q-40 0 -68 28t-28 68v1600q0 40 28 68t68 28h800v-544q0 -40 28 -68t68 -28zM1152 160v64q0 14 -9 23t-23 9h-704q-14 0 -23 -9t-9 -23v-64q0 -14 9 -23t23 -9h704 q14 0 23 9t9 23zM1152 416v64q0 14 -9 23t-23 9h-704q-14 0 -23 -9t-9 -23v-64q0 -14 9 -23t23 -9h704q14 0 23 9t9 23zM1152 672v64q0 14 -9 23t-23 9h-704q-14 0 -23 -9t-9 -23v-64q0 -14 9 -23t23 -9h704q14 0 23 9t9 23z" />
<glyph unicode="&#xf15d;" horiz-adv-x="1664" d="M1191 1128h177l-72 218l-12 47q-2 16 -2 20h-4l-3 -20q0 -1 -3.5 -18t-7.5 -29zM736 96q0 -12 -10 -24l-319 -319q-10 -9 -23 -9q-12 0 -23 9l-320 320q-15 16 -7 35q8 20 30 20h192v1376q0 14 9 23t23 9h192q14 0 23 -9t9 -23v-1376h192q14 0 23 -9t9 -23zM1572 -23 v-233h-584v90l369 529q12 18 21 27l11 9v3q-2 0 -6.5 -0.5t-7.5 -0.5q-12 -3 -30 -3h-232v-115h-120v229h567v-89l-369 -530q-6 -8 -21 -26l-11 -11v-2l14 2q9 2 30 2h248v119h121zM1661 874v-106h-288v106h75l-47 144h-243l-47 -144h75v-106h-287v106h70l230 662h162 l230 -662h70z" />
<glyph unicode="&#xf15e;" horiz-adv-x="1664" d="M1191 104h177l-72 218l-12 47q-2 16 -2 20h-4l-3 -20q0 -1 -3.5 -18t-7.5 -29zM736 96q0 -12 -10 -24l-319 -319q-10 -9 -23 -9q-12 0 -23 9l-320 320q-15 16 -7 35q8 20 30 20h192v1376q0 14 9 23t23 9h192q14 0 23 -9t9 -23v-1376h192q14 0 23 -9t9 -23zM1661 -150 v-106h-288v106h75l-47 144h-243l-47 -144h75v-106h-287v106h70l230 662h162l230 -662h70zM1572 1001v-233h-584v90l369 529q12 18 21 27l11 9v3q-2 0 -6.5 -0.5t-7.5 -0.5q-12 -3 -30 -3h-232v-115h-120v229h567v-89l-369 -530q-6 -8 -21 -26l-11 -10v-3l14 3q9 1 30 1h248 v119h121z" />
<glyph unicode="&#xf160;" horiz-adv-x="1792" d="M736 96q0 -12 -10 -24l-319 -319q-10 -9 -23 -9q-12 0 -23 9l-320 320q-15 16 -7 35q8 20 30 20h192v1376q0 14 9 23t23 9h192q14 0 23 -9t9 -23v-1376h192q14 0 23 -9t9 -23zM1792 -32v-192q0 -14 -9 -23t-23 -9h-832q-14 0 -23 9t-9 23v192q0 14 9 23t23 9h832 q14 0 23 -9t9 -23zM1600 480v-192q0 -14 -9 -23t-23 -9h-640q-14 0 -23 9t-9 23v192q0 14 9 23t23 9h640q14 0 23 -9t9 -23zM1408 992v-192q0 -14 -9 -23t-23 -9h-448q-14 0 -23 9t-9 23v192q0 14 9 23t23 9h448q14 0 23 -9t9 -23zM1216 1504v-192q0 -14 -9 -23t-23 -9h-256 q-14 0 -23 9t-9 23v192q0 14 9 23t23 9h256q14 0 23 -9t9 -23z" />
<glyph unicode="&#xf161;" horiz-adv-x="1792" d="M1216 -32v-192q0 -14 -9 -23t-23 -9h-256q-14 0 -23 9t-9 23v192q0 14 9 23t23 9h256q14 0 23 -9t9 -23zM736 96q0 -12 -10 -24l-319 -319q-10 -9 -23 -9q-12 0 -23 9l-320 320q-15 16 -7 35q8 20 30 20h192v1376q0 14 9 23t23 9h192q14 0 23 -9t9 -23v-1376h192 q14 0 23 -9t9 -23zM1408 480v-192q0 -14 -9 -23t-23 -9h-448q-14 0 -23 9t-9 23v192q0 14 9 23t23 9h448q14 0 23 -9t9 -23zM1600 992v-192q0 -14 -9 -23t-23 -9h-640q-14 0 -23 9t-9 23v192q0 14 9 23t23 9h640q14 0 23 -9t9 -23zM1792 1504v-192q0 -14 -9 -23t-23 -9h-832 q-14 0 -23 9t-9 23v192q0 14 9 23t23 9h832q14 0 23 -9t9 -23z" />
<glyph unicode="&#xf162;" d="M1346 223q0 63 -44 116t-103 53q-52 0 -83 -37t-31 -94t36.5 -95t104.5 -38q50 0 85 27t35 68zM736 96q0 -12 -10 -24l-319 -319q-10 -9 -23 -9q-12 0 -23 9l-320 320q-15 16 -7 35q8 20 30 20h192v1376q0 14 9 23t23 9h192q14 0 23 -9t9 -23v-1376h192q14 0 23 -9t9 -23 zM1486 165q0 -62 -13 -121.5t-41 -114t-68 -95.5t-98.5 -65.5t-127.5 -24.5q-62 0 -108 16q-24 8 -42 15l39 113q15 -7 31 -11q37 -13 75 -13q84 0 134.5 58.5t66.5 145.5h-2q-21 -23 -61.5 -37t-84.5 -14q-106 0 -173 71.5t-67 172.5q0 105 72 178t181 73q123 0 205 -94.5 t82 -252.5zM1456 882v-114h-469v114h167v432q0 7 0.5 19t0.5 17v16h-2l-7 -12q-8 -13 -26 -31l-62 -58l-82 86l192 185h123v-654h165z" />
<glyph unicode="&#xf163;" d="M1346 1247q0 63 -44 116t-103 53q-52 0 -83 -37t-31 -94t36.5 -95t104.5 -38q50 0 85 27t35 68zM736 96q0 -12 -10 -24l-319 -319q-10 -9 -23 -9q-12 0 -23 9l-320 320q-15 16 -7 35q8 20 30 20h192v1376q0 14 9 23t23 9h192q14 0 23 -9t9 -23v-1376h192q14 0 23 -9 t9 -23zM1456 -142v-114h-469v114h167v432q0 7 0.5 19t0.5 17v16h-2l-7 -12q-8 -13 -26 -31l-62 -58l-82 86l192 185h123v-654h165zM1486 1189q0 -62 -13 -121.5t-41 -114t-68 -95.5t-98.5 -65.5t-127.5 -24.5q-62 0 -108 16q-24 8 -42 15l39 113q15 -7 31 -11q37 -13 75 -13 q84 0 134.5 58.5t66.5 145.5h-2q-21 -23 -61.5 -37t-84.5 -14q-106 0 -173 71.5t-67 172.5q0 105 72 178t181 73q123 0 205 -94.5t82 -252.5z" />
<glyph unicode="&#xf164;" horiz-adv-x="1664" d="M256 192q0 26 -19 45t-45 19q-27 0 -45.5 -19t-18.5 -45q0 -27 18.5 -45.5t45.5 -18.5q26 0 45 18.5t19 45.5zM416 704v-640q0 -26 -19 -45t-45 -19h-288q-26 0 -45 19t-19 45v640q0 26 19 45t45 19h288q26 0 45 -19t19 -45zM1600 704q0 -86 -55 -149q15 -44 15 -76 q3 -76 -43 -137q17 -56 0 -117q-15 -57 -54 -94q9 -112 -49 -181q-64 -76 -197 -78h-36h-76h-17q-66 0 -144 15.5t-121.5 29t-120.5 39.5q-123 43 -158 44q-26 1 -45 19.5t-19 44.5v641q0 25 18 43.5t43 20.5q24 2 76 59t101 121q68 87 101 120q18 18 31 48t17.5 48.5 t13.5 60.5q7 39 12.5 61t19.5 52t34 50q19 19 45 19q46 0 82.5 -10.5t60 -26t40 -40.5t24 -45t12 -50t5 -45t0.5 -39q0 -38 -9.5 -76t-19 -60t-27.5 -56q-3 -6 -10 -18t-11 -22t-8 -24h277q78 0 135 -57t57 -135z" />
<glyph unicode="&#xf165;" horiz-adv-x="1664" d="M256 960q0 -26 -19 -45t-45 -19q-27 0 -45.5 19t-18.5 45q0 27 18.5 45.5t45.5 18.5q26 0 45 -18.5t19 -45.5zM416 448v640q0 26 -19 45t-45 19h-288q-26 0 -45 -19t-19 -45v-640q0 -26 19 -45t45 -19h288q26 0 45 19t19 45zM1545 597q55 -61 55 -149q-1 -78 -57.5 -135 t-134.5 -57h-277q4 -14 8 -24t11 -22t10 -18q18 -37 27 -57t19 -58.5t10 -76.5q0 -24 -0.5 -39t-5 -45t-12 -50t-24 -45t-40 -40.5t-60 -26t-82.5 -10.5q-26 0 -45 19q-20 20 -34 50t-19.5 52t-12.5 61q-9 42 -13.5 60.5t-17.5 48.5t-31 48q-33 33 -101 120q-49 64 -101 121 t-76 59q-25 2 -43 20.5t-18 43.5v641q0 26 19 44.5t45 19.5q35 1 158 44q77 26 120.5 39.5t121.5 29t144 15.5h17h76h36q133 -2 197 -78q58 -69 49 -181q39 -37 54 -94q17 -61 0 -117q46 -61 43 -137q0 -32 -15 -76z" />
<glyph unicode="&#xf166;" d="M919 233v157q0 50 -29 50q-17 0 -33 -16v-224q16 -16 33 -16q29 0 29 49zM1103 355h66v34q0 51 -33 51t-33 -51v-34zM532 621v-70h-80v-423h-74v423h-78v70h232zM733 495v-367h-67v40q-39 -45 -76 -45q-33 0 -42 28q-6 16 -6 54v290h66v-270q0 -24 1 -26q1 -15 15 -15 q20 0 42 31v280h67zM985 384v-146q0 -52 -7 -73q-12 -42 -53 -42q-35 0 -68 41v-36h-67v493h67v-161q32 40 68 40q41 0 53 -42q7 -21 7 -74zM1236 255v-9q0 -29 -2 -43q-3 -22 -15 -40q-27 -40 -80 -40q-52 0 -81 38q-21 27 -21 86v129q0 59 20 86q29 38 80 38t78 -38 q21 -28 21 -86v-76h-133v-65q0 -51 34 -51q24 0 30 26q0 1 0.5 7t0.5 16.5v21.5h68zM785 1079v-156q0 -51 -32 -51t-32 51v156q0 52 32 52t32 -52zM1318 366q0 177 -19 260q-10 44 -43 73.5t-76 34.5q-136 15 -412 15q-275 0 -411 -15q-44 -5 -76.5 -34.5t-42.5 -73.5 q-20 -87 -20 -260q0 -176 20 -260q10 -43 42.5 -73t75.5 -35q137 -15 412 -15t412 15q43 5 75.5 35t42.5 73q20 84 20 260zM563 1017l90 296h-75l-51 -195l-53 195h-78l24 -69t23 -69q35 -103 46 -158v-201h74v201zM852 936v130q0 58 -21 87q-29 38 -78 38q-51 0 -78 -38 q-21 -29 -21 -87v-130q0 -58 21 -87q27 -38 78 -38q49 0 78 38q21 27 21 87zM1033 816h67v370h-67v-283q-22 -31 -42 -31q-15 0 -16 16q-1 2 -1 26v272h-67v-293q0 -37 6 -55q11 -27 43 -27q36 0 77 45v-40zM1536 1120v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960 q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf167;" d="M971 292v-211q0 -67 -39 -67q-23 0 -45 22v301q22 22 45 22q39 0 39 -67zM1309 291v-46h-90v46q0 68 45 68t45 -68zM343 509h107v94h-312v-94h105v-569h100v569zM631 -60h89v494h-89v-378q-30 -42 -57 -42q-18 0 -21 21q-1 3 -1 35v364h-89v-391q0 -49 8 -73 q12 -37 58 -37q48 0 102 61v-54zM1060 88v197q0 73 -9 99q-17 56 -71 56q-50 0 -93 -54v217h-89v-663h89v48q45 -55 93 -55q54 0 71 55q9 27 9 100zM1398 98v13h-91q0 -51 -2 -61q-7 -36 -40 -36q-46 0 -46 69v87h179v103q0 79 -27 116q-39 51 -106 51q-68 0 -107 -51 q-28 -37 -28 -116v-173q0 -79 29 -116q39 -51 108 -51q72 0 108 53q18 27 21 54q2 9 2 58zM790 1011v210q0 69 -43 69t-43 -69v-210q0 -70 43 -70t43 70zM1509 260q0 -234 -26 -350q-14 -59 -58 -99t-102 -46q-184 -21 -555 -21t-555 21q-58 6 -102.5 46t-57.5 99 q-26 112 -26 350q0 234 26 350q14 59 58 99t103 47q183 20 554 20t555 -20q58 -7 102.5 -47t57.5 -99q26 -112 26 -350zM511 1536h102l-121 -399v-271h-100v271q-14 74 -61 212q-37 103 -65 187h106l71 -263zM881 1203v-175q0 -81 -28 -118q-37 -51 -106 -51q-67 0 -105 51 q-28 38 -28 118v175q0 80 28 117q38 51 105 51q69 0 106 -51q28 -37 28 -117zM1216 1365v-499h-91v55q-53 -62 -103 -62q-46 0 -59 37q-8 24 -8 75v394h91v-367q0 -33 1 -35q3 -22 21 -22q27 0 57 43v381h91z" />
<glyph unicode="&#xf168;" horiz-adv-x="1408" d="M597 869q-10 -18 -257 -456q-27 -46 -65 -46h-239q-21 0 -31 17t0 36l253 448q1 0 0 1l-161 279q-12 22 -1 37q9 15 32 15h239q40 0 66 -45zM1403 1511q11 -16 0 -37l-528 -934v-1l336 -615q11 -20 1 -37q-10 -15 -32 -15h-239q-42 0 -66 45l-339 622q18 32 531 942 q25 45 64 45h241q22 0 31 -15z" />
<glyph unicode="&#xf169;" d="M685 771q0 1 -126 222q-21 34 -52 34h-184q-18 0 -26 -11q-7 -12 1 -29l125 -216v-1l-196 -346q-9 -14 0 -28q8 -13 24 -13h185q31 0 50 36zM1309 1268q-7 12 -24 12h-187q-30 0 -49 -35l-411 -729q1 -2 262 -481q20 -35 52 -35h184q18 0 25 12q8 13 -1 28l-260 476v1 l409 723q8 16 0 28zM1536 1120v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf16a;" horiz-adv-x="1792" d="M1280 640q0 37 -30 54l-512 320q-31 20 -65 2q-33 -18 -33 -56v-640q0 -38 33 -56q16 -8 31 -8q20 0 34 10l512 320q30 17 30 54zM1792 640q0 -96 -1 -150t-8.5 -136.5t-22.5 -147.5q-16 -73 -69 -123t-124 -58q-222 -25 -671 -25t-671 25q-71 8 -124.5 58t-69.5 123 q-14 65 -21.5 147.5t-8.5 136.5t-1 150t1 150t8.5 136.5t22.5 147.5q16 73 69 123t124 58q222 25 671 25t671 -25q71 -8 124.5 -58t69.5 -123q14 -65 21.5 -147.5t8.5 -136.5t1 -150z" />
<glyph unicode="&#xf16b;" horiz-adv-x="1792" d="M402 829l494 -305l-342 -285l-490 319zM1388 274v-108l-490 -293v-1l-1 1l-1 -1v1l-489 293v108l147 -96l342 284v2l1 -1l1 1v-2l343 -284zM554 1418l342 -285l-494 -304l-338 270zM1390 829l338 -271l-489 -319l-343 285zM1239 1418l489 -319l-338 -270l-494 304z" />
<glyph unicode="&#xf16c;" horiz-adv-x="1408" d="M928 135v-151l-707 -1v151zM1169 481v-701l-1 -35v-1h-1132l-35 1h-1v736h121v-618h928v618h120zM241 393l704 -65l-13 -150l-705 65zM309 709l683 -183l-39 -146l-683 183zM472 1058l609 -360l-77 -130l-609 360zM832 1389l398 -585l-124 -85l-399 584zM1285 1536 l121 -697l-149 -26l-121 697z" />
<glyph unicode="&#xf16d;" d="M1362 110v648h-135q20 -63 20 -131q0 -126 -64 -232.5t-174 -168.5t-240 -62q-197 0 -337 135.5t-140 327.5q0 68 20 131h-141v-648q0 -26 17.5 -43.5t43.5 -17.5h1069q25 0 43 17.5t18 43.5zM1078 643q0 124 -90.5 211.5t-218.5 87.5q-127 0 -217.5 -87.5t-90.5 -211.5 t90.5 -211.5t217.5 -87.5q128 0 218.5 87.5t90.5 211.5zM1362 1003v165q0 28 -20 48.5t-49 20.5h-174q-29 0 -49 -20.5t-20 -48.5v-165q0 -29 20 -49t49 -20h174q29 0 49 20t20 49zM1536 1211v-1142q0 -81 -58 -139t-139 -58h-1142q-81 0 -139 58t-58 139v1142q0 81 58 139 t139 58h1142q81 0 139 -58t58 -139z" />
<glyph unicode="&#xf16e;" d="M1248 1408q119 0 203.5 -84.5t84.5 -203.5v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960zM698 640q0 88 -62 150t-150 62t-150 -62t-62 -150t62 -150t150 -62t150 62t62 150zM1262 640q0 88 -62 150 t-150 62t-150 -62t-62 -150t62 -150t150 -62t150 62t62 150z" />
<glyph unicode="&#xf170;" d="M768 914l201 -306h-402zM1133 384h94l-459 691l-459 -691h94l104 160h522zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf171;" horiz-adv-x="1408" d="M815 677q8 -63 -50.5 -101t-111.5 -6q-39 17 -53.5 58t-0.5 82t52 58q36 18 72.5 12t64 -35.5t27.5 -67.5zM926 698q-14 107 -113 164t-197 13q-63 -28 -100.5 -88.5t-34.5 -129.5q4 -91 77.5 -155t165.5 -56q91 8 152 84t50 168zM1165 1240q-20 27 -56 44.5t-58 22 t-71 12.5q-291 47 -566 -2q-43 -7 -66 -12t-55 -22t-50 -43q30 -28 76 -45.5t73.5 -22t87.5 -11.5q228 -29 448 -1q63 8 89.5 12t72.5 21.5t75 46.5zM1222 205q-8 -26 -15.5 -76.5t-14 -84t-28.5 -70t-58 -56.5q-86 -48 -189.5 -71.5t-202 -22t-201.5 18.5q-46 8 -81.5 18 t-76.5 27t-73 43.5t-52 61.5q-25 96 -57 292l6 16l18 9q223 -148 506.5 -148t507.5 148q21 -6 24 -23t-5 -45t-8 -37zM1403 1166q-26 -167 -111 -655q-5 -30 -27 -56t-43.5 -40t-54.5 -31q-252 -126 -610 -88q-248 27 -394 139q-15 12 -25.5 26.5t-17 35t-9 34t-6 39.5 t-5.5 35q-9 50 -26.5 150t-28 161.5t-23.5 147.5t-22 158q3 26 17.5 48.5t31.5 37.5t45 30t46 22.5t48 18.5q125 46 313 64q379 37 676 -50q155 -46 215 -122q16 -20 16.5 -51t-5.5 -54z" />
<glyph unicode="&#xf172;" d="M848 666q0 43 -41 66t-77 1q-43 -20 -42.5 -72.5t43.5 -70.5q39 -23 81 4t36 72zM928 682q8 -66 -36 -121t-110 -61t-119 40t-56 113q-2 49 25.5 93t72.5 64q70 31 141.5 -10t81.5 -118zM1100 1073q-20 -21 -53.5 -34t-53 -16t-63.5 -8q-155 -20 -324 0q-44 6 -63 9.5 t-52.5 16t-54.5 32.5q13 19 36 31t40 15.5t47 8.5q198 35 408 1q33 -5 51 -8.5t43 -16t39 -31.5zM1142 327q0 7 5.5 26.5t3 32t-17.5 16.5q-161 -106 -365 -106t-366 106l-12 -6l-5 -12q26 -154 41 -210q47 -81 204 -108q249 -46 428 53q34 19 49 51.5t22.5 85.5t12.5 71z M1272 1020q9 53 -8 75q-43 55 -155 88q-216 63 -487 36q-132 -12 -226 -46q-38 -15 -59.5 -25t-47 -34t-29.5 -54q8 -68 19 -138t29 -171t24 -137q1 -5 5 -31t7 -36t12 -27t22 -28q105 -80 284 -100q259 -28 440 63q24 13 39.5 23t31 29t19.5 40q48 267 80 473zM1536 1120 v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf173;" horiz-adv-x="1024" d="M944 207l80 -237q-23 -35 -111 -66t-177 -32q-104 -2 -190.5 26t-142.5 74t-95 106t-55.5 120t-16.5 118v544h-168v215q72 26 129 69.5t91 90t58 102t34 99t15 88.5q1 5 4.5 8.5t7.5 3.5h244v-424h333v-252h-334v-518q0 -30 6.5 -56t22.5 -52.5t49.5 -41.5t81.5 -14 q78 2 134 29z" />
<glyph unicode="&#xf174;" d="M1136 75l-62 183q-44 -22 -103 -22q-36 -1 -62 10.5t-38.5 31.5t-17.5 40.5t-5 43.5v398h257v194h-256v326h-188q-8 0 -9 -10q-5 -44 -17.5 -87t-39 -95t-77 -95t-118.5 -68v-165h130v-418q0 -57 21.5 -115t65 -111t121 -85.5t176.5 -30.5q69 1 136.5 25t85.5 50z M1536 1120v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf175;" horiz-adv-x="768" d="M765 237q8 -19 -5 -35l-350 -384q-10 -10 -23 -10q-14 0 -24 10l-355 384q-13 16 -5 35q9 19 29 19h224v1248q0 14 9 23t23 9h192q14 0 23 -9t9 -23v-1248h224q21 0 29 -19z" />
<glyph unicode="&#xf176;" horiz-adv-x="768" d="M765 1043q-9 -19 -29 -19h-224v-1248q0 -14 -9 -23t-23 -9h-192q-14 0 -23 9t-9 23v1248h-224q-21 0 -29 19t5 35l350 384q10 10 23 10q14 0 24 -10l355 -384q13 -16 5 -35z" />
<glyph unicode="&#xf177;" horiz-adv-x="1792" d="M1792 736v-192q0 -14 -9 -23t-23 -9h-1248v-224q0 -21 -19 -29t-35 5l-384 350q-10 10 -10 23q0 14 10 24l384 354q16 14 35 6q19 -9 19 -29v-224h1248q14 0 23 -9t9 -23z" />
<glyph unicode="&#xf178;" horiz-adv-x="1792" d="M1728 643q0 -14 -10 -24l-384 -354q-16 -14 -35 -6q-19 9 -19 29v224h-1248q-14 0 -23 9t-9 23v192q0 14 9 23t23 9h1248v224q0 21 19 29t35 -5l384 -350q10 -10 10 -23z" />
<glyph unicode="&#xf179;" horiz-adv-x="1408" d="M1393 321q-39 -125 -123 -250q-129 -196 -257 -196q-49 0 -140 32q-86 32 -151 32q-61 0 -142 -33q-81 -34 -132 -34q-152 0 -301 259q-147 261 -147 503q0 228 113 374q112 144 284 144q72 0 177 -30q104 -30 138 -30q45 0 143 34q102 34 173 34q119 0 213 -65 q52 -36 104 -100q-79 -67 -114 -118q-65 -94 -65 -207q0 -124 69 -223t158 -126zM1017 1494q0 -61 -29 -136q-30 -75 -93 -138q-54 -54 -108 -72q-37 -11 -104 -17q3 149 78 257q74 107 250 148q1 -3 2.5 -11t2.5 -11q0 -4 0.5 -10t0.5 -10z" />
<glyph unicode="&#xf17a;" horiz-adv-x="1664" d="M682 530v-651l-682 94v557h682zM682 1273v-659h-682v565zM1664 530v-786l-907 125v661h907zM1664 1408v-794h-907v669z" />
<glyph unicode="&#xf17b;" horiz-adv-x="1408" d="M493 1053q16 0 27.5 11.5t11.5 27.5t-11.5 27.5t-27.5 11.5t-27 -11.5t-11 -27.5t11 -27.5t27 -11.5zM915 1053q16 0 27 11.5t11 27.5t-11 27.5t-27 11.5t-27.5 -11.5t-11.5 -27.5t11.5 -27.5t27.5 -11.5zM103 869q42 0 72 -30t30 -72v-430q0 -43 -29.5 -73t-72.5 -30 t-73 30t-30 73v430q0 42 30 72t73 30zM1163 850v-666q0 -46 -32 -78t-77 -32h-75v-227q0 -43 -30 -73t-73 -30t-73 30t-30 73v227h-138v-227q0 -43 -30 -73t-73 -30q-42 0 -72 30t-30 73l-1 227h-74q-46 0 -78 32t-32 78v666h918zM931 1255q107 -55 171 -153.5t64 -215.5 h-925q0 117 64 215.5t172 153.5l-71 131q-7 13 5 20q13 6 20 -6l72 -132q95 42 201 42t201 -42l72 132q7 12 20 6q12 -7 5 -20zM1408 767v-430q0 -43 -30 -73t-73 -30q-42 0 -72 30t-30 73v430q0 43 30 72.5t72 29.5q43 0 73 -29.5t30 -72.5z" />
<glyph unicode="&#xf17c;" d="M663 1125q-11 -1 -15.5 -10.5t-8.5 -9.5q-5 -1 -5 5q0 12 19 15h10zM750 1111q-4 -1 -11.5 6.5t-17.5 4.5q24 11 32 -2q3 -6 -3 -9zM399 684q-4 1 -6 -3t-4.5 -12.5t-5.5 -13.5t-10 -13q-7 -10 -1 -12q4 -1 12.5 7t12.5 18q1 3 2 7t2 6t1.5 4.5t0.5 4v3t-1 2.5t-3 2z M1254 325q0 18 -55 42q4 15 7.5 27.5t5 26t3 21.5t0.5 22.5t-1 19.5t-3.5 22t-4 20.5t-5 25t-5.5 26.5q-10 48 -47 103t-72 75q24 -20 57 -83q87 -162 54 -278q-11 -40 -50 -42q-31 -4 -38.5 18.5t-8 83.5t-11.5 107q-9 39 -19.5 69t-19.5 45.5t-15.5 24.5t-13 15t-7.5 7 q-14 62 -31 103t-29.5 56t-23.5 33t-15 40q-4 21 6 53.5t4.5 49.5t-44.5 25q-15 3 -44.5 18t-35.5 16q-8 1 -11 26t8 51t36 27q37 3 51 -30t4 -58q-11 -19 -2 -26.5t30 -0.5q13 4 13 36v37q-5 30 -13.5 50t-21 30.5t-23.5 15t-27 7.5q-107 -8 -89 -134q0 -15 -1 -15 q-9 9 -29.5 10.5t-33 -0.5t-15.5 5q1 57 -16 90t-45 34q-27 1 -41.5 -27.5t-16.5 -59.5q-1 -15 3.5 -37t13 -37.5t15.5 -13.5q10 3 16 14q4 9 -7 8q-7 0 -15.5 14.5t-9.5 33.5q-1 22 9 37t34 14q17 0 27 -21t9.5 -39t-1.5 -22q-22 -15 -31 -29q-8 -12 -27.5 -23.5 t-20.5 -12.5q-13 -14 -15.5 -27t7.5 -18q14 -8 25 -19.5t16 -19t18.5 -13t35.5 -6.5q47 -2 102 15q2 1 23 7t34.5 10.5t29.5 13t21 17.5q9 14 20 8q5 -3 6.5 -8.5t-3 -12t-16.5 -9.5q-20 -6 -56.5 -21.5t-45.5 -19.5q-44 -19 -70 -23q-25 -5 -79 2q-10 2 -9 -2t17 -19 q25 -23 67 -22q17 1 36 7t36 14t33.5 17.5t30 17t24.5 12t17.5 2.5t8.5 -11q0 -2 -1 -4.5t-4 -5t-6 -4.5t-8.5 -5t-9 -4.5t-10 -5t-9.5 -4.5q-28 -14 -67.5 -44t-66.5 -43t-49 -1q-21 11 -63 73q-22 31 -25 22q-1 -3 -1 -10q0 -25 -15 -56.5t-29.5 -55.5t-21 -58t11.5 -63 q-23 -6 -62.5 -90t-47.5 -141q-2 -18 -1.5 -69t-5.5 -59q-8 -24 -29 -3q-32 31 -36 94q-2 28 4 56q4 19 -1 18l-4 -5q-36 -65 10 -166q5 -12 25 -28t24 -20q20 -23 104 -90.5t93 -76.5q16 -15 17.5 -38t-14 -43t-45.5 -23q8 -15 29 -44.5t28 -54t7 -70.5q46 24 7 92 q-4 8 -10.5 16t-9.5 12t-2 6q3 5 13 9.5t20 -2.5q46 -52 166 -36q133 15 177 87q23 38 34 30q12 -6 10 -52q-1 -25 -23 -92q-9 -23 -6 -37.5t24 -15.5q3 19 14.5 77t13.5 90q2 21 -6.5 73.5t-7.5 97t23 70.5q15 18 51 18q1 37 34.5 53t72.5 10.5t60 -22.5zM626 1152 q3 17 -2.5 30t-11.5 15q-9 2 -9 -7q2 -5 5 -6q10 0 7 -15q-3 -20 8 -20q3 0 3 3zM1045 955q-2 8 -6.5 11.5t-13 5t-14.5 5.5q-5 3 -9.5 8t-7 8t-5.5 6.5t-4 4t-4 -1.5q-14 -16 7 -43.5t39 -31.5q9 -1 14.5 8t3.5 20zM867 1168q0 11 -5 19.5t-11 12.5t-9 3q-14 -1 -7 -7l4 -2 q14 -4 18 -31q0 -3 8 2zM921 1401q0 2 -2.5 5t-9 7t-9.5 6q-15 15 -24 15q-9 -1 -11.5 -7.5t-1 -13t-0.5 -12.5q-1 -4 -6 -10.5t-6 -9t3 -8.5q4 -3 8 0t11 9t15 9q1 1 9 1t15 2t9 7zM1486 60q20 -12 31 -24.5t12 -24t-2.5 -22.5t-15.5 -22t-23.5 -19.5t-30 -18.5 t-31.5 -16.5t-32 -15.5t-27 -13q-38 -19 -85.5 -56t-75.5 -64q-17 -16 -68 -19.5t-89 14.5q-18 9 -29.5 23.5t-16.5 25.5t-22 19.5t-47 9.5q-44 1 -130 1q-19 0 -57 -1.5t-58 -2.5q-44 -1 -79.5 -15t-53.5 -30t-43.5 -28.5t-53.5 -11.5q-29 1 -111 31t-146 43q-19 4 -51 9.5 t-50 9t-39.5 9.5t-33.5 14.5t-17 19.5q-10 23 7 66.5t18 54.5q1 16 -4 40t-10 42.5t-4.5 36.5t10.5 27q14 12 57 14t60 12q30 18 42 35t12 51q21 -73 -32 -106q-32 -20 -83 -15q-34 3 -43 -10q-13 -15 5 -57q2 -6 8 -18t8.5 -18t4.5 -17t1 -22q0 -15 -17 -49t-14 -48 q3 -17 37 -26q20 -6 84.5 -18.5t99.5 -20.5q24 -6 74 -22t82.5 -23t55.5 -4q43 6 64.5 28t23 48t-7.5 58.5t-19 52t-20 36.5q-121 190 -169 242q-68 74 -113 40q-11 -9 -15 15q-3 16 -2 38q1 29 10 52t24 47t22 42q8 21 26.5 72t29.5 78t30 61t39 54q110 143 124 195 q-12 112 -16 310q-2 90 24 151.5t106 104.5q39 21 104 21q53 1 106 -13.5t89 -41.5q57 -42 91.5 -121.5t29.5 -147.5q-5 -95 30 -214q34 -113 133 -218q55 -59 99.5 -163t59.5 -191q8 -49 5 -84.5t-12 -55.5t-20 -22q-10 -2 -23.5 -19t-27 -35.5t-40.5 -33.5t-61 -14 q-18 1 -31.5 5t-22.5 13.5t-13.5 15.5t-11.5 20.5t-9 19.5q-22 37 -41 30t-28 -49t7 -97q20 -70 1 -195q-10 -65 18 -100.5t73 -33t85 35.5q59 49 89.5 66.5t103.5 42.5q53 18 77 36.5t18.5 34.5t-25 28.5t-51.5 23.5q-33 11 -49.5 48t-15 72.5t15.5 47.5q1 -31 8 -56.5 t14.5 -40.5t20.5 -28.5t21 -19t21.5 -13t16.5 -9.5z" />
<glyph unicode="&#xf17d;" d="M1024 36q-42 241 -140 498h-2l-2 -1q-16 -6 -43 -16.5t-101 -49t-137 -82t-131 -114.5t-103 -148l-15 11q184 -150 418 -150q132 0 256 52zM839 643q-21 49 -53 111q-311 -93 -673 -93q-1 -7 -1 -21q0 -124 44 -236.5t124 -201.5q50 89 123.5 166.5t142.5 124.5t130.5 81 t99.5 48l37 13q4 1 13 3.5t13 4.5zM732 855q-120 213 -244 378q-138 -65 -234 -186t-128 -272q302 0 606 80zM1416 536q-210 60 -409 29q87 -239 128 -469q111 75 185 189.5t96 250.5zM611 1277q-1 0 -2 -1q1 1 2 1zM1201 1132q-185 164 -433 164q-76 0 -155 -19 q131 -170 246 -382q69 26 130 60.5t96.5 61.5t65.5 57t37.5 40.5zM1424 647q-3 232 -149 410l-1 -1q-9 -12 -19 -24.5t-43.5 -44.5t-71 -60.5t-100 -65t-131.5 -64.5q25 -53 44 -95q2 -6 6.5 -17.5t7.5 -16.5q36 5 74.5 7t73.5 2t69 -1.5t64 -4t56.5 -5.5t48 -6.5t36.5 -6 t25 -4.5zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf17e;" d="M1173 473q0 50 -19.5 91.5t-48.5 68.5t-73 49t-82.5 34t-87.5 23l-104 24q-30 7 -44 10.5t-35 11.5t-30 16t-16.5 21t-7.5 30q0 77 144 77q43 0 77 -12t54 -28.5t38 -33.5t40 -29t48 -12q47 0 75.5 32t28.5 77q0 55 -56 99.5t-142 67.5t-182 23q-68 0 -132 -15.5 t-119.5 -47t-89 -87t-33.5 -128.5q0 -61 19 -106.5t56 -75.5t80 -48.5t103 -32.5l146 -36q90 -22 112 -36q32 -20 32 -60q0 -39 -40 -64.5t-105 -25.5q-51 0 -91.5 16t-65 38.5t-45.5 45t-46 38.5t-54 16q-50 0 -75.5 -30t-25.5 -75q0 -92 122 -157.5t291 -65.5 q73 0 140 18.5t122.5 53.5t88.5 93.5t33 131.5zM1536 256q0 -159 -112.5 -271.5t-271.5 -112.5q-130 0 -234 80q-77 -16 -150 -16q-143 0 -273.5 55.5t-225 150t-150 225t-55.5 273.5q0 73 16 150q-80 104 -80 234q0 159 112.5 271.5t271.5 112.5q130 0 234 -80 q77 16 150 16q143 0 273.5 -55.5t225 -150t150 -225t55.5 -273.5q0 -73 -16 -150q80 -104 80 -234z" />
<glyph unicode="&#xf180;" horiz-adv-x="1280" d="M1000 1102l37 194q5 23 -9 40t-35 17h-712q-23 0 -38.5 -17t-15.5 -37v-1101q0 -7 6 -1l291 352q23 26 38 33.5t48 7.5h239q22 0 37 14.5t18 29.5q24 130 37 191q4 21 -11.5 40t-36.5 19h-294q-29 0 -48 19t-19 48v42q0 29 19 47.5t48 18.5h346q18 0 35 13.5t20 29.5z M1227 1324q-15 -73 -53.5 -266.5t-69.5 -350t-35 -173.5q-6 -22 -9 -32.5t-14 -32.5t-24.5 -33t-38.5 -21t-58 -10h-271q-13 0 -22 -10q-8 -9 -426 -494q-22 -25 -58.5 -28.5t-48.5 5.5q-55 22 -55 98v1410q0 55 38 102.5t120 47.5h888q95 0 127 -53t10 -159zM1227 1324 l-158 -790q4 17 35 173.5t69.5 350t53.5 266.5z" />
<glyph unicode="&#xf181;" d="M704 192v1024q0 14 -9 23t-23 9h-480q-14 0 -23 -9t-9 -23v-1024q0 -14 9 -23t23 -9h480q14 0 23 9t9 23zM1376 576v640q0 14 -9 23t-23 9h-480q-14 0 -23 -9t-9 -23v-640q0 -14 9 -23t23 -9h480q14 0 23 9t9 23zM1536 1344v-1408q0 -26 -19 -45t-45 -19h-1408 q-26 0 -45 19t-19 45v1408q0 26 19 45t45 19h1408q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf182;" horiz-adv-x="1280" d="M1280 480q0 -40 -28 -68t-68 -28q-51 0 -80 43l-227 341h-45v-132l247 -411q9 -15 9 -33q0 -26 -19 -45t-45 -19h-192v-272q0 -46 -33 -79t-79 -33h-160q-46 0 -79 33t-33 79v272h-192q-26 0 -45 19t-19 45q0 18 9 33l247 411v132h-45l-227 -341q-29 -43 -80 -43 q-40 0 -68 28t-28 68q0 29 16 53l256 384q73 107 176 107h384q103 0 176 -107l256 -384q16 -24 16 -53zM864 1280q0 -93 -65.5 -158.5t-158.5 -65.5t-158.5 65.5t-65.5 158.5t65.5 158.5t158.5 65.5t158.5 -65.5t65.5 -158.5z" />
<glyph unicode="&#xf183;" horiz-adv-x="1024" d="M1024 832v-416q0 -40 -28 -68t-68 -28t-68 28t-28 68v352h-64v-912q0 -46 -33 -79t-79 -33t-79 33t-33 79v464h-64v-464q0 -46 -33 -79t-79 -33t-79 33t-33 79v912h-64v-352q0 -40 -28 -68t-68 -28t-68 28t-28 68v416q0 80 56 136t136 56h640q80 0 136 -56t56 -136z M736 1280q0 -93 -65.5 -158.5t-158.5 -65.5t-158.5 65.5t-65.5 158.5t65.5 158.5t158.5 65.5t158.5 -65.5t65.5 -158.5z" />
<glyph unicode="&#xf184;" d="M773 234l350 473q16 22 24.5 59t-6 85t-61.5 79q-40 26 -83 25.5t-73.5 -17.5t-54.5 -45q-36 -40 -96 -40q-59 0 -95 40q-24 28 -54.5 45t-73.5 17.5t-84 -25.5q-46 -31 -60.5 -79t-6 -85t24.5 -59zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103 t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf185;" horiz-adv-x="1792" d="M1472 640q0 117 -45.5 223.5t-123 184t-184 123t-223.5 45.5t-223.5 -45.5t-184 -123t-123 -184t-45.5 -223.5t45.5 -223.5t123 -184t184 -123t223.5 -45.5t223.5 45.5t184 123t123 184t45.5 223.5zM1748 363q-4 -15 -20 -20l-292 -96v-306q0 -16 -13 -26q-15 -10 -29 -4 l-292 94l-180 -248q-10 -13 -26 -13t-26 13l-180 248l-292 -94q-14 -6 -29 4q-13 10 -13 26v306l-292 96q-16 5 -20 20q-5 17 4 29l180 248l-180 248q-9 13 -4 29q4 15 20 20l292 96v306q0 16 13 26q15 10 29 4l292 -94l180 248q9 12 26 12t26 -12l180 -248l292 94 q14 6 29 -4q13 -10 13 -26v-306l292 -96q16 -5 20 -20q5 -16 -4 -29l-180 -248l180 -248q9 -12 4 -29z" />
<glyph unicode="&#xf186;" d="M1262 233q-54 -9 -110 -9q-182 0 -337 90t-245 245t-90 337q0 192 104 357q-201 -60 -328.5 -229t-127.5 -384q0 -130 51 -248.5t136.5 -204t204 -136.5t248.5 -51q144 0 273.5 61.5t220.5 171.5zM1465 318q-94 -203 -283.5 -324.5t-413.5 -121.5q-156 0 -298 61 t-245 164t-164 245t-61 298q0 153 57.5 292.5t156 241.5t235.5 164.5t290 68.5q44 2 61 -39q18 -41 -15 -72q-86 -78 -131.5 -181.5t-45.5 -218.5q0 -148 73 -273t198 -198t273 -73q118 0 228 51q41 18 72 -13q14 -14 17.5 -34t-4.5 -38z" />
<glyph unicode="&#xf187;" horiz-adv-x="1792" d="M1088 704q0 26 -19 45t-45 19h-256q-26 0 -45 -19t-19 -45t19 -45t45 -19h256q26 0 45 19t19 45zM1664 896v-960q0 -26 -19 -45t-45 -19h-1408q-26 0 -45 19t-19 45v960q0 26 19 45t45 19h1408q26 0 45 -19t19 -45zM1728 1344v-256q0 -26 -19 -45t-45 -19h-1536 q-26 0 -45 19t-19 45v256q0 26 19 45t45 19h1536q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf188;" horiz-adv-x="1664" d="M1632 576q0 -26 -19 -45t-45 -19h-224q0 -171 -67 -290l208 -209q19 -19 19 -45t-19 -45q-18 -19 -45 -19t-45 19l-198 197q-5 -5 -15 -13t-42 -28.5t-65 -36.5t-82 -29t-97 -13v896h-128v-896q-51 0 -101.5 13.5t-87 33t-66 39t-43.5 32.5l-15 14l-183 -207 q-20 -21 -48 -21q-24 0 -43 16q-19 18 -20.5 44.5t15.5 46.5l202 227q-58 114 -58 274h-224q-26 0 -45 19t-19 45t19 45t45 19h224v294l-173 173q-19 19 -19 45t19 45t45 19t45 -19l173 -173h844l173 173q19 19 45 19t45 -19t19 -45t-19 -45l-173 -173v-294h224q26 0 45 -19 t19 -45zM1152 1152h-640q0 133 93.5 226.5t226.5 93.5t226.5 -93.5t93.5 -226.5z" />
<glyph unicode="&#xf189;" horiz-adv-x="1920" d="M1917 1016q23 -64 -150 -294q-24 -32 -65 -85q-78 -100 -90 -131q-17 -41 14 -81q17 -21 81 -82h1l1 -1l1 -1l2 -2q141 -131 191 -221q3 -5 6.5 -12.5t7 -26.5t-0.5 -34t-25 -27.5t-59 -12.5l-256 -4q-24 -5 -56 5t-52 22l-20 12q-30 21 -70 64t-68.5 77.5t-61 58 t-56.5 15.5q-3 -1 -8 -3.5t-17 -14.5t-21.5 -29.5t-17 -52t-6.5 -77.5q0 -15 -3.5 -27.5t-7.5 -18.5l-4 -5q-18 -19 -53 -22h-115q-71 -4 -146 16.5t-131.5 53t-103 66t-70.5 57.5l-25 24q-10 10 -27.5 30t-71.5 91t-106 151t-122.5 211t-130.5 272q-6 16 -6 27t3 16l4 6 q15 19 57 19l274 2q12 -2 23 -6.5t16 -8.5l5 -3q16 -11 24 -32q20 -50 46 -103.5t41 -81.5l16 -29q29 -60 56 -104t48.5 -68.5t41.5 -38.5t34 -14t27 5q2 1 5 5t12 22t13.5 47t9.5 81t0 125q-2 40 -9 73t-14 46l-6 12q-25 34 -85 43q-13 2 5 24q17 19 38 30q53 26 239 24 q82 -1 135 -13q20 -5 33.5 -13.5t20.5 -24t10.5 -32t3.5 -45.5t-1 -55t-2.5 -70.5t-1.5 -82.5q0 -11 -1 -42t-0.5 -48t3.5 -40.5t11.5 -39t22.5 -24.5q8 -2 17 -4t26 11t38 34.5t52 67t68 107.5q60 104 107 225q4 10 10 17.5t11 10.5l4 3l5 2.5t13 3t20 0.5l288 2 q39 5 64 -2.5t31 -16.5z" />
<glyph unicode="&#xf18a;" horiz-adv-x="1792" d="M675 252q21 34 11 69t-45 50q-34 14 -73 1t-60 -46q-22 -34 -13 -68.5t43 -50.5t74.5 -2.5t62.5 47.5zM769 373q8 13 3.5 26.5t-17.5 18.5q-14 5 -28.5 -0.5t-21.5 -18.5q-17 -31 13 -45q14 -5 29 0.5t22 18.5zM943 266q-45 -102 -158 -150t-224 -12 q-107 34 -147.5 126.5t6.5 187.5q47 93 151.5 139t210.5 19q111 -29 158.5 -119.5t2.5 -190.5zM1255 426q-9 96 -89 170t-208.5 109t-274.5 21q-223 -23 -369.5 -141.5t-132.5 -264.5q9 -96 89 -170t208.5 -109t274.5 -21q223 23 369.5 141.5t132.5 264.5zM1563 422 q0 -68 -37 -139.5t-109 -137t-168.5 -117.5t-226 -83t-270.5 -31t-275 33.5t-240.5 93t-171.5 151t-65 199.5q0 115 69.5 245t197.5 258q169 169 341.5 236t246.5 -7q65 -64 20 -209q-4 -14 -1 -20t10 -7t14.5 0.5t13.5 3.5l6 2q139 59 246 59t153 -61q45 -63 0 -178 q-2 -13 -4.5 -20t4.5 -12.5t12 -7.5t17 -6q57 -18 103 -47t80 -81.5t34 -116.5zM1489 1046q42 -47 54.5 -108.5t-6.5 -117.5q-8 -23 -29.5 -34t-44.5 -4q-23 8 -34 29.5t-4 44.5q20 63 -24 111t-107 35q-24 -5 -45 8t-25 37q-5 24 8 44.5t37 25.5q60 13 119 -5.5t101 -65.5z M1670 1209q87 -96 112.5 -222.5t-13.5 -241.5q-9 -27 -34 -40t-52 -4t-40 34t-5 52q28 82 10 172t-80 158q-62 69 -148 95.5t-173 8.5q-28 -6 -52 9.5t-30 43.5t9.5 51.5t43.5 29.5q123 26 244 -11.5t208 -134.5z" />
<glyph unicode="&#xf18b;" d="M1133 -34q-171 -94 -368 -94q-196 0 -367 94q138 87 235.5 211t131.5 268q35 -144 132.5 -268t235.5 -211zM638 1394v-485q0 -252 -126.5 -459.5t-330.5 -306.5q-181 215 -181 495q0 187 83.5 349.5t229.5 269.5t325 137zM1536 638q0 -280 -181 -495 q-204 99 -330.5 306.5t-126.5 459.5v485q179 -30 325 -137t229.5 -269.5t83.5 -349.5z" />
<glyph unicode="&#xf18c;" horiz-adv-x="1408" d="M1402 433q-32 -80 -76 -138t-91 -88.5t-99 -46.5t-101.5 -14.5t-96.5 8.5t-86.5 22t-69.5 27.5t-46 22.5l-17 10q-113 -228 -289.5 -359.5t-384.5 -132.5q-19 0 -32 13t-13 32t13 31.5t32 12.5q173 1 322.5 107.5t251.5 294.5q-36 -14 -72 -23t-83 -13t-91 2.5t-93 28.5 t-92 59t-84.5 100t-74.5 146q114 47 214 57t167.5 -7.5t124.5 -56.5t88.5 -77t56.5 -82q53 131 79 291q-7 -1 -18 -2.5t-46.5 -2.5t-69.5 0.5t-81.5 10t-88.5 23t-84 42.5t-75 65t-54.5 94.5t-28.5 127.5q70 28 133.5 36.5t112.5 -1t92 -30t73.5 -50t56 -61t42 -63t27.5 -56 t16 -39.5l4 -16q12 122 12 195q-8 6 -21.5 16t-49 44.5t-63.5 71.5t-54 93t-33 112.5t12 127t70 138.5q73 -25 127.5 -61.5t84.5 -76.5t48 -85t20.5 -89t-0.5 -85.5t-13 -76.5t-19 -62t-17 -42l-7 -15q1 -5 1 -50.5t-1 -71.5q3 7 10 18.5t30.5 43t50.5 58t71 55.5t91.5 44.5 t112 14.5t132.5 -24q-2 -78 -21.5 -141.5t-50 -104.5t-69.5 -71.5t-81.5 -45.5t-84.5 -24t-80 -9.5t-67.5 1t-46.5 4.5l-17 3q-23 -147 -73 -283q6 7 18 18.5t49.5 41t77.5 52.5t99.5 42t117.5 20t129 -23.5t137 -77.5z" />
<glyph unicode="&#xf18d;" horiz-adv-x="1280" d="M1259 283v-66q0 -85 -57.5 -144.5t-138.5 -59.5h-57l-260 -269v269h-529q-81 0 -138.5 59.5t-57.5 144.5v66h1238zM1259 609v-255h-1238v255h1238zM1259 937v-255h-1238v255h1238zM1259 1077v-67h-1238v67q0 84 57.5 143.5t138.5 59.5h846q81 0 138.5 -59.5t57.5 -143.5z " />
<glyph unicode="&#xf18e;" d="M1152 640q0 -14 -9 -23l-320 -320q-9 -9 -23 -9q-13 0 -22.5 9.5t-9.5 22.5v192h-352q-13 0 -22.5 9.5t-9.5 22.5v192q0 13 9.5 22.5t22.5 9.5h352v192q0 14 9 23t23 9q12 0 24 -10l319 -319q9 -9 9 -23zM1312 640q0 148 -73 273t-198 198t-273 73t-273 -73t-198 -198 t-73 -273t73 -273t198 -198t273 -73t273 73t198 198t73 273zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf190;" d="M1152 736v-192q0 -13 -9.5 -22.5t-22.5 -9.5h-352v-192q0 -14 -9 -23t-23 -9q-12 0 -24 10l-319 319q-9 9 -9 23t9 23l320 320q9 9 23 9q13 0 22.5 -9.5t9.5 -22.5v-192h352q13 0 22.5 -9.5t9.5 -22.5zM1312 640q0 148 -73 273t-198 198t-273 73t-273 -73t-198 -198 t-73 -273t73 -273t198 -198t273 -73t273 73t198 198t73 273zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf191;" d="M1024 960v-640q0 -26 -19 -45t-45 -19q-20 0 -37 12l-448 320q-27 19 -27 52t27 52l448 320q17 12 37 12q26 0 45 -19t19 -45zM1280 160v960q0 13 -9.5 22.5t-22.5 9.5h-960q-13 0 -22.5 -9.5t-9.5 -22.5v-960q0 -13 9.5 -22.5t22.5 -9.5h960q13 0 22.5 9.5t9.5 22.5z M1536 1120v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf192;" d="M1024 640q0 -106 -75 -181t-181 -75t-181 75t-75 181t75 181t181 75t181 -75t75 -181zM768 1184q-148 0 -273 -73t-198 -198t-73 -273t73 -273t198 -198t273 -73t273 73t198 198t73 273t-73 273t-198 198t-273 73zM1536 640q0 -209 -103 -385.5t-279.5 -279.5 t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf193;" horiz-adv-x="1664" d="M1023 349l102 -204q-58 -179 -210 -290t-339 -111q-156 0 -288.5 77.5t-210 210t-77.5 288.5q0 181 104.5 330t274.5 211l17 -131q-122 -54 -195 -165.5t-73 -244.5q0 -185 131.5 -316.5t316.5 -131.5q126 0 232.5 65t165 175.5t49.5 236.5zM1571 249l58 -114l-256 -128 q-13 -7 -29 -7q-40 0 -57 35l-239 477h-472q-24 0 -42.5 16.5t-21.5 40.5l-96 779q-2 16 6 42q14 51 57 82.5t97 31.5q66 0 113 -47t47 -113q0 -69 -52 -117.5t-120 -41.5l37 -289h423v-128h-407l16 -128h455q40 0 57 -35l228 -455z" />
<glyph unicode="&#xf194;" d="M1254 899q16 85 -21 132q-52 65 -187 45q-17 -3 -41 -12.5t-57.5 -30.5t-64.5 -48.5t-59.5 -70t-44.5 -91.5q80 7 113.5 -16t26.5 -99q-5 -52 -52 -143q-43 -78 -71 -99q-44 -32 -87 14q-23 24 -37.5 64.5t-19 73t-10 84t-8.5 71.5q-23 129 -34 164q-12 37 -35.5 69 t-50.5 40q-57 16 -127 -25q-54 -32 -136.5 -106t-122.5 -102v-7q16 -8 25.5 -26t21.5 -20q21 -3 54.5 8.5t58 10.5t41.5 -30q11 -18 18.5 -38.5t15 -48t12.5 -40.5q17 -46 53 -187q36 -146 57 -197q42 -99 103 -125q43 -12 85 -1.5t76 31.5q131 77 250 237 q104 139 172.5 292.5t82.5 226.5zM1536 1120v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf195;" horiz-adv-x="1152" d="M1152 704q0 -191 -94.5 -353t-256.5 -256.5t-353 -94.5h-160q-14 0 -23 9t-9 23v611l-215 -66q-3 -1 -9 -1q-10 0 -19 6q-13 10 -13 26v128q0 23 23 31l233 71v93l-215 -66q-3 -1 -9 -1q-10 0 -19 6q-13 10 -13 26v128q0 23 23 31l233 71v250q0 14 9 23t23 9h160 q14 0 23 -9t9 -23v-181l375 116q15 5 28 -5t13 -26v-128q0 -23 -23 -31l-393 -121v-93l375 116q15 5 28 -5t13 -26v-128q0 -23 -23 -31l-393 -121v-487q188 13 318 151t130 328q0 14 9 23t23 9h160q14 0 23 -9t9 -23z" />
<glyph unicode="&#xf196;" horiz-adv-x="1408" d="M1152 736v-64q0 -14 -9 -23t-23 -9h-352v-352q0 -14 -9 -23t-23 -9h-64q-14 0 -23 9t-9 23v352h-352q-14 0 -23 9t-9 23v64q0 14 9 23t23 9h352v352q0 14 9 23t23 9h64q14 0 23 -9t9 -23v-352h352q14 0 23 -9t9 -23zM1280 288v832q0 66 -47 113t-113 47h-832 q-66 0 -113 -47t-47 -113v-832q0 -66 47 -113t113 -47h832q66 0 113 47t47 113zM1408 1120v-832q0 -119 -84.5 -203.5t-203.5 -84.5h-832q-119 0 -203.5 84.5t-84.5 203.5v832q0 119 84.5 203.5t203.5 84.5h832q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf197;" horiz-adv-x="2176" d="M620 416q-110 -64 -268 -64h-128v64h-64q-13 0 -22.5 23.5t-9.5 56.5q0 24 7 49q-58 2 -96.5 10.5t-38.5 20.5t38.5 20.5t96.5 10.5q-7 25 -7 49q0 33 9.5 56.5t22.5 23.5h64v64h128q158 0 268 -64h1113q42 -7 106.5 -18t80.5 -14q89 -15 150 -40.5t83.5 -47.5t22.5 -40 t-22.5 -40t-83.5 -47.5t-150 -40.5q-16 -3 -80.5 -14t-106.5 -18h-1113zM1739 668q53 -36 53 -92t-53 -92l81 -30q68 48 68 122t-68 122zM625 400h1015q-217 -38 -456 -80q-57 0 -113 -24t-83 -48l-28 -24l-288 -288q-26 -26 -70.5 -45t-89.5 -19h-96l-93 464h29 q157 0 273 64zM352 816h-29l93 464h96q46 0 90 -19t70 -45l288 -288q4 -4 11 -10.5t30.5 -23t48.5 -29t61.5 -23t72.5 -10.5l456 -80h-1015q-116 64 -273 64z" />
<glyph unicode="&#xf198;" horiz-adv-x="1664" d="M1519 760q62 0 103.5 -40.5t41.5 -101.5q0 -97 -93 -130l-172 -59l56 -167q7 -21 7 -47q0 -59 -42 -102t-101 -43q-47 0 -85.5 27t-53.5 72l-55 165l-310 -106l55 -164q8 -24 8 -47q0 -59 -42 -102t-102 -43q-47 0 -85 27t-53 72l-55 163l-153 -53q-29 -9 -50 -9 q-61 0 -101.5 40t-40.5 101q0 47 27.5 85t71.5 53l156 53l-105 313l-156 -54q-26 -8 -48 -8q-60 0 -101 40.5t-41 100.5q0 47 27.5 85t71.5 53l157 53l-53 159q-8 24 -8 47q0 60 42 102.5t102 42.5q47 0 85 -27t53 -72l54 -160l310 105l-54 160q-8 24 -8 47q0 59 42.5 102 t101.5 43q47 0 85.5 -27.5t53.5 -71.5l53 -161l162 55q21 6 43 6q60 0 102.5 -39.5t42.5 -98.5q0 -45 -30 -81.5t-74 -51.5l-157 -54l105 -316l164 56q24 8 46 8zM725 498l310 105l-105 315l-310 -107z" />
<glyph unicode="&#xf199;" d="M1248 1408q119 0 203.5 -84.5t84.5 -203.5v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960zM1280 352v436q-31 -35 -64 -55q-34 -22 -132.5 -85t-151.5 -99q-98 -69 -164 -69v0v0q-66 0 -164 69 q-46 32 -141.5 92.5t-142.5 92.5q-12 8 -33 27t-31 27v-436q0 -40 28 -68t68 -28h832q40 0 68 28t28 68zM1280 925q0 41 -27.5 70t-68.5 29h-832q-40 0 -68 -28t-28 -68q0 -37 30.5 -76.5t67.5 -64.5q47 -32 137.5 -89t129.5 -83q3 -2 17 -11.5t21 -14t21 -13t23.5 -13 t21.5 -9.5t22.5 -7.5t20.5 -2.5t20.5 2.5t22.5 7.5t21.5 9.5t23.5 13t21 13t21 14t17 11.5l267 174q35 23 66.5 62.5t31.5 73.5z" />
<glyph unicode="&#xf19a;" horiz-adv-x="1792" d="M127 640q0 163 67 313l367 -1005q-196 95 -315 281t-119 411zM1415 679q0 -19 -2.5 -38.5t-10 -49.5t-11.5 -44t-17.5 -59t-17.5 -58l-76 -256l-278 826q46 3 88 8q19 2 26 18.5t-2.5 31t-28.5 13.5l-205 -10q-75 1 -202 10q-12 1 -20.5 -5t-11.5 -15t-1.5 -18.5t9 -16.5 t19.5 -8l80 -8l120 -328l-168 -504l-280 832q46 3 88 8q19 2 26 18.5t-2.5 31t-28.5 13.5l-205 -10q-7 0 -23 0.5t-26 0.5q105 160 274.5 253.5t367.5 93.5q147 0 280.5 -53t238.5 -149h-10q-55 0 -92 -40.5t-37 -95.5q0 -12 2 -24t4 -21.5t8 -23t9 -21t12 -22.5t12.5 -21 t14.5 -24t14 -23q63 -107 63 -212zM909 573l237 -647q1 -6 5 -11q-126 -44 -255 -44q-112 0 -217 32zM1570 1009q95 -174 95 -369q0 -209 -104 -385.5t-279 -278.5l235 678q59 169 59 276q0 42 -6 79zM896 1536q182 0 348 -71t286 -191t191 -286t71 -348t-71 -348t-191 -286 t-286 -191t-348 -71t-348 71t-286 191t-191 286t-71 348t71 348t191 286t286 191t348 71zM896 -215q173 0 331.5 68t273 182.5t182.5 273t68 331.5t-68 331.5t-182.5 273t-273 182.5t-331.5 68t-331.5 -68t-273 -182.5t-182.5 -273t-68 -331.5t68 -331.5t182.5 -273 t273 -182.5t331.5 -68z" />
<glyph unicode="&#xf19b;" horiz-adv-x="1792" d="M1086 1536v-1536l-272 -128q-228 20 -414 102t-293 208.5t-107 272.5q0 140 100.5 263.5t275 205.5t391.5 108v-172q-217 -38 -356.5 -150t-139.5 -255q0 -152 154.5 -267t388.5 -145v1360zM1755 954l37 -390l-525 114l147 83q-119 70 -280 99v172q277 -33 481 -157z" />
<glyph unicode="&#xf19c;" horiz-adv-x="2048" d="M960 1536l960 -384v-128h-128q0 -26 -20.5 -45t-48.5 -19h-1526q-28 0 -48.5 19t-20.5 45h-128v128zM256 896h256v-768h128v768h256v-768h128v768h256v-768h128v768h256v-768h59q28 0 48.5 -19t20.5 -45v-64h-1664v64q0 26 20.5 45t48.5 19h59v768zM1851 -64 q28 0 48.5 -19t20.5 -45v-128h-1920v128q0 26 20.5 45t48.5 19h1782z" />
<glyph unicode="&#xf19d;" horiz-adv-x="2304" d="M1774 700l18 -316q4 -69 -82 -128t-235 -93.5t-323 -34.5t-323 34.5t-235 93.5t-82 128l18 316l574 -181q22 -7 48 -7t48 7zM2304 1024q0 -23 -22 -31l-1120 -352q-4 -1 -10 -1t-10 1l-652 206q-43 -34 -71 -111.5t-34 -178.5q63 -36 63 -109q0 -69 -58 -107l58 -433 q2 -14 -8 -25q-9 -11 -24 -11h-192q-15 0 -24 11q-10 11 -8 25l58 433q-58 38 -58 107q0 73 65 111q11 207 98 330l-333 104q-22 8 -22 31t22 31l1120 352q4 1 10 1t10 -1l1120 -352q22 -8 22 -31z" />
<glyph unicode="&#xf19e;" d="M859 579l13 -707q-62 11 -105 11q-41 0 -105 -11l13 707q-40 69 -168.5 295.5t-216.5 374.5t-181 287q58 -15 108 -15q43 0 111 15q63 -111 133.5 -229.5t167 -276.5t138.5 -227q37 61 109.5 177.5t117.5 190t105 176t107 189.5q54 -14 107 -14q56 0 114 14v0 q-28 -39 -60 -88.5t-49.5 -78.5t-56.5 -96t-49 -84q-146 -248 -353 -610z" />
<glyph unicode="&#xf1a0;" horiz-adv-x="1280" d="M981 197q0 25 -7 49t-14.5 42t-27 41.5t-29.5 35t-38.5 34.5t-36.5 29t-41.5 30t-36.5 26q-16 2 -49 2q-53 0 -104.5 -7t-107 -25t-97 -46t-68.5 -74.5t-27 -105.5q0 -56 23.5 -102t61 -75.5t87 -50t100 -29t101.5 -8.5q58 0 111.5 13t99 39t73 73t27.5 109zM864 1055 q0 59 -17 125.5t-48 129t-84 103.5t-117 41q-42 0 -82.5 -19.5t-66.5 -52.5q-46 -59 -46 -160q0 -46 10 -97.5t31.5 -103t52 -92.5t75 -67t96.5 -26q37 0 77.5 16.5t65.5 43.5q53 56 53 159zM752 1536h417l-137 -88h-132q75 -63 113 -133t38 -160q0 -72 -24.5 -129.5 t-59.5 -93t-69.5 -65t-59 -61.5t-24.5 -66q0 -36 32 -70.5t77 -68t90.5 -73.5t77.5 -104t32 -142q0 -91 -49 -173q-71 -122 -209.5 -179.5t-298.5 -57.5q-132 0 -246.5 41.5t-172.5 137.5q-36 59 -36 131q0 81 44.5 150t118.5 115q131 82 404 100q-32 41 -47.5 73.5 t-15.5 73.5q0 40 21 85q-46 -4 -68 -4q-148 0 -249.5 96.5t-101.5 244.5q0 82 36 159t99 131q76 66 182 98t218 32z" />
<glyph unicode="&#xf1a1;" horiz-adv-x="2304" d="M1509 107q0 -14 -12 -29q-52 -59 -147.5 -83t-196.5 -24q-252 0 -346 107q-12 15 -12 29q0 17 12 29.5t29 12.5q15 0 30 -12q58 -49 125.5 -66t159.5 -17t160 17t127 66q15 12 30 12q17 0 29 -12.5t12 -29.5zM978 498q0 -61 -43 -104t-104 -43q-60 0 -104.5 43.5 t-44.5 103.5q0 61 44 105t105 44t104 -44t43 -105zM1622 498q0 -61 -43 -104t-104 -43q-60 0 -104.5 43.5t-44.5 103.5q0 61 44 105t105 44t104 -44t43 -105zM415 793q-39 27 -88 27q-66 0 -113 -47t-47 -113q0 -72 54 -121q53 141 194 254zM2020 382q0 222 -249 387 q-128 85 -291.5 126.5t-331.5 41.5t-331.5 -41.5t-292.5 -126.5q-249 -165 -249 -387t249 -387q129 -85 292.5 -126.5t331.5 -41.5t331.5 41.5t291.5 126.5q249 165 249 387zM2137 660q0 66 -47 113t-113 47q-50 0 -93 -30q140 -114 192 -256q61 48 61 126zM1993 1335 q0 49 -34.5 83.5t-82.5 34.5q-49 0 -83.5 -34.5t-34.5 -83.5q0 -48 34.5 -82.5t83.5 -34.5q48 0 82.5 34.5t34.5 82.5zM2220 660q0 -65 -33 -122t-89 -90q5 -35 5 -66q0 -139 -79 -255.5t-208 -201.5q-140 -92 -313.5 -136.5t-354.5 -44.5t-355 44.5t-314 136.5 q-129 85 -208 201.5t-79 255.5q0 36 6 71q-53 33 -83.5 88.5t-30.5 118.5q0 100 71 171.5t172 71.5q91 0 159 -60q265 170 638 177l144 456q10 29 40 29q24 0 384 -90q24 55 74 88t110 33q82 0 141 -59t59 -142t-59 -141.5t-141 -58.5q-83 0 -141.5 58.5t-59.5 140.5 l-339 80l-125 -395q349 -15 603 -179q71 63 163 63q101 0 172 -71.5t71 -171.5z" />
<glyph unicode="&#xf1a2;" d="M950 393q7 7 17.5 7t17.5 -7t7 -18t-7 -18q-65 -64 -208 -64h-1h-1q-143 0 -207 64q-8 7 -8 18t8 18q7 7 17.5 7t17.5 -7q49 -51 172 -51h1h1q122 0 173 51zM671 613q0 -37 -26 -64t-63 -27t-63 27t-26 64t26 63t63 26t63 -26t26 -63zM1214 1049q-29 0 -50 21t-21 50 q0 30 21 51t50 21q30 0 51 -21t21 -51q0 -29 -21 -50t-51 -21zM1216 1408q132 0 226 -94t94 -227v-894q0 -133 -94 -227t-226 -94h-896q-132 0 -226 94t-94 227v894q0 133 94 227t226 94h896zM1321 596q35 14 57 45.5t22 70.5q0 51 -36 87.5t-87 36.5q-60 0 -98 -48 q-151 107 -375 115l83 265l206 -49q1 -50 36.5 -85t84.5 -35q50 0 86 35.5t36 85.5t-36 86t-86 36q-36 0 -66 -20.5t-45 -53.5l-227 54q-9 2 -17.5 -2.5t-11.5 -14.5l-95 -302q-224 -4 -381 -113q-36 43 -93 43q-51 0 -87 -36.5t-36 -87.5q0 -37 19.5 -67.5t52.5 -45.5 q-7 -25 -7 -54q0 -98 74 -181.5t201.5 -132t278.5 -48.5q150 0 277.5 48.5t201.5 132t74 181.5q0 27 -6 54zM971 702q37 0 63 -26t26 -63t-26 -64t-63 -27t-63 27t-26 64t26 63t63 26z" />
<glyph unicode="&#xf1a3;" d="M866 697l90 27v62q0 79 -58 135t-138 56t-138 -55.5t-58 -134.5v-283q0 -20 -14 -33.5t-33 -13.5t-32.5 13.5t-13.5 33.5v120h-151v-122q0 -82 57.5 -139t139.5 -57q81 0 138.5 56.5t57.5 136.5v280q0 19 13.5 33t33.5 14q19 0 32.5 -14t13.5 -33v-54zM1199 502v122h-150 v-126q0 -20 -13.5 -33.5t-33.5 -13.5q-19 0 -32.5 14t-13.5 33v123l-90 -26l-60 28v-123q0 -80 58 -137t139 -57t138.5 57t57.5 139zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103 t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf1a4;" horiz-adv-x="1920" d="M1062 824v118q0 42 -30 72t-72 30t-72 -30t-30 -72v-612q0 -175 -126 -299t-303 -124q-178 0 -303.5 125.5t-125.5 303.5v266h328v-262q0 -43 30 -72.5t72 -29.5t72 29.5t30 72.5v620q0 171 126.5 292t301.5 121q176 0 302 -122t126 -294v-136l-195 -58zM1592 602h328 v-266q0 -178 -125.5 -303.5t-303.5 -125.5q-177 0 -303 124.5t-126 300.5v268l131 -61l195 58v-270q0 -42 30 -71.5t72 -29.5t72 29.5t30 71.5v275z" />
<glyph unicode="&#xf1a5;" d="M1472 160v480h-704v704h-480q-93 0 -158.5 -65.5t-65.5 -158.5v-480h704v-704h480q93 0 158.5 65.5t65.5 158.5zM1536 1120v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5 t84.5 -203.5z" />
<glyph unicode="&#xf1a6;" horiz-adv-x="2048" d="M328 1254h204v-983h-532v697h328v286zM328 435v369h-123v-369h123zM614 968v-697h205v697h-205zM614 1254v-204h205v204h-205zM901 968h533v-942h-533v163h328v82h-328v697zM1229 435v369h-123v-369h123zM1516 968h532v-942h-532v163h327v82h-327v697zM1843 435v369h-123 v-369h123z" />
<glyph unicode="&#xf1a7;" d="M1046 516q0 -64 -38 -109t-91 -45q-43 0 -70 15v277q28 17 70 17q53 0 91 -45.5t38 -109.5zM703 944q0 -64 -38 -109.5t-91 -45.5q-43 0 -70 15v277q28 17 70 17q53 0 91 -45t38 -109zM1265 513q0 134 -88 229t-213 95q-20 0 -39 -3q-23 -78 -78 -136q-87 -95 -211 -101 v-636l211 41v206q51 -19 117 -19q125 0 213 95t88 229zM922 940q0 134 -88.5 229t-213.5 95q-74 0 -141 -36h-186v-840l211 41v206q55 -19 116 -19q125 0 213.5 95t88.5 229zM1536 1120v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960 q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf1a8;" horiz-adv-x="2038" d="M1222 607q75 3 143.5 -20.5t118 -58.5t101 -94.5t84 -108t75.5 -120.5q33 -56 78.5 -109t75.5 -80.5t99 -88.5q-48 -30 -108.5 -57.5t-138.5 -59t-114 -47.5q-44 37 -74 115t-43.5 164.5t-33 180.5t-42.5 168.5t-72.5 123t-122.5 48.5l-10 -2l-6 -4q4 -5 13 -14 q6 -5 28 -23.5t25.5 -22t19 -18t18 -20.5t11.5 -21t10.5 -27.5t4.5 -31t4 -40.5l1 -33q1 -26 -2.5 -57.5t-7.5 -52t-12.5 -58.5t-11.5 -53q-35 1 -101 -9.5t-98 -10.5q-39 0 -72 10q-2 16 -2 47q0 74 3 96q2 13 31.5 41.5t57 59t26.5 51.5q-24 2 -43 -24 q-36 -53 -111.5 -99.5t-136.5 -46.5q-25 0 -75.5 63t-106.5 139.5t-84 96.5q-6 4 -27 30q-482 -112 -513 -112q-16 0 -28 11t-12 27q0 15 8.5 26.5t22.5 14.5l486 106q-8 14 -8 25t5.5 17.5t16 11.5t20 7t23 4.5t18.5 4.5q4 1 15.5 7.5t17.5 6.5q15 0 28 -16t20 -33 q163 37 172 37q17 0 29.5 -11t12.5 -28q0 -15 -8.5 -26t-23.5 -14l-182 -40l-1 -16q-1 -26 81.5 -117.5t104.5 -91.5q47 0 119 80t72 129q0 36 -23.5 53t-51 18.5t-51 11.5t-23.5 34q0 16 10 34l-68 19q43 44 43 117q0 26 -5 58q82 16 144 16q44 0 71.5 -1.5t48.5 -8.5 t31 -13.5t20.5 -24.5t15.5 -33.5t17 -47.5t24 -60l50 25q-3 -40 -23 -60t-42.5 -21t-40 -6.5t-16.5 -20.5zM1282 842q-5 5 -13.5 15.5t-12 14.5t-10.5 11.5t-10 10.5l-8 8t-8.5 7.5t-8 5t-8.5 4.5q-7 3 -14.5 5t-20.5 2.5t-22 0.5h-32.5h-37.5q-126 0 -217 -43 q16 30 36 46.5t54 29.5t65.5 36t46 36.5t50 55t43.5 50.5q12 -9 28 -31.5t32 -36.5t38 -13l12 1v-76l22 -1q247 95 371 190q28 21 50 39t42.5 37.5t33 31t29.5 34t24 31t24.5 37t23 38t27 47.5t29.5 53l7 9q-2 -53 -43 -139q-79 -165 -205 -264t-306 -142q-14 -3 -42 -7.5 t-50 -9.5t-39 -14q3 -19 24.5 -46t21.5 -34q0 -11 -26 -30zM1061 -79q39 26 131.5 47.5t146.5 21.5q9 0 22.5 -15.5t28 -42.5t26 -50t24 -51t14.5 -33q-121 -45 -244 -45q-61 0 -125 11zM822 568l48 12l109 -177l-73 -48zM1323 51q3 -15 3 -16q0 -7 -17.5 -14.5t-46 -13 t-54 -9.5t-53.5 -7.5t-32 -4.5l-7 43q21 2 60.5 8.5t72 10t60.5 3.5h14zM866 679l-96 -20l-6 17q10 1 32.5 7t34.5 6q19 0 35 -10zM1061 45h31l10 -83l-41 -12v95zM1950 1535v1v-1zM1950 1535l-1 -5l-2 -2l1 3zM1950 1535l1 1z" />
<glyph unicode="&#xf1a9;" d="M1167 -50q-5 19 -24 5q-30 -22 -87 -39t-131 -17q-129 0 -193 49q-5 4 -13 4q-11 0 -26 -12q-7 -6 -7.5 -16t7.5 -20q34 -32 87.5 -46t102.5 -12.5t99 4.5q41 4 84.5 20.5t65 30t28.5 20.5q12 12 7 29zM1128 65q-19 47 -39 61q-23 15 -76 15q-47 0 -71 -10 q-29 -12 -78 -56q-26 -24 -12 -44q9 -8 17.5 -4.5t31.5 23.5q3 2 10.5 8.5t10.5 8.5t10 7t11.5 7t12.5 5t15 4.5t16.5 2.5t20.5 1q27 0 44.5 -7.5t23 -14.5t13.5 -22q10 -17 12.5 -20t12.5 1q23 12 14 34zM1483 346q0 22 -5 44.5t-16.5 45t-34 36.5t-52.5 14 q-33 0 -97 -41.5t-129 -83.5t-101 -42q-27 -1 -63.5 19t-76 49t-83.5 58t-100 49t-111 19q-115 -1 -197 -78.5t-84 -178.5q-2 -112 74 -164q29 -20 62.5 -28.5t103.5 -8.5q57 0 132 32.5t134 71t120 70.5t93 31q26 -1 65 -31.5t71.5 -67t68 -67.5t55.5 -32q35 -3 58.5 14 t55.5 63q28 41 42.5 101t14.5 106zM1536 506q0 -164 -62 -304.5t-166 -236t-242.5 -149.5t-290.5 -54t-293 57.5t-247.5 157t-170.5 241.5t-64 302q0 89 19.5 172.5t49 145.5t70.5 118.5t78.5 94t78.5 69.5t64.5 46.5t42.5 24.5q14 8 51 26.5t54.5 28.5t48 30t60.5 44 q36 28 58 72.5t30 125.5q129 -155 186 -193q44 -29 130 -68t129 -66q21 -13 39 -25t60.5 -46.5t76 -70.5t75 -95t69 -122t47 -148.5t19.5 -177.5z" />
<glyph unicode="&#xf1aa;" d="M1070 463l-160 -160l-151 -152l-30 -30q-65 -64 -151.5 -87t-171.5 -2q-16 -70 -72 -115t-129 -45q-85 0 -145 60.5t-60 145.5q0 72 44.5 128t113.5 72q-22 86 1 173t88 152l12 12l151 -152l-11 -11q-37 -37 -37 -89t37 -90q37 -37 89 -37t89 37l30 30l151 152l161 160z M729 1145l12 -12l-152 -152l-12 12q-37 37 -89 37t-89 -37t-37 -89.5t37 -89.5l29 -29l152 -152l160 -160l-151 -152l-161 160l-151 152l-30 30q-68 67 -90 159.5t5 179.5q-70 15 -115 71t-45 129q0 85 60 145.5t145 60.5q76 0 133.5 -49t69.5 -123q84 20 169.5 -3.5 t149.5 -87.5zM1536 78q0 -85 -60 -145.5t-145 -60.5q-74 0 -131 47t-71 118q-86 -28 -179.5 -6t-161.5 90l-11 12l151 152l12 -12q37 -37 89 -37t89 37t37 89t-37 89l-30 30l-152 152l-160 160l152 152l160 -160l152 -152l29 -30q64 -64 87.5 -150.5t2.5 -171.5 q76 -11 126.5 -68.5t50.5 -134.5zM1534 1202q0 -77 -51 -135t-127 -69q26 -85 3 -176.5t-90 -158.5l-12 -12l-151 152l12 12q37 37 37 89t-37 89t-89 37t-89 -37l-30 -30l-152 -152l-160 -160l-152 152l161 160l152 152l29 30q67 67 159 89.5t178 -3.5q11 75 68.5 126 t135.5 51q85 0 145 -60.5t60 -145.5z" />
<glyph unicode="&#xf1ab;" d="M654 458q-1 -3 -12.5 0.5t-31.5 11.5l-20 9q-44 20 -87 49q-7 5 -41 31.5t-38 28.5q-67 -103 -134 -181q-81 -95 -105 -110q-4 -2 -19.5 -4t-18.5 0q6 4 82 92q21 24 85.5 115t78.5 118q17 30 51 98.5t36 77.5q-8 1 -110 -33q-8 -2 -27.5 -7.5t-34.5 -9.5t-17 -5 q-2 -2 -2 -10.5t-1 -9.5q-5 -10 -31 -15q-23 -7 -47 0q-18 4 -28 21q-4 6 -5 23q6 2 24.5 5t29.5 6q58 16 105 32q100 35 102 35q10 2 43 19.5t44 21.5q9 3 21.5 8t14.5 5.5t6 -0.5q2 -12 -1 -33q0 -2 -12.5 -27t-26.5 -53.5t-17 -33.5q-25 -50 -77 -131l64 -28 q12 -6 74.5 -32t67.5 -28q4 -1 10.5 -25.5t4.5 -30.5zM449 944q3 -15 -4 -28q-12 -23 -50 -38q-30 -12 -60 -12q-26 3 -49 26q-14 15 -18 41l1 3q3 -3 19.5 -5t26.5 0t58 16q36 12 55 14q17 0 21 -17zM1147 815l63 -227l-139 42zM39 15l694 232v1032l-694 -233v-1031z M1280 332l102 -31l-181 657l-100 31l-216 -536l102 -31l45 110l211 -65zM777 1294l573 -184v380zM1088 -29l158 -13l-54 -160l-40 66q-130 -83 -276 -108q-58 -12 -91 -12h-84q-79 0 -199.5 39t-183.5 85q-8 7 -8 16q0 8 5 13.5t13 5.5q4 0 18 -7.5t30.5 -16.5t20.5 -11 q73 -37 159.5 -61.5t157.5 -24.5q95 0 167 14.5t157 50.5q15 7 30.5 15.5t34 19t28.5 16.5zM1536 1050v-1079l-774 246q-14 -6 -375 -127.5t-368 -121.5q-13 0 -18 13q0 1 -1 3v1078q3 9 4 10q5 6 20 11q106 35 149 50v384l558 -198q2 0 160.5 55t316 108.5t161.5 53.5 q20 0 20 -21v-418z" />
<glyph unicode="&#xf1ac;" horiz-adv-x="1792" d="M288 1152q66 0 113 -47t47 -113v-1088q0 -66 -47 -113t-113 -47h-128q-66 0 -113 47t-47 113v1088q0 66 47 113t113 47h128zM1664 989q58 -34 93 -93t35 -128v-768q0 -106 -75 -181t-181 -75h-864q-66 0 -113 47t-47 113v1536q0 40 28 68t68 28h672q40 0 88 -20t76 -48 l152 -152q28 -28 48 -76t20 -88v-163zM928 0v128q0 14 -9 23t-23 9h-128q-14 0 -23 -9t-9 -23v-128q0 -14 9 -23t23 -9h128q14 0 23 9t9 23zM928 256v128q0 14 -9 23t-23 9h-128q-14 0 -23 -9t-9 -23v-128q0 -14 9 -23t23 -9h128q14 0 23 9t9 23zM928 512v128q0 14 -9 23 t-23 9h-128q-14 0 -23 -9t-9 -23v-128q0 -14 9 -23t23 -9h128q14 0 23 9t9 23zM1184 0v128q0 14 -9 23t-23 9h-128q-14 0 -23 -9t-9 -23v-128q0 -14 9 -23t23 -9h128q14 0 23 9t9 23zM1184 256v128q0 14 -9 23t-23 9h-128q-14 0 -23 -9t-9 -23v-128q0 -14 9 -23t23 -9h128 q14 0 23 9t9 23zM1184 512v128q0 14 -9 23t-23 9h-128q-14 0 -23 -9t-9 -23v-128q0 -14 9 -23t23 -9h128q14 0 23 9t9 23zM1440 0v128q0 14 -9 23t-23 9h-128q-14 0 -23 -9t-9 -23v-128q0 -14 9 -23t23 -9h128q14 0 23 9t9 23zM1440 256v128q0 14 -9 23t-23 9h-128 q-14 0 -23 -9t-9 -23v-128q0 -14 9 -23t23 -9h128q14 0 23 9t9 23zM1440 512v128q0 14 -9 23t-23 9h-128q-14 0 -23 -9t-9 -23v-128q0 -14 9 -23t23 -9h128q14 0 23 9t9 23zM1536 896v256h-160q-40 0 -68 28t-28 68v160h-640v-512h896z" />
<glyph unicode="&#xf1ad;" d="M1344 1536q26 0 45 -19t19 -45v-1664q0 -26 -19 -45t-45 -19h-1280q-26 0 -45 19t-19 45v1664q0 26 19 45t45 19h1280zM512 1248v-64q0 -14 9 -23t23 -9h64q14 0 23 9t9 23v64q0 14 -9 23t-23 9h-64q-14 0 -23 -9t-9 -23zM512 992v-64q0 -14 9 -23t23 -9h64q14 0 23 9 t9 23v64q0 14 -9 23t-23 9h-64q-14 0 -23 -9t-9 -23zM512 736v-64q0 -14 9 -23t23 -9h64q14 0 23 9t9 23v64q0 14 -9 23t-23 9h-64q-14 0 -23 -9t-9 -23zM512 480v-64q0 -14 9 -23t23 -9h64q14 0 23 9t9 23v64q0 14 -9 23t-23 9h-64q-14 0 -23 -9t-9 -23zM384 160v64 q0 14 -9 23t-23 9h-64q-14 0 -23 -9t-9 -23v-64q0 -14 9 -23t23 -9h64q14 0 23 9t9 23zM384 416v64q0 14 -9 23t-23 9h-64q-14 0 -23 -9t-9 -23v-64q0 -14 9 -23t23 -9h64q14 0 23 9t9 23zM384 672v64q0 14 -9 23t-23 9h-64q-14 0 -23 -9t-9 -23v-64q0 -14 9 -23t23 -9h64 q14 0 23 9t9 23zM384 928v64q0 14 -9 23t-23 9h-64q-14 0 -23 -9t-9 -23v-64q0 -14 9 -23t23 -9h64q14 0 23 9t9 23zM384 1184v64q0 14 -9 23t-23 9h-64q-14 0 -23 -9t-9 -23v-64q0 -14 9 -23t23 -9h64q14 0 23 9t9 23zM896 -96v192q0 14 -9 23t-23 9h-320q-14 0 -23 -9 t-9 -23v-192q0 -14 9 -23t23 -9h320q14 0 23 9t9 23zM896 416v64q0 14 -9 23t-23 9h-64q-14 0 -23 -9t-9 -23v-64q0 -14 9 -23t23 -9h64q14 0 23 9t9 23zM896 672v64q0 14 -9 23t-23 9h-64q-14 0 -23 -9t-9 -23v-64q0 -14 9 -23t23 -9h64q14 0 23 9t9 23zM896 928v64 q0 14 -9 23t-23 9h-64q-14 0 -23 -9t-9 -23v-64q0 -14 9 -23t23 -9h64q14 0 23 9t9 23zM896 1184v64q0 14 -9 23t-23 9h-64q-14 0 -23 -9t-9 -23v-64q0 -14 9 -23t23 -9h64q14 0 23 9t9 23zM1152 160v64q0 14 -9 23t-23 9h-64q-14 0 -23 -9t-9 -23v-64q0 -14 9 -23t23 -9h64 q14 0 23 9t9 23zM1152 416v64q0 14 -9 23t-23 9h-64q-14 0 -23 -9t-9 -23v-64q0 -14 9 -23t23 -9h64q14 0 23 9t9 23zM1152 672v64q0 14 -9 23t-23 9h-64q-14 0 -23 -9t-9 -23v-64q0 -14 9 -23t23 -9h64q14 0 23 9t9 23zM1152 928v64q0 14 -9 23t-23 9h-64q-14 0 -23 -9 t-9 -23v-64q0 -14 9 -23t23 -9h64q14 0 23 9t9 23zM1152 1184v64q0 14 -9 23t-23 9h-64q-14 0 -23 -9t-9 -23v-64q0 -14 9 -23t23 -9h64q14 0 23 9t9 23z" />
<glyph unicode="&#xf1ae;" horiz-adv-x="1280" d="M1188 988l-292 -292v-824q0 -46 -33 -79t-79 -33t-79 33t-33 79v384h-64v-384q0 -46 -33 -79t-79 -33t-79 33t-33 79v824l-292 292q-28 28 -28 68t28 68t68 28t68 -28l228 -228h368l228 228q28 28 68 28t68 -28t28 -68t-28 -68zM864 1152q0 -93 -65.5 -158.5 t-158.5 -65.5t-158.5 65.5t-65.5 158.5t65.5 158.5t158.5 65.5t158.5 -65.5t65.5 -158.5z" />
<glyph unicode="&#xf1b0;" horiz-adv-x="1664" d="M780 1064q0 -60 -19 -113.5t-63 -92.5t-105 -39q-76 0 -138 57.5t-92 135.5t-30 151q0 60 19 113.5t63 92.5t105 39q77 0 138.5 -57.5t91.5 -135t30 -151.5zM438 581q0 -80 -42 -139t-119 -59q-76 0 -141.5 55.5t-100.5 133.5t-35 152q0 80 42 139.5t119 59.5 q76 0 141.5 -55.5t100.5 -134t35 -152.5zM832 608q118 0 255 -97.5t229 -237t92 -254.5q0 -46 -17 -76.5t-48.5 -45t-64.5 -20t-76 -5.5q-68 0 -187.5 45t-182.5 45q-66 0 -192.5 -44.5t-200.5 -44.5q-183 0 -183 146q0 86 56 191.5t139.5 192.5t187.5 146t193 59zM1071 819 q-61 0 -105 39t-63 92.5t-19 113.5q0 74 30 151.5t91.5 135t138.5 57.5q61 0 105 -39t63 -92.5t19 -113.5q0 -73 -30 -151t-92 -135.5t-138 -57.5zM1503 923q77 0 119 -59.5t42 -139.5q0 -74 -35 -152t-100.5 -133.5t-141.5 -55.5q-77 0 -119 59t-42 139q0 74 35 152.5 t100.5 134t141.5 55.5z" />
<glyph unicode="&#xf1b1;" horiz-adv-x="768" d="M704 1008q0 -145 -57 -243.5t-152 -135.5l45 -821q2 -26 -16 -45t-44 -19h-192q-26 0 -44 19t-16 45l45 821q-95 37 -152 135.5t-57 243.5q0 128 42.5 249.5t117.5 200t160 78.5t160 -78.5t117.5 -200t42.5 -249.5z" />
<glyph unicode="&#xf1b2;" horiz-adv-x="1792" d="M896 -93l640 349v636l-640 -233v-752zM832 772l698 254l-698 254l-698 -254zM1664 1024v-768q0 -35 -18 -65t-49 -47l-704 -384q-28 -16 -61 -16t-61 16l-704 384q-31 17 -49 47t-18 65v768q0 40 23 73t61 47l704 256q22 8 44 8t44 -8l704 -256q38 -14 61 -47t23 -73z " />
<glyph unicode="&#xf1b3;" horiz-adv-x="2304" d="M640 -96l384 192v314l-384 -164v-342zM576 358l404 173l-404 173l-404 -173zM1664 -96l384 192v314l-384 -164v-342zM1600 358l404 173l-404 173l-404 -173zM1152 651l384 165v266l-384 -164v-267zM1088 1030l441 189l-441 189l-441 -189zM2176 512v-416q0 -36 -19 -67 t-52 -47l-448 -224q-25 -14 -57 -14t-57 14l-448 224q-5 2 -7 4q-2 -2 -7 -4l-448 -224q-25 -14 -57 -14t-57 14l-448 224q-33 16 -52 47t-19 67v416q0 38 21.5 70t56.5 48l434 186v400q0 38 21.5 70t56.5 48l448 192q23 10 50 10t50 -10l448 -192q35 -16 56.5 -48t21.5 -70 v-400l434 -186q36 -16 57 -48t21 -70z" />
<glyph unicode="&#xf1b4;" horiz-adv-x="2048" d="M1848 1197h-511v-124h511v124zM1596 771q-90 0 -146 -52.5t-62 -142.5h408q-18 195 -200 195zM1612 186q63 0 122 32t76 87h221q-100 -307 -427 -307q-214 0 -340.5 132t-126.5 347q0 208 130.5 345.5t336.5 137.5q138 0 240.5 -68t153 -179t50.5 -248q0 -17 -2 -47h-658 q0 -111 57.5 -171.5t166.5 -60.5zM277 236h296q205 0 205 167q0 180 -199 180h-302v-347zM277 773h281q78 0 123.5 36.5t45.5 113.5q0 144 -190 144h-260v-294zM0 1282h594q87 0 155 -14t126.5 -47.5t90 -96.5t31.5 -154q0 -181 -172 -263q114 -32 172 -115t58 -204 q0 -75 -24.5 -136.5t-66 -103.5t-98.5 -71t-121 -42t-134 -13h-611v1260z" />
<glyph unicode="&#xf1b5;" d="M1248 1408q119 0 203.5 -84.5t84.5 -203.5v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960zM499 1041h-371v-787h382q117 0 197 57.5t80 170.5q0 158 -143 200q107 52 107 164q0 57 -19.5 96.5 t-56.5 60.5t-79 29.5t-97 8.5zM477 723h-176v184h163q119 0 119 -90q0 -94 -106 -94zM486 388h-185v217h189q124 0 124 -113q0 -104 -128 -104zM1136 356q-68 0 -104 38t-36 107h411q1 10 1 30q0 132 -74.5 220.5t-203.5 88.5q-128 0 -210 -86t-82 -216q0 -135 79 -217 t213 -82q205 0 267 191h-138q-11 -34 -47.5 -54t-75.5 -20zM1126 722q113 0 124 -122h-254q4 56 39 89t91 33zM964 988h319v-77h-319v77z" />
<glyph unicode="&#xf1b6;" horiz-adv-x="1792" d="M1582 954q0 -101 -71.5 -172.5t-172.5 -71.5t-172.5 71.5t-71.5 172.5t71.5 172.5t172.5 71.5t172.5 -71.5t71.5 -172.5zM812 212q0 104 -73 177t-177 73q-27 0 -54 -6l104 -42q77 -31 109.5 -106.5t1.5 -151.5q-31 -77 -107 -109t-152 -1q-21 8 -62 24.5t-61 24.5 q32 -60 91 -96.5t130 -36.5q104 0 177 73t73 177zM1642 953q0 126 -89.5 215.5t-215.5 89.5q-127 0 -216.5 -89.5t-89.5 -215.5q0 -127 89.5 -216t216.5 -89q126 0 215.5 89t89.5 216zM1792 953q0 -189 -133.5 -322t-321.5 -133l-437 -319q-12 -129 -109 -218t-229 -89 q-121 0 -214 76t-118 192l-230 92v429l389 -157q79 48 173 48q13 0 35 -2l284 407q2 187 135.5 319t320.5 132q188 0 321.5 -133.5t133.5 -321.5z" />
<glyph unicode="&#xf1b7;" d="M1242 889q0 80 -57 136.5t-137 56.5t-136.5 -57t-56.5 -136q0 -80 56.5 -136.5t136.5 -56.5t137 56.5t57 136.5zM632 301q0 -83 -58 -140.5t-140 -57.5q-56 0 -103 29t-72 77q52 -20 98 -40q60 -24 120 1.5t85 86.5q24 60 -1.5 120t-86.5 84l-82 33q22 5 42 5 q82 0 140 -57.5t58 -140.5zM1536 1120v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v153l172 -69q20 -92 93.5 -152t168.5 -60q104 0 181 70t87 173l345 252q150 0 255.5 105.5t105.5 254.5q0 150 -105.5 255.5t-255.5 105.5 q-148 0 -253 -104.5t-107 -252.5l-225 -322q-9 1 -28 1q-75 0 -137 -37l-297 119v468q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5zM1289 887q0 -100 -71 -170.5t-171 -70.5t-170.5 70.5t-70.5 170.5t70.5 171t170.5 71q101 0 171.5 -70.5t70.5 -171.5z " />
<glyph unicode="&#xf1b8;" horiz-adv-x="1792" d="M836 367l-15 -368l-2 -22l-420 29q-36 3 -67 31.5t-47 65.5q-11 27 -14.5 55t4 65t12 55t21.5 64t19 53q78 -12 509 -28zM449 953l180 -379l-147 92q-63 -72 -111.5 -144.5t-72.5 -125t-39.5 -94.5t-18.5 -63l-4 -21l-190 357q-17 26 -18 56t6 47l8 18q35 63 114 188 l-140 86zM1680 436l-188 -359q-12 -29 -36.5 -46.5t-43.5 -20.5l-18 -4q-71 -7 -219 -12l8 -164l-230 367l211 362l7 -173q170 -16 283 -5t170 33zM895 1360q-47 -63 -265 -435l-317 187l-19 12l225 356q20 31 60 45t80 10q24 -2 48.5 -12t42 -21t41.5 -33t36 -34.5 t36 -39.5t32 -35zM1550 1053l212 -363q18 -37 12.5 -76t-27.5 -74q-13 -20 -33 -37t-38 -28t-48.5 -22t-47 -16t-51.5 -14t-46 -12q-34 72 -265 436l313 195zM1407 1279l142 83l-220 -373l-419 20l151 86q-34 89 -75 166t-75.5 123.5t-64.5 80t-47 46.5l-17 13l405 -1 q31 3 58 -10.5t39 -28.5l11 -15q39 -61 112 -190z" />
<glyph unicode="&#xf1b9;" horiz-adv-x="2048" d="M480 448q0 66 -47 113t-113 47t-113 -47t-47 -113t47 -113t113 -47t113 47t47 113zM516 768h1016l-89 357q-2 8 -14 17.5t-21 9.5h-768q-9 0 -21 -9.5t-14 -17.5zM1888 448q0 66 -47 113t-113 47t-113 -47t-47 -113t47 -113t113 -47t113 47t47 113zM2048 544v-384 q0 -14 -9 -23t-23 -9h-96v-128q0 -80 -56 -136t-136 -56t-136 56t-56 136v128h-1024v-128q0 -80 -56 -136t-136 -56t-136 56t-56 136v128h-96q-14 0 -23 9t-9 23v384q0 93 65.5 158.5t158.5 65.5h28l105 419q23 94 104 157.5t179 63.5h768q98 0 179 -63.5t104 -157.5 l105 -419h28q93 0 158.5 -65.5t65.5 -158.5z" />
<glyph unicode="&#xf1ba;" horiz-adv-x="2048" d="M1824 640q93 0 158.5 -65.5t65.5 -158.5v-384q0 -14 -9 -23t-23 -9h-96v-64q0 -80 -56 -136t-136 -56t-136 56t-56 136v64h-1024v-64q0 -80 -56 -136t-136 -56t-136 56t-56 136v64h-96q-14 0 -23 9t-9 23v384q0 93 65.5 158.5t158.5 65.5h28l105 419q23 94 104 157.5 t179 63.5h128v224q0 14 9 23t23 9h448q14 0 23 -9t9 -23v-224h128q98 0 179 -63.5t104 -157.5l105 -419h28zM320 160q66 0 113 47t47 113t-47 113t-113 47t-113 -47t-47 -113t47 -113t113 -47zM516 640h1016l-89 357q-2 8 -14 17.5t-21 9.5h-768q-9 0 -21 -9.5t-14 -17.5z M1728 160q66 0 113 47t47 113t-47 113t-113 47t-113 -47t-47 -113t47 -113t113 -47z" />
<glyph unicode="&#xf1bb;" d="M1504 64q0 -26 -19 -45t-45 -19h-462q1 -17 6 -87.5t5 -108.5q0 -25 -18 -42.5t-43 -17.5h-320q-25 0 -43 17.5t-18 42.5q0 38 5 108.5t6 87.5h-462q-26 0 -45 19t-19 45t19 45l402 403h-229q-26 0 -45 19t-19 45t19 45l402 403h-197q-26 0 -45 19t-19 45t19 45l384 384 q19 19 45 19t45 -19l384 -384q19 -19 19 -45t-19 -45t-45 -19h-197l402 -403q19 -19 19 -45t-19 -45t-45 -19h-229l402 -403q19 -19 19 -45z" />
<glyph unicode="&#xf1bc;" d="M1127 326q0 32 -30 51q-193 115 -447 115q-133 0 -287 -34q-42 -9 -42 -52q0 -20 13.5 -34.5t35.5 -14.5q5 0 37 8q132 27 243 27q226 0 397 -103q19 -11 33 -11q19 0 33 13.5t14 34.5zM1223 541q0 40 -35 61q-237 141 -548 141q-153 0 -303 -42q-48 -13 -48 -64 q0 -25 17.5 -42.5t42.5 -17.5q7 0 37 8q122 33 251 33q279 0 488 -124q24 -13 38 -13q25 0 42.5 17.5t17.5 42.5zM1331 789q0 47 -40 70q-126 73 -293 110.5t-343 37.5q-204 0 -364 -47q-23 -7 -38.5 -25.5t-15.5 -48.5q0 -31 20.5 -52t51.5 -21q11 0 40 8q133 37 307 37 q159 0 309.5 -34t253.5 -95q21 -12 40 -12q29 0 50.5 20.5t21.5 51.5zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf1bd;" horiz-adv-x="1024" d="M1024 1233l-303 -582l24 -31h279v-415h-507l-44 -30l-142 -273l-30 -30h-301v303l303 583l-24 30h-279v415h507l44 30l142 273l30 30h301v-303z" />
<glyph unicode="&#xf1be;" horiz-adv-x="2304" d="M784 164l16 241l-16 523q-1 10 -7.5 17t-16.5 7q-9 0 -16 -7t-7 -17l-14 -523l14 -241q1 -10 7.5 -16.5t15.5 -6.5q22 0 24 23zM1080 193l11 211l-12 586q0 16 -13 24q-8 5 -16 5t-16 -5q-13 -8 -13 -24l-1 -6l-10 -579q0 -1 11 -236v-1q0 -10 6 -17q9 -11 23 -11 q11 0 20 9q9 7 9 20zM35 533l20 -128l-20 -126q-2 -9 -9 -9t-9 9l-17 126l17 128q2 9 9 9t9 -9zM121 612l26 -207l-26 -203q-2 -9 -10 -9q-9 0 -9 10l-23 202l23 207q0 9 9 9q8 0 10 -9zM401 159zM213 650l25 -245l-25 -237q0 -11 -11 -11q-10 0 -12 11l-21 237l21 245 q2 12 12 12q11 0 11 -12zM307 657l23 -252l-23 -244q-2 -13 -14 -13q-13 0 -13 13l-21 244l21 252q0 13 13 13q12 0 14 -13zM401 639l21 -234l-21 -246q-2 -16 -16 -16q-6 0 -10.5 4.5t-4.5 11.5l-20 246l20 234q0 6 4.5 10.5t10.5 4.5q14 0 16 -15zM784 164zM495 785 l21 -380l-21 -246q0 -7 -5 -12.5t-12 -5.5q-16 0 -18 18l-18 246l18 380q2 18 18 18q7 0 12 -5.5t5 -12.5zM589 871l19 -468l-19 -244q0 -8 -5.5 -13.5t-13.5 -5.5q-18 0 -20 19l-16 244l16 468q2 19 20 19q8 0 13.5 -5.5t5.5 -13.5zM687 911l18 -506l-18 -242 q-2 -21 -22 -21q-19 0 -21 21l-16 242l16 506q0 9 6.5 15.5t14.5 6.5q9 0 15 -6.5t7 -15.5zM1079 169v0v0zM881 915l15 -510l-15 -239q0 -10 -7.5 -17.5t-17.5 -7.5t-17 7t-8 18l-14 239l14 510q0 11 7.5 18t17.5 7t17.5 -7t7.5 -18zM980 896l14 -492l-14 -236q0 -11 -8 -19 t-19 -8t-19 8t-9 19l-12 236l12 492q1 12 9 20t19 8t18.5 -8t8.5 -20zM1192 404l-14 -231v0q0 -13 -9 -22t-22 -9t-22 9t-10 22l-6 114l-6 117l12 636v3q2 15 12 24q9 7 20 7q8 0 15 -5q14 -8 16 -26zM2304 423q0 -117 -83 -199.5t-200 -82.5h-786q-13 2 -22 11t-9 22v899 q0 23 28 33q85 34 181 34q195 0 338 -131.5t160 -323.5q53 22 110 22q117 0 200 -83t83 -201z" />
<glyph unicode="&#xf1c0;" d="M768 768q237 0 443 43t325 127v-170q0 -69 -103 -128t-280 -93.5t-385 -34.5t-385 34.5t-280 93.5t-103 128v170q119 -84 325 -127t443 -43zM768 0q237 0 443 43t325 127v-170q0 -69 -103 -128t-280 -93.5t-385 -34.5t-385 34.5t-280 93.5t-103 128v170q119 -84 325 -127 t443 -43zM768 384q237 0 443 43t325 127v-170q0 -69 -103 -128t-280 -93.5t-385 -34.5t-385 34.5t-280 93.5t-103 128v170q119 -84 325 -127t443 -43zM768 1536q208 0 385 -34.5t280 -93.5t103 -128v-128q0 -69 -103 -128t-280 -93.5t-385 -34.5t-385 34.5t-280 93.5 t-103 128v128q0 69 103 128t280 93.5t385 34.5z" />
<glyph unicode="&#xf1c1;" d="M1468 1156q28 -28 48 -76t20 -88v-1152q0 -40 -28 -68t-68 -28h-1344q-40 0 -68 28t-28 68v1600q0 40 28 68t68 28h896q40 0 88 -20t76 -48zM1024 1400v-376h376q-10 29 -22 41l-313 313q-12 12 -41 22zM1408 -128v1024h-416q-40 0 -68 28t-28 68v416h-768v-1536h1280z M894 465q33 -26 84 -56q59 7 117 7q147 0 177 -49q16 -22 2 -52q0 -1 -1 -2l-2 -2v-1q-6 -38 -71 -38q-48 0 -115 20t-130 53q-221 -24 -392 -83q-153 -262 -242 -262q-15 0 -28 7l-24 12q-1 1 -6 5q-10 10 -6 36q9 40 56 91.5t132 96.5q14 9 23 -6q2 -2 2 -4q52 85 107 197 q68 136 104 262q-24 82 -30.5 159.5t6.5 127.5q11 40 42 40h21h1q23 0 35 -15q18 -21 9 -68q-2 -6 -4 -8q1 -3 1 -8v-30q-2 -123 -14 -192q55 -164 146 -238zM318 54q52 24 137 158q-51 -40 -87.5 -84t-49.5 -74zM716 974q-15 -42 -2 -132q1 7 7 44q0 3 7 43q1 4 4 8 q-1 1 -1 2t-0.5 1.5t-0.5 1.5q-1 22 -13 36q0 -1 -1 -2v-2zM592 313q135 54 284 81q-2 1 -13 9.5t-16 13.5q-76 67 -127 176q-27 -86 -83 -197q-30 -56 -45 -83zM1238 329q-24 24 -140 24q76 -28 124 -28q14 0 18 1q0 1 -2 3z" />
<glyph unicode="&#xf1c2;" d="M1468 1156q28 -28 48 -76t20 -88v-1152q0 -40 -28 -68t-68 -28h-1344q-40 0 -68 28t-28 68v1600q0 40 28 68t68 28h896q40 0 88 -20t76 -48zM1024 1400v-376h376q-10 29 -22 41l-313 313q-12 12 -41 22zM1408 -128v1024h-416q-40 0 -68 28t-28 68v416h-768v-1536h1280z M233 768v-107h70l164 -661h159l128 485q7 20 10 46q2 16 2 24h4l3 -24q1 -3 3.5 -20t5.5 -26l128 -485h159l164 661h70v107h-300v-107h90l-99 -438q-5 -20 -7 -46l-2 -21h-4l-3 21q-1 5 -4 21t-5 25l-144 545h-114l-144 -545q-2 -9 -4.5 -24.5t-3.5 -21.5l-4 -21h-4l-2 21 q-2 26 -7 46l-99 438h90v107h-300z" />
<glyph unicode="&#xf1c3;" d="M1468 1156q28 -28 48 -76t20 -88v-1152q0 -40 -28 -68t-68 -28h-1344q-40 0 -68 28t-28 68v1600q0 40 28 68t68 28h896q40 0 88 -20t76 -48zM1024 1400v-376h376q-10 29 -22 41l-313 313q-12 12 -41 22zM1408 -128v1024h-416q-40 0 -68 28t-28 68v416h-768v-1536h1280z M429 106v-106h281v106h-75l103 161q5 7 10 16.5t7.5 13.5t3.5 4h2q1 -4 5 -10q2 -4 4.5 -7.5t6 -8t6.5 -8.5l107 -161h-76v-106h291v106h-68l-192 273l195 282h67v107h-279v-107h74l-103 -159q-4 -7 -10 -16.5t-9 -13.5l-2 -3h-2q-1 4 -5 10q-6 11 -17 23l-106 159h76v107 h-290v-107h68l189 -272l-194 -283h-68z" />
<glyph unicode="&#xf1c4;" d="M1468 1156q28 -28 48 -76t20 -88v-1152q0 -40 -28 -68t-68 -28h-1344q-40 0 -68 28t-28 68v1600q0 40 28 68t68 28h896q40 0 88 -20t76 -48zM1024 1400v-376h376q-10 29 -22 41l-313 313q-12 12 -41 22zM1408 -128v1024h-416q-40 0 -68 28t-28 68v416h-768v-1536h1280z M416 106v-106h327v106h-93v167h137q76 0 118 15q67 23 106.5 87t39.5 146q0 81 -37 141t-100 87q-48 19 -130 19h-368v-107h92v-555h-92zM769 386h-119v268h120q52 0 83 -18q56 -33 56 -115q0 -89 -62 -120q-31 -15 -78 -15z" />
<glyph unicode="&#xf1c5;" d="M1468 1156q28 -28 48 -76t20 -88v-1152q0 -40 -28 -68t-68 -28h-1344q-40 0 -68 28t-28 68v1600q0 40 28 68t68 28h896q40 0 88 -20t76 -48zM1024 1400v-376h376q-10 29 -22 41l-313 313q-12 12 -41 22zM1408 -128v1024h-416q-40 0 -68 28t-28 68v416h-768v-1536h1280z M1280 320v-320h-1024v192l192 192l128 -128l384 384zM448 512q-80 0 -136 56t-56 136t56 136t136 56t136 -56t56 -136t-56 -136t-136 -56z" />
<glyph unicode="&#xf1c6;" d="M640 1152v128h-128v-128h128zM768 1024v128h-128v-128h128zM640 896v128h-128v-128h128zM768 768v128h-128v-128h128zM1468 1156q28 -28 48 -76t20 -88v-1152q0 -40 -28 -68t-68 -28h-1344q-40 0 -68 28t-28 68v1600q0 40 28 68t68 28h896q40 0 88 -20t76 -48zM1024 1400 v-376h376q-10 29 -22 41l-313 313q-12 12 -41 22zM1408 -128v1024h-416q-40 0 -68 28t-28 68v416h-128v-128h-128v128h-512v-1536h1280zM781 593l107 -349q8 -27 8 -52q0 -83 -72.5 -137.5t-183.5 -54.5t-183.5 54.5t-72.5 137.5q0 25 8 52q21 63 120 396v128h128v-128h79 q22 0 39 -13t23 -34zM640 128q53 0 90.5 19t37.5 45t-37.5 45t-90.5 19t-90.5 -19t-37.5 -45t37.5 -45t90.5 -19z" />
<glyph unicode="&#xf1c7;" d="M1468 1156q28 -28 48 -76t20 -88v-1152q0 -40 -28 -68t-68 -28h-1344q-40 0 -68 28t-28 68v1600q0 40 28 68t68 28h896q40 0 88 -20t76 -48zM1024 1400v-376h376q-10 29 -22 41l-313 313q-12 12 -41 22zM1408 -128v1024h-416q-40 0 -68 28t-28 68v416h-768v-1536h1280z M620 686q20 -8 20 -30v-544q0 -22 -20 -30q-8 -2 -12 -2q-12 0 -23 9l-166 167h-131q-14 0 -23 9t-9 23v192q0 14 9 23t23 9h131l166 167q16 15 35 7zM1037 -3q31 0 50 24q129 159 129 363t-129 363q-16 21 -43 24t-47 -14q-21 -17 -23.5 -43.5t14.5 -47.5 q100 -123 100 -282t-100 -282q-17 -21 -14.5 -47.5t23.5 -42.5q18 -15 40 -15zM826 145q27 0 47 20q87 93 87 219t-87 219q-18 19 -45 20t-46 -17t-20 -44.5t18 -46.5q52 -57 52 -131t-52 -131q-19 -20 -18 -46.5t20 -44.5q20 -17 44 -17z" />
<glyph unicode="&#xf1c8;" d="M1468 1156q28 -28 48 -76t20 -88v-1152q0 -40 -28 -68t-68 -28h-1344q-40 0 -68 28t-28 68v1600q0 40 28 68t68 28h896q40 0 88 -20t76 -48zM1024 1400v-376h376q-10 29 -22 41l-313 313q-12 12 -41 22zM1408 -128v1024h-416q-40 0 -68 28t-28 68v416h-768v-1536h1280z M768 768q52 0 90 -38t38 -90v-384q0 -52 -38 -90t-90 -38h-384q-52 0 -90 38t-38 90v384q0 52 38 90t90 38h384zM1260 766q20 -8 20 -30v-576q0 -22 -20 -30q-8 -2 -12 -2q-14 0 -23 9l-265 266v90l265 266q9 9 23 9q4 0 12 -2z" />
<glyph unicode="&#xf1c9;" d="M1468 1156q28 -28 48 -76t20 -88v-1152q0 -40 -28 -68t-68 -28h-1344q-40 0 -68 28t-28 68v1600q0 40 28 68t68 28h896q40 0 88 -20t76 -48zM1024 1400v-376h376q-10 29 -22 41l-313 313q-12 12 -41 22zM1408 -128v1024h-416q-40 0 -68 28t-28 68v416h-768v-1536h1280z M480 768q8 11 21 12.5t24 -6.5l51 -38q11 -8 12.5 -21t-6.5 -24l-182 -243l182 -243q8 -11 6.5 -24t-12.5 -21l-51 -38q-11 -8 -24 -6.5t-21 12.5l-226 301q-14 19 0 38zM1282 467q14 -19 0 -38l-226 -301q-8 -11 -21 -12.5t-24 6.5l-51 38q-11 8 -12.5 21t6.5 24l182 243 l-182 243q-8 11 -6.5 24t12.5 21l51 38q11 8 24 6.5t21 -12.5zM662 6q-13 2 -20.5 13t-5.5 24l138 831q2 13 13 20.5t24 5.5l63 -10q13 -2 20.5 -13t5.5 -24l-138 -831q-2 -13 -13 -20.5t-24 -5.5z" />
<glyph unicode="&#xf1ca;" d="M1497 709v-198q-101 -23 -198 -23q-65 -136 -165.5 -271t-181.5 -215.5t-128 -106.5q-80 -45 -162 3q-28 17 -60.5 43.5t-85 83.5t-102.5 128.5t-107.5 184t-105.5 244t-91.5 314.5t-70.5 390h283q26 -218 70 -398.5t104.5 -317t121.5 -235.5t140 -195q169 169 287 406 q-142 72 -223 220t-81 333q0 192 104 314.5t284 122.5q178 0 273 -105.5t95 -297.5q0 -159 -58 -286q-7 -1 -19.5 -3t-46 -2t-63 6t-62 25.5t-50.5 51.5q31 103 31 184q0 87 -29 132t-79 45q-53 0 -85 -49.5t-32 -140.5q0 -186 105 -293.5t267 -107.5q62 0 121 14z" />
<glyph unicode="&#xf1cb;" horiz-adv-x="1792" d="M216 367l603 -402v359l-334 223zM154 511l193 129l-193 129v-258zM973 -35l603 402l-269 180l-334 -223v-359zM896 458l272 182l-272 182l-272 -182zM485 733l334 223v359l-603 -402zM1445 640l193 -129v258zM1307 733l269 180l-603 402v-359zM1792 913v-546 q0 -41 -34 -64l-819 -546q-21 -13 -43 -13t-43 13l-819 546q-34 23 -34 64v546q0 41 34 64l819 546q21 13 43 13t43 -13l819 -546q34 -23 34 -64z" />
<glyph unicode="&#xf1cc;" horiz-adv-x="2048" d="M1800 764q111 -46 179.5 -145.5t68.5 -221.5q0 -164 -118 -280.5t-285 -116.5q-4 0 -11.5 0.5t-10.5 0.5h-1209h-1h-2h-5q-170 10 -288 125.5t-118 280.5q0 110 55 203t147 147q-12 39 -12 82q0 115 82 196t199 81q95 0 172 -58q75 154 222.5 248t326.5 94 q166 0 306 -80.5t221.5 -218.5t81.5 -301q0 -6 -0.5 -18t-0.5 -18zM468 498q0 -122 84 -193t208 -71q137 0 240 99q-16 20 -47.5 56.5t-43.5 50.5q-67 -65 -144 -65q-55 0 -93.5 33.5t-38.5 87.5q0 53 38.5 87t91.5 34q44 0 84.5 -21t73 -55t65 -75t69 -82t77 -75t97 -55 t121.5 -21q121 0 204.5 71.5t83.5 190.5q0 121 -84 192t-207 71q-143 0 -241 -97q14 -16 29.5 -34t34.5 -40t29 -34q66 64 142 64q52 0 92 -33t40 -84q0 -57 -37 -91.5t-94 -34.5q-43 0 -82.5 21t-72 55t-65.5 75t-69.5 82t-77.5 75t-96.5 55t-118.5 21q-122 0 -207 -70.5 t-85 -189.5z" />
<glyph unicode="&#xf1cd;" horiz-adv-x="1792" d="M896 1536q182 0 348 -71t286 -191t191 -286t71 -348t-71 -348t-191 -286t-286 -191t-348 -71t-348 71t-286 191t-191 286t-71 348t71 348t191 286t286 191t348 71zM896 1408q-190 0 -361 -90l194 -194q82 28 167 28t167 -28l194 194q-171 90 -361 90zM218 279l194 194 q-28 82 -28 167t28 167l-194 194q-90 -171 -90 -361t90 -361zM896 -128q190 0 361 90l-194 194q-82 -28 -167 -28t-167 28l-194 -194q171 -90 361 -90zM896 256q159 0 271.5 112.5t112.5 271.5t-112.5 271.5t-271.5 112.5t-271.5 -112.5t-112.5 -271.5t112.5 -271.5 t271.5 -112.5zM1380 473l194 -194q90 171 90 361t-90 361l-194 -194q28 -82 28 -167t-28 -167z" />
<glyph unicode="&#xf1ce;" horiz-adv-x="1792" d="M1792 640q0 -182 -71 -348t-191 -286t-286 -191t-348 -71t-348 71t-286 191t-191 286t-71 348q0 222 101 414.5t276.5 317t390.5 155.5v-260q-221 -45 -366.5 -221t-145.5 -406q0 -130 51 -248.5t136.5 -204t204 -136.5t248.5 -51t248.5 51t204 136.5t136.5 204t51 248.5 q0 230 -145.5 406t-366.5 221v260q215 -31 390.5 -155.5t276.5 -317t101 -414.5z" />
<glyph unicode="&#xf1d0;" horiz-adv-x="1792" d="M19 662q8 217 116 406t305 318h5q0 -1 -1 -3q-8 -8 -28 -33.5t-52 -76.5t-60 -110.5t-44.5 -135.5t-14 -150.5t39 -157.5t108.5 -154q50 -50 102 -69.5t90.5 -11.5t69.5 23.5t47 32.5l16 16q39 51 53 116.5t6.5 122.5t-21 107t-26.5 80l-14 29q-10 25 -30.5 49.5t-43 41 t-43.5 29.5t-35 19l-13 6l104 115q39 -17 78 -52t59 -61l19 -27q1 48 -18.5 103.5t-40.5 87.5l-20 31l161 183l160 -181q-33 -46 -52.5 -102.5t-22.5 -90.5l-4 -33q22 37 61.5 72.5t67.5 52.5l28 17l103 -115q-44 -14 -85 -50t-60 -65l-19 -29q-31 -56 -48 -133.5t-7 -170 t57 -156.5q33 -45 77.5 -60.5t85 -5.5t76 26.5t57.5 33.5l21 16q60 53 96.5 115t48.5 121.5t10 121.5t-18 118t-37 107.5t-45.5 93t-45 72t-34.5 47.5l-13 17q-14 13 -7 13l10 -3q40 -29 62.5 -46t62 -50t64 -58t58.5 -65t55.5 -77t45.5 -88t38 -103t23.5 -117t10.5 -136 q3 -259 -108 -465t-312 -321t-456 -115q-185 0 -351 74t-283.5 198t-184 293t-60.5 353z" />
<glyph unicode="&#xf1d1;" horiz-adv-x="1792" d="M874 -102v-66q-208 6 -385 109.5t-283 275.5l58 34q29 -49 73 -99l65 57q148 -168 368 -212l-17 -86q65 -12 121 -13zM276 428l-83 -28q22 -60 49 -112l-57 -33q-98 180 -98 385t98 385l57 -33q-30 -56 -49 -112l82 -28q-35 -100 -35 -212q0 -109 36 -212zM1528 251 l58 -34q-106 -172 -283 -275.5t-385 -109.5v66q56 1 121 13l-17 86q220 44 368 212l65 -57q44 50 73 99zM1377 805l-233 -80q14 -42 14 -85t-14 -85l232 -80q-31 -92 -98 -169l-185 162q-57 -67 -147 -85l48 -241q-52 -10 -98 -10t-98 10l48 241q-90 18 -147 85l-185 -162 q-67 77 -98 169l232 80q-14 42 -14 85t14 85l-233 80q33 93 99 169l185 -162q59 68 147 86l-48 240q44 10 98 10t98 -10l-48 -240q88 -18 147 -86l185 162q66 -76 99 -169zM874 1448v-66q-65 -2 -121 -13l17 -86q-220 -42 -368 -211l-65 56q-38 -42 -73 -98l-57 33 q106 172 282 275.5t385 109.5zM1705 640q0 -205 -98 -385l-57 33q27 52 49 112l-83 28q36 103 36 212q0 112 -35 212l82 28q-19 56 -49 112l57 33q98 -180 98 -385zM1585 1063l-57 -33q-35 56 -73 98l-65 -56q-148 169 -368 211l17 86q-56 11 -121 13v66q209 -6 385 -109.5 t282 -275.5zM1748 640q0 173 -67.5 331t-181.5 272t-272 181.5t-331 67.5t-331 -67.5t-272 -181.5t-181.5 -272t-67.5 -331t67.5 -331t181.5 -272t272 -181.5t331 -67.5t331 67.5t272 181.5t181.5 272t67.5 331zM1792 640q0 -182 -71 -348t-191 -286t-286 -191t-348 -71 t-348 71t-286 191t-191 286t-71 348t71 348t191 286t286 191t348 71t348 -71t286 -191t191 -286t71 -348z" />
<glyph unicode="&#xf1d2;" d="M582 228q0 -66 -93 -66q-107 0 -107 63q0 64 98 64q102 0 102 -61zM546 694q0 -85 -74 -85q-77 0 -77 84q0 90 77 90q36 0 55 -25.5t19 -63.5zM712 769v125q-78 -29 -135 -29q-50 29 -110 29q-86 0 -145 -57t-59 -143q0 -50 29.5 -102t73.5 -67v-3q-38 -17 -38 -85 q0 -53 41 -77v-3q-113 -37 -113 -139q0 -45 20 -78.5t54 -51t72 -25.5t81 -8q224 0 224 188q0 67 -48 99t-126 46q-27 5 -51.5 20.5t-24.5 39.5q0 44 49 52q77 15 122 70t45 134q0 24 -10 52q37 9 49 13zM771 350h137q-2 27 -2 82v387q0 46 2 69h-137q3 -23 3 -71v-392 q0 -50 -3 -75zM1280 366v121q-30 -21 -68 -21q-53 0 -53 82v225h52q9 0 26.5 -1t26.5 -1v117h-105q0 82 3 102h-140q4 -24 4 -55v-47h-60v-117q36 3 37 3q3 0 11 -0.5t12 -0.5v-2h-2v-217q0 -37 2.5 -64t11.5 -56.5t24.5 -48.5t43.5 -31t66 -12q64 0 108 24zM924 1072 q0 36 -24 63.5t-60 27.5t-60.5 -27t-24.5 -64q0 -36 25 -62.5t60 -26.5t59.5 27t24.5 62zM1536 1120v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf1d3;" horiz-adv-x="1792" d="M595 22q0 100 -165 100q-158 0 -158 -104q0 -101 172 -101q151 0 151 105zM536 777q0 61 -30 102t-89 41q-124 0 -124 -145q0 -135 124 -135q119 0 119 137zM805 1101v-202q-36 -12 -79 -22q16 -43 16 -84q0 -127 -73 -216.5t-197 -112.5q-40 -8 -59.5 -27t-19.5 -58 q0 -31 22.5 -51.5t58 -32t78.5 -22t86 -25.5t78.5 -37.5t58 -64t22.5 -98.5q0 -304 -363 -304q-69 0 -130 12.5t-116 41t-87.5 82t-32.5 127.5q0 165 182 225v4q-67 41 -67 126q0 109 63 137v4q-72 24 -119.5 108.5t-47.5 165.5q0 139 95 231.5t235 92.5q96 0 178 -47 q98 0 218 47zM1123 220h-222q4 45 4 134v609q0 94 -4 128h222q-4 -33 -4 -124v-613q0 -89 4 -134zM1724 442v-196q-71 -39 -174 -39q-62 0 -107 20t-70 50t-39.5 78t-18.5 92t-4 103v351h2v4q-7 0 -19 1t-18 1q-21 0 -59 -6v190h96v76q0 54 -6 89h227q-6 -41 -6 -165h171 v-190q-15 0 -43.5 2t-42.5 2h-85v-365q0 -131 87 -131q61 0 109 33zM1148 1389q0 -58 -39 -101.5t-96 -43.5q-58 0 -98 43.5t-40 101.5q0 59 39.5 103t98.5 44q58 0 96.5 -44.5t38.5 -102.5z" />
<glyph unicode="&#xf1d4;" d="M825 547l343 588h-150q-21 -39 -63.5 -118.5t-68 -128.5t-59.5 -118.5t-60 -128.5h-3q-21 48 -44.5 97t-52 105.5t-46.5 92t-54 104.5t-49 95h-150l323 -589v-435h134v436zM1536 1120v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960 q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf1d5;" horiz-adv-x="1280" d="M842 964q0 -80 -57 -136.5t-136 -56.5q-60 0 -111 35q-62 -67 -115 -146q-247 -371 -202 -859q1 -22 -12.5 -38.5t-34.5 -18.5h-5q-20 0 -35 13.5t-17 33.5q-14 126 -3.5 247.5t29.5 217t54 186t69 155.5t74 125q61 90 132 165q-16 35 -16 77q0 80 56.5 136.5t136.5 56.5 t136.5 -56.5t56.5 -136.5zM1223 953q0 -158 -78 -292t-212.5 -212t-292.5 -78q-64 0 -131 14q-21 5 -32.5 23.5t-6.5 39.5q5 20 23 31.5t39 7.5q51 -13 108 -13q97 0 186 38t153 102t102 153t38 186t-38 186t-102 153t-153 102t-186 38t-186 -38t-153 -102t-102 -153 t-38 -186q0 -114 52 -218q10 -20 3.5 -40t-25.5 -30t-39.5 -3t-30.5 26q-64 123 -64 265q0 119 46.5 227t124.5 186t186 124t226 46q158 0 292.5 -78t212.5 -212.5t78 -292.5z" />
<glyph unicode="&#xf1d6;" horiz-adv-x="1792" d="M270 730q-8 19 -8 52q0 20 11 49t24 45q-1 22 7.5 53t22.5 43q0 139 92.5 288.5t217.5 209.5q139 66 324 66q133 0 266 -55q49 -21 90 -48t71 -56t55 -68t42 -74t32.5 -84.5t25.5 -89.5t22 -98l1 -5q55 -83 55 -150q0 -14 -9 -40t-9 -38q0 -1 1.5 -3.5t3.5 -5t2 -3.5 q77 -114 120.5 -214.5t43.5 -208.5q0 -43 -19.5 -100t-55.5 -57q-9 0 -19.5 7.5t-19 17.5t-19 26t-16 26.5t-13.5 26t-9 17.5q-1 1 -3 1l-5 -4q-59 -154 -132 -223q20 -20 61.5 -38.5t69 -41.5t35.5 -65q-2 -4 -4 -16t-7 -18q-64 -97 -302 -97q-53 0 -110.5 9t-98 20 t-104.5 30q-15 5 -23 7q-14 4 -46 4.5t-40 1.5q-41 -45 -127.5 -65t-168.5 -20q-35 0 -69 1.5t-93 9t-101 20.5t-74.5 40t-32.5 64q0 40 10 59.5t41 48.5q11 2 40.5 13t49.5 12q4 0 14 2q2 2 2 4l-2 3q-48 11 -108 105.5t-73 156.5l-5 3q-4 0 -12 -20q-18 -41 -54.5 -74.5 t-77.5 -37.5h-1q-4 0 -6 4.5t-5 5.5q-23 54 -23 100q0 275 252 466z" />
<glyph unicode="&#xf1d7;" horiz-adv-x="2048" d="M580 1075q0 41 -25 66t-66 25q-43 0 -76 -25.5t-33 -65.5q0 -39 33 -64.5t76 -25.5q41 0 66 24.5t25 65.5zM1323 568q0 28 -25.5 50t-65.5 22q-27 0 -49.5 -22.5t-22.5 -49.5q0 -28 22.5 -50.5t49.5 -22.5q40 0 65.5 22t25.5 51zM1087 1075q0 41 -24.5 66t-65.5 25 q-43 0 -76 -25.5t-33 -65.5q0 -39 33 -64.5t76 -25.5q41 0 65.5 24.5t24.5 65.5zM1722 568q0 28 -26 50t-65 22q-27 0 -49.5 -22.5t-22.5 -49.5q0 -28 22.5 -50.5t49.5 -22.5q39 0 65 22t26 51zM1456 965q-31 4 -70 4q-169 0 -311 -77t-223.5 -208.5t-81.5 -287.5 q0 -78 23 -152q-35 -3 -68 -3q-26 0 -50 1.5t-55 6.5t-44.5 7t-54.5 10.5t-50 10.5l-253 -127l72 218q-290 203 -290 490q0 169 97.5 311t264 223.5t363.5 81.5q176 0 332.5 -66t262 -182.5t136.5 -260.5zM2048 404q0 -117 -68.5 -223.5t-185.5 -193.5l55 -181l-199 109 q-150 -37 -218 -37q-169 0 -311 70.5t-223.5 191.5t-81.5 264t81.5 264t223.5 191.5t311 70.5q161 0 303 -70.5t227.5 -192t85.5 -263.5z" />
<glyph unicode="&#xf1d8;" horiz-adv-x="1792" d="M1764 1525q33 -24 27 -64l-256 -1536q-5 -29 -32 -45q-14 -8 -31 -8q-11 0 -24 5l-453 185l-242 -295q-18 -23 -49 -23q-13 0 -22 4q-19 7 -30.5 23.5t-11.5 36.5v349l864 1059l-1069 -925l-395 162q-37 14 -40 55q-2 40 32 59l1664 960q15 9 32 9q20 0 36 -11z" />
<glyph unicode="&#xf1d9;" horiz-adv-x="1792" d="M1764 1525q33 -24 27 -64l-256 -1536q-5 -29 -32 -45q-14 -8 -31 -8q-11 0 -24 5l-527 215l-298 -327q-18 -21 -47 -21q-14 0 -23 4q-19 7 -30 23.5t-11 36.5v452l-472 193q-37 14 -40 55q-3 39 32 59l1664 960q35 21 68 -2zM1422 26l221 1323l-1434 -827l336 -137 l863 639l-478 -797z" />
<glyph unicode="&#xf1da;" d="M1536 640q0 -156 -61 -298t-164 -245t-245 -164t-298 -61q-172 0 -327 72.5t-264 204.5q-7 10 -6.5 22.5t8.5 20.5l137 138q10 9 25 9q16 -2 23 -12q73 -95 179 -147t225 -52q104 0 198.5 40.5t163.5 109.5t109.5 163.5t40.5 198.5t-40.5 198.5t-109.5 163.5 t-163.5 109.5t-198.5 40.5q-98 0 -188 -35.5t-160 -101.5l137 -138q31 -30 14 -69q-17 -40 -59 -40h-448q-26 0 -45 19t-19 45v448q0 42 40 59q39 17 69 -14l130 -129q107 101 244.5 156.5t284.5 55.5q156 0 298 -61t245 -164t164 -245t61 -298zM896 928v-448q0 -14 -9 -23 t-23 -9h-320q-14 0 -23 9t-9 23v64q0 14 9 23t23 9h224v352q0 14 9 23t23 9h64q14 0 23 -9t9 -23z" />
<glyph unicode="&#xf1db;" d="M768 1280q-130 0 -248.5 -51t-204 -136.5t-136.5 -204t-51 -248.5t51 -248.5t136.5 -204t204 -136.5t248.5 -51t248.5 51t204 136.5t136.5 204t51 248.5t-51 248.5t-136.5 204t-204 136.5t-248.5 51zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103 t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf1dc;" horiz-adv-x="1792" d="M1682 -128q-44 0 -132.5 3.5t-133.5 3.5q-44 0 -132 -3.5t-132 -3.5q-24 0 -37 20.5t-13 45.5q0 31 17 46t39 17t51 7t45 15q33 21 33 140l-1 391q0 21 -1 31q-13 4 -50 4h-675q-38 0 -51 -4q-1 -10 -1 -31l-1 -371q0 -142 37 -164q16 -10 48 -13t57 -3.5t45 -15 t20 -45.5q0 -26 -12.5 -48t-36.5 -22q-47 0 -139.5 3.5t-138.5 3.5q-43 0 -128 -3.5t-127 -3.5q-23 0 -35.5 21t-12.5 45q0 30 15.5 45t36 17.5t47.5 7.5t42 15q33 23 33 143l-1 57v813q0 3 0.5 26t0 36.5t-1.5 38.5t-3.5 42t-6.5 36.5t-11 31.5t-16 18q-15 10 -45 12t-53 2 t-41 14t-18 45q0 26 12 48t36 22q46 0 138.5 -3.5t138.5 -3.5q42 0 126.5 3.5t126.5 3.5q25 0 37.5 -22t12.5 -48q0 -30 -17 -43.5t-38.5 -14.5t-49.5 -4t-43 -13q-35 -21 -35 -160l1 -320q0 -21 1 -32q13 -3 39 -3h699q25 0 38 3q1 11 1 32l1 320q0 139 -35 160 q-18 11 -58.5 12.5t-66 13t-25.5 49.5q0 26 12.5 48t37.5 22q44 0 132 -3.5t132 -3.5q43 0 129 3.5t129 3.5q25 0 37.5 -22t12.5 -48q0 -30 -17.5 -44t-40 -14.5t-51.5 -3t-44 -12.5q-35 -23 -35 -161l1 -943q0 -119 34 -140q16 -10 46 -13.5t53.5 -4.5t41.5 -15.5t18 -44.5 q0 -26 -12 -48t-36 -22z" />
<glyph unicode="&#xf1dd;" horiz-adv-x="1280" d="M1278 1347v-73q0 -29 -18.5 -61t-42.5 -32q-50 0 -54 -1q-26 -6 -32 -31q-3 -11 -3 -64v-1152q0 -25 -18 -43t-43 -18h-108q-25 0 -43 18t-18 43v1218h-143v-1218q0 -25 -17.5 -43t-43.5 -18h-108q-26 0 -43.5 18t-17.5 43v496q-147 12 -245 59q-126 58 -192 179 q-64 117 -64 259q0 166 88 286q88 118 209 159q111 37 417 37h479q25 0 43 -18t18 -43z" />
<glyph unicode="&#xf1de;" d="M352 128v-128h-352v128h352zM704 256q26 0 45 -19t19 -45v-256q0 -26 -19 -45t-45 -19h-256q-26 0 -45 19t-19 45v256q0 26 19 45t45 19h256zM864 640v-128h-864v128h864zM224 1152v-128h-224v128h224zM1536 128v-128h-736v128h736zM576 1280q26 0 45 -19t19 -45v-256 q0 -26 -19 -45t-45 -19h-256q-26 0 -45 19t-19 45v256q0 26 19 45t45 19h256zM1216 768q26 0 45 -19t19 -45v-256q0 -26 -19 -45t-45 -19h-256q-26 0 -45 19t-19 45v256q0 26 19 45t45 19h256zM1536 640v-128h-224v128h224zM1536 1152v-128h-864v128h864z" />
<glyph unicode="&#xf1e0;" d="M1216 512q133 0 226.5 -93.5t93.5 -226.5t-93.5 -226.5t-226.5 -93.5t-226.5 93.5t-93.5 226.5q0 12 2 34l-360 180q-92 -86 -218 -86q-133 0 -226.5 93.5t-93.5 226.5t93.5 226.5t226.5 93.5q126 0 218 -86l360 180q-2 22 -2 34q0 133 93.5 226.5t226.5 93.5 t226.5 -93.5t93.5 -226.5t-93.5 -226.5t-226.5 -93.5q-126 0 -218 86l-360 -180q2 -22 2 -34t-2 -34l360 -180q92 86 218 86z" />
<glyph unicode="&#xf1e1;" d="M1280 341q0 88 -62.5 151t-150.5 63q-84 0 -145 -58l-241 120q2 16 2 23t-2 23l241 120q61 -58 145 -58q88 0 150.5 63t62.5 151t-62.5 150.5t-150.5 62.5t-151 -62.5t-63 -150.5q0 -7 2 -23l-241 -120q-62 57 -145 57q-88 0 -150.5 -62.5t-62.5 -150.5t62.5 -150.5 t150.5 -62.5q83 0 145 57l241 -120q-2 -16 -2 -23q0 -88 63 -150.5t151 -62.5t150.5 62.5t62.5 150.5zM1536 1120v-960q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf1e2;" horiz-adv-x="1792" d="M571 947q-10 25 -34 35t-49 0q-108 -44 -191 -127t-127 -191q-10 -25 0 -49t35 -34q13 -5 24 -5q42 0 60 40q34 84 98.5 148.5t148.5 98.5q25 11 35 35t0 49zM1513 1303l46 -46l-244 -243l68 -68q19 -19 19 -45.5t-19 -45.5l-64 -64q89 -161 89 -343q0 -143 -55.5 -273.5 t-150 -225t-225 -150t-273.5 -55.5t-273.5 55.5t-225 150t-150 225t-55.5 273.5t55.5 273.5t150 225t225 150t273.5 55.5q182 0 343 -89l64 64q19 19 45.5 19t45.5 -19l68 -68zM1521 1359q-10 -10 -22 -10q-13 0 -23 10l-91 90q-9 10 -9 23t9 23q10 9 23 9t23 -9l90 -91 q10 -9 10 -22.5t-10 -22.5zM1751 1129q-11 -9 -23 -9t-23 9l-90 91q-10 9 -10 22.5t10 22.5q9 10 22.5 10t22.5 -10l91 -90q9 -10 9 -23t-9 -23zM1792 1312q0 -14 -9 -23t-23 -9h-96q-14 0 -23 9t-9 23t9 23t23 9h96q14 0 23 -9t9 -23zM1600 1504v-96q0 -14 -9 -23t-23 -9 t-23 9t-9 23v96q0 14 9 23t23 9t23 -9t9 -23zM1751 1449l-91 -90q-10 -10 -22 -10q-13 0 -23 10q-10 9 -10 22.5t10 22.5l90 91q10 9 23 9t23 -9q9 -10 9 -23t-9 -23z" />
<glyph unicode="&#xf1e3;" horiz-adv-x="1792" d="M609 720l287 208l287 -208l-109 -336h-355zM896 1536q182 0 348 -71t286 -191t191 -286t71 -348t-71 -348t-191 -286t-286 -191t-348 -71t-348 71t-286 191t-191 286t-71 348t71 348t191 286t286 191t348 71zM1515 186q149 203 149 454v3l-102 -89l-240 224l63 323 l134 -12q-150 206 -389 282l53 -124l-287 -159l-287 159l53 124q-239 -76 -389 -282l135 12l62 -323l-240 -224l-102 89v-3q0 -251 149 -454l30 132l326 -40l139 -298l-116 -69q117 -39 240 -39t240 39l-116 69l139 298l326 40z" />
<glyph unicode="&#xf1e4;" horiz-adv-x="1792" d="M448 224v-192q0 -14 -9 -23t-23 -9h-192q-14 0 -23 9t-9 23v192q0 14 9 23t23 9h192q14 0 23 -9t9 -23zM256 608v-192q0 -14 -9 -23t-23 -9h-192q-14 0 -23 9t-9 23v192q0 14 9 23t23 9h192q14 0 23 -9t9 -23zM832 224v-192q0 -14 -9 -23t-23 -9h-192q-14 0 -23 9t-9 23 v192q0 14 9 23t23 9h192q14 0 23 -9t9 -23zM640 608v-192q0 -14 -9 -23t-23 -9h-192q-14 0 -23 9t-9 23v192q0 14 9 23t23 9h192q14 0 23 -9t9 -23zM66 768q-28 0 -47 19t-19 46v129h514v-129q0 -27 -19 -46t-46 -19h-383zM1216 224v-192q0 -14 -9 -23t-23 -9h-192 q-14 0 -23 9t-9 23v192q0 14 9 23t23 9h192q14 0 23 -9t9 -23zM1024 608v-192q0 -14 -9 -23t-23 -9h-192q-14 0 -23 9t-9 23v192q0 14 9 23t23 9h192q14 0 23 -9t9 -23zM1600 224v-192q0 -14 -9 -23t-23 -9h-192q-14 0 -23 9t-9 23v192q0 14 9 23t23 9h192q14 0 23 -9t9 -23 zM1408 608v-192q0 -14 -9 -23t-23 -9h-192q-14 0 -23 9t-9 23v192q0 14 9 23t23 9h192q14 0 23 -9t9 -23zM1792 1016v-13h-514v10q0 104 -382 102q-382 -1 -382 -102v-10h-514v13q0 17 8.5 43t34 64t65.5 75.5t110.5 76t160 67.5t224 47.5t293.5 18.5t293 -18.5t224 -47.5 t160.5 -67.5t110.5 -76t65.5 -75.5t34 -64t8.5 -43zM1792 608v-192q0 -14 -9 -23t-23 -9h-192q-14 0 -23 9t-9 23v192q0 14 9 23t23 9h192q14 0 23 -9t9 -23zM1792 962v-129q0 -27 -19 -46t-46 -19h-384q-27 0 -46 19t-19 46v129h514z" />
<glyph unicode="&#xf1e5;" horiz-adv-x="1792" d="M704 1216v-768q0 -26 -19 -45t-45 -19v-576q0 -26 -19 -45t-45 -19h-512q-26 0 -45 19t-19 45v512l249 873q7 23 31 23h424zM1024 1216v-704h-256v704h256zM1792 320v-512q0 -26 -19 -45t-45 -19h-512q-26 0 -45 19t-19 45v576q-26 0 -45 19t-19 45v768h424q24 0 31 -23z M736 1504v-224h-352v224q0 14 9 23t23 9h288q14 0 23 -9t9 -23zM1408 1504v-224h-352v224q0 14 9 23t23 9h288q14 0 23 -9t9 -23z" />
<glyph unicode="&#xf1e6;" horiz-adv-x="1792" d="M1755 1083q37 -37 37 -90t-37 -91l-401 -400l150 -150l-160 -160q-163 -163 -389.5 -186.5t-411.5 100.5l-362 -362h-181v181l362 362q-124 185 -100.5 411.5t186.5 389.5l160 160l150 -150l400 401q38 37 91 37t90 -37t37 -90.5t-37 -90.5l-400 -401l234 -234l401 400 q38 37 91 37t90 -37z" />
<glyph unicode="&#xf1e7;" horiz-adv-x="1792" d="M873 796q0 -83 -63.5 -142.5t-152.5 -59.5t-152.5 59.5t-63.5 142.5q0 84 63.5 143t152.5 59t152.5 -59t63.5 -143zM1375 796q0 -83 -63 -142.5t-153 -59.5q-89 0 -152.5 59.5t-63.5 142.5q0 84 63.5 143t152.5 59q90 0 153 -59t63 -143zM1600 616v667q0 87 -32 123.5 t-111 36.5h-1112q-83 0 -112.5 -34t-29.5 -126v-673q43 -23 88.5 -40t81 -28t81 -18.5t71 -11t70 -4t58.5 -0.5t56.5 2t44.5 2q68 1 95 -27q6 -6 10 -9q26 -25 61 -51q7 91 118 87q5 0 36.5 -1.5t43 -2t45.5 -1t53 1t54.5 4.5t61 8.5t62 13.5t67 19.5t67.5 27t72 34.5z M1763 621q-121 -149 -372 -252q84 -285 -23 -465q-66 -113 -183 -148q-104 -32 -182 15q-86 51 -82 164l-1 326v1q-8 2 -24.5 6t-23.5 5l-1 -338q4 -114 -83 -164q-79 -47 -183 -15q-117 36 -182 150q-105 180 -22 463q-251 103 -372 252q-25 37 -4 63t60 -1q3 -2 11 -7 t11 -8v694q0 72 47 123t114 51h1257q67 0 114 -51t47 -123v-694l21 15q39 27 60 1t-4 -63z" />
<glyph unicode="&#xf1e8;" horiz-adv-x="1792" d="M896 1102v-434h-145v434h145zM1294 1102v-434h-145v434h145zM1294 342l253 254v795h-1194v-1049h326v-217l217 217h398zM1692 1536v-1013l-434 -434h-326l-217 -217h-217v217h-398v1158l109 289h1483z" />
<glyph unicode="&#xf1e9;" d="M773 217v-127q-1 -292 -6 -305q-12 -32 -51 -40q-54 -9 -181.5 38t-162.5 89q-13 15 -17 36q-1 12 4 26q4 10 34 47t181 216q1 0 60 70q15 19 39.5 24.5t49.5 -3.5q24 -10 37.5 -29t12.5 -42zM624 468q-3 -55 -52 -70l-120 -39q-275 -88 -292 -88q-35 2 -54 36 q-12 25 -17 75q-8 76 1 166.5t30 124.5t56 32q13 0 202 -77q70 -29 115 -47l84 -34q23 -9 35.5 -30.5t11.5 -48.5zM1450 171q-7 -54 -91.5 -161t-135.5 -127q-37 -14 -63 7q-14 10 -184 287l-47 77q-14 21 -11.5 46t19.5 46q35 43 83 26q1 -1 119 -40q203 -66 242 -79.5 t47 -20.5q28 -22 22 -61zM778 803q5 -102 -54 -122q-58 -17 -114 71l-378 598q-8 35 19 62q41 43 207.5 89.5t224.5 31.5q40 -10 49 -45q3 -18 22 -305.5t24 -379.5zM1440 695q3 -39 -26 -59q-15 -10 -329 -86q-67 -15 -91 -23l1 2q-23 -6 -46 4t-37 32q-30 47 0 87 q1 1 75 102q125 171 150 204t34 39q28 19 65 2q48 -23 123 -133.5t81 -167.5v-3z" />
<glyph unicode="&#xf1ea;" horiz-adv-x="2048" d="M1024 1024h-384v-384h384v384zM1152 384v-128h-640v128h640zM1152 1152v-640h-640v640h640zM1792 384v-128h-512v128h512zM1792 640v-128h-512v128h512zM1792 896v-128h-512v128h512zM1792 1152v-128h-512v128h512zM256 192v960h-128v-960q0 -26 19 -45t45 -19t45 19 t19 45zM1920 192v1088h-1536v-1088q0 -33 -11 -64h1483q26 0 45 19t19 45zM2048 1408v-1216q0 -80 -56 -136t-136 -56h-1664q-80 0 -136 56t-56 136v1088h256v128h1792z" />
<glyph unicode="&#xf1eb;" horiz-adv-x="2048" d="M1024 13q-20 0 -93 73.5t-73 93.5q0 32 62.5 54t103.5 22t103.5 -22t62.5 -54q0 -20 -73 -93.5t-93 -73.5zM1294 284q-2 0 -40 25t-101.5 50t-128.5 25t-128.5 -25t-101 -50t-40.5 -25q-18 0 -93.5 75t-75.5 93q0 13 10 23q78 77 196 121t233 44t233 -44t196 -121 q10 -10 10 -23q0 -18 -75.5 -93t-93.5 -75zM1567 556q-11 0 -23 8q-136 105 -252 154.5t-268 49.5q-85 0 -170.5 -22t-149 -53t-113.5 -62t-79 -53t-31 -22q-17 0 -92 75t-75 93q0 12 10 22q132 132 320 205t380 73t380 -73t320 -205q10 -10 10 -22q0 -18 -75 -93t-92 -75z M1838 827q-11 0 -22 9q-179 157 -371.5 236.5t-420.5 79.5t-420.5 -79.5t-371.5 -236.5q-11 -9 -22 -9q-17 0 -92.5 75t-75.5 93q0 13 10 23q187 186 445 288t527 102t527 -102t445 -288q10 -10 10 -23q0 -18 -75.5 -93t-92.5 -75z" />
<glyph unicode="&#xf1ec;" horiz-adv-x="1792" d="M384 0q0 53 -37.5 90.5t-90.5 37.5t-90.5 -37.5t-37.5 -90.5t37.5 -90.5t90.5 -37.5t90.5 37.5t37.5 90.5zM768 0q0 53 -37.5 90.5t-90.5 37.5t-90.5 -37.5t-37.5 -90.5t37.5 -90.5t90.5 -37.5t90.5 37.5t37.5 90.5zM384 384q0 53 -37.5 90.5t-90.5 37.5t-90.5 -37.5 t-37.5 -90.5t37.5 -90.5t90.5 -37.5t90.5 37.5t37.5 90.5zM1152 0q0 53 -37.5 90.5t-90.5 37.5t-90.5 -37.5t-37.5 -90.5t37.5 -90.5t90.5 -37.5t90.5 37.5t37.5 90.5zM768 384q0 53 -37.5 90.5t-90.5 37.5t-90.5 -37.5t-37.5 -90.5t37.5 -90.5t90.5 -37.5t90.5 37.5 t37.5 90.5zM384 768q0 53 -37.5 90.5t-90.5 37.5t-90.5 -37.5t-37.5 -90.5t37.5 -90.5t90.5 -37.5t90.5 37.5t37.5 90.5zM1152 384q0 53 -37.5 90.5t-90.5 37.5t-90.5 -37.5t-37.5 -90.5t37.5 -90.5t90.5 -37.5t90.5 37.5t37.5 90.5zM768 768q0 53 -37.5 90.5t-90.5 37.5 t-90.5 -37.5t-37.5 -90.5t37.5 -90.5t90.5 -37.5t90.5 37.5t37.5 90.5zM1536 0v384q0 52 -38 90t-90 38t-90 -38t-38 -90v-384q0 -52 38 -90t90 -38t90 38t38 90zM1152 768q0 53 -37.5 90.5t-90.5 37.5t-90.5 -37.5t-37.5 -90.5t37.5 -90.5t90.5 -37.5t90.5 37.5t37.5 90.5z M1536 1088v256q0 26 -19 45t-45 19h-1280q-26 0 -45 -19t-19 -45v-256q0 -26 19 -45t45 -19h1280q26 0 45 19t19 45zM1536 768q0 53 -37.5 90.5t-90.5 37.5t-90.5 -37.5t-37.5 -90.5t37.5 -90.5t90.5 -37.5t90.5 37.5t37.5 90.5zM1664 1408v-1536q0 -52 -38 -90t-90 -38 h-1408q-52 0 -90 38t-38 90v1536q0 52 38 90t90 38h1408q52 0 90 -38t38 -90z" />
<glyph unicode="&#xf1ed;" horiz-adv-x="1792" d="M1112 1090q0 159 -237 159h-70q-32 0 -59.5 -21.5t-34.5 -52.5l-63 -276q-2 -5 -2 -16q0 -24 17 -39.5t41 -15.5h53q69 0 128.5 13t112.5 41t83.5 81.5t30.5 126.5zM1716 938q0 -265 -220 -428q-219 -161 -612 -161h-61q-32 0 -59 -21.5t-34 -52.5l-73 -316 q-8 -36 -40.5 -61.5t-69.5 -25.5h-213q-31 0 -53 20t-22 51q0 10 13 65h151q34 0 64 23.5t38 56.5l73 316q8 33 37.5 57t63.5 24h61q390 0 607 160t217 421q0 129 -51 207q183 -92 183 -335zM1533 1123q0 -264 -221 -428q-218 -161 -612 -161h-60q-32 0 -59.5 -22t-34.5 -53 l-73 -315q-8 -36 -40 -61.5t-69 -25.5h-214q-31 0 -52.5 19.5t-21.5 51.5q0 8 2 20l300 1301q8 36 40.5 61.5t69.5 25.5h444q68 0 125 -4t120.5 -15t113.5 -30t96.5 -50.5t77.5 -74t49.5 -103.5t18.5 -136z" />
<glyph unicode="&#xf1ee;" horiz-adv-x="1792" d="M602 949q19 -61 31 -123.5t17 -141.5t-14 -159t-62 -145q-21 81 -67 157t-95.5 127t-99 90.5t-78.5 57.5t-33 19q-62 34 -81.5 100t14.5 128t101 81.5t129 -14.5q138 -83 238 -177zM927 1236q11 -25 20.5 -46t36.5 -100.5t42.5 -150.5t25.5 -179.5t0 -205.5t-47.5 -209.5 t-105.5 -208.5q-51 -72 -138 -72q-54 0 -98 31q-57 40 -69 109t28 127q60 85 81 195t13 199.5t-32 180.5t-39 128t-22 52q-31 63 -8.5 129.5t85.5 97.5q34 17 75 17q47 0 88.5 -25t63.5 -69zM1248 567q-17 -160 -72 -311q-17 131 -63 246q25 174 -5 361q-27 178 -94 342 q114 -90 212 -211q9 -37 15 -80q26 -179 7 -347zM1520 1440q9 -17 23.5 -49.5t43.5 -117.5t50.5 -178t34 -227.5t5 -269t-47 -300t-112.5 -323.5q-22 -48 -66 -75.5t-95 -27.5q-39 0 -74 16q-67 31 -92.5 100t4.5 136q58 126 90 257.5t37.5 239.5t-3.5 213.5t-26.5 180.5 t-38.5 138.5t-32.5 90t-15.5 32.5q-34 65 -11.5 135.5t87.5 104.5q37 20 81 20q49 0 91.5 -25.5t66.5 -70.5z" />
<glyph unicode="&#xf1f0;" horiz-adv-x="2304" d="M1975 546h-138q14 37 66 179l3 9q4 10 10 26t9 26l12 -55zM531 611l-58 295q-11 54 -75 54h-268l-2 -13q311 -79 403 -336zM710 960l-162 -438l-17 89q-26 70 -85 129.5t-131 88.5l135 -510h175l261 641h-176zM849 318h166l104 642h-166zM1617 944q-69 27 -149 27 q-123 0 -201 -59t-79 -153q-1 -102 145 -174q48 -23 67 -41t19 -39q0 -30 -30 -46t-69 -16q-86 0 -156 33l-22 11l-23 -144q74 -34 185 -34q130 -1 208.5 59t80.5 160q0 106 -140 174q-49 25 -71 42t-22 38q0 22 24.5 38.5t70.5 16.5q70 1 124 -24l15 -8zM2042 960h-128 q-65 0 -87 -54l-246 -588h174l35 96h212q5 -22 20 -96h154zM2304 1280v-1280q0 -52 -38 -90t-90 -38h-2048q-52 0 -90 38t-38 90v1280q0 52 38 90t90 38h2048q52 0 90 -38t38 -90z" />
<glyph unicode="&#xf1f1;" horiz-adv-x="2304" d="M671 603h-13q-47 0 -47 -32q0 -22 20 -22q17 0 28 15t12 39zM1066 639h62v3q1 4 0.5 6.5t-1 7t-2 8t-4.5 6.5t-7.5 5t-11.5 2q-28 0 -36 -38zM1606 603h-12q-48 0 -48 -32q0 -22 20 -22q17 0 28 15t12 39zM1925 629q0 41 -30 41q-19 0 -31 -20t-12 -51q0 -42 28 -42 q20 0 32.5 20t12.5 52zM480 770h87l-44 -262h-56l32 201l-71 -201h-39l-4 200l-34 -200h-53l44 262h81l2 -163zM733 663q0 -6 -4 -42q-16 -101 -17 -113h-47l1 22q-20 -26 -58 -26q-23 0 -37.5 16t-14.5 42q0 39 26 60.5t73 21.5q14 0 23 -1q0 3 0.5 5.5t1 4.5t0.5 3 q0 20 -36 20q-29 0 -59 -10q0 4 7 48q38 11 67 11q74 0 74 -62zM889 721l-8 -49q-22 3 -41 3q-27 0 -27 -17q0 -8 4.5 -12t21.5 -11q40 -19 40 -60q0 -72 -87 -71q-34 0 -58 6q0 2 7 49q29 -8 51 -8q32 0 32 19q0 7 -4.5 11.5t-21.5 12.5q-43 20 -43 59q0 72 84 72 q30 0 50 -4zM977 721h28l-7 -52h-29q-2 -17 -6.5 -40.5t-7 -38.5t-2.5 -18q0 -16 19 -16q8 0 16 2l-8 -47q-21 -7 -40 -7q-43 0 -45 47q0 12 8 56q3 20 25 146h55zM1180 648q0 -23 -7 -52h-111q-3 -22 10 -33t38 -11q30 0 58 14l-9 -54q-30 -8 -57 -8q-95 0 -95 95 q0 55 27.5 90.5t69.5 35.5q35 0 55.5 -21t20.5 -56zM1319 722q-13 -23 -22 -62q-22 2 -31 -24t-25 -128h-56l3 14q22 130 29 199h51l-3 -33q14 21 25.5 29.5t28.5 4.5zM1506 763l-9 -57q-28 14 -50 14q-31 0 -51 -27.5t-20 -70.5q0 -30 13.5 -47t38.5 -17q21 0 48 13 l-10 -59q-28 -8 -50 -8q-45 0 -71.5 30.5t-26.5 82.5q0 70 35.5 114.5t91.5 44.5q26 0 61 -13zM1668 663q0 -18 -4 -42q-13 -79 -17 -113h-46l1 22q-20 -26 -59 -26q-23 0 -37 16t-14 42q0 39 25.5 60.5t72.5 21.5q15 0 23 -1q2 7 2 13q0 20 -36 20q-29 0 -59 -10q0 4 8 48 q38 11 67 11q73 0 73 -62zM1809 722q-14 -24 -21 -62q-23 2 -31.5 -23t-25.5 -129h-56l3 14q19 104 29 199h52q0 -11 -4 -33q15 21 26.5 29.5t27.5 4.5zM1950 770h56l-43 -262h-53l3 19q-23 -23 -52 -23q-31 0 -49.5 24t-18.5 64q0 53 27.5 92t64.5 39q31 0 53 -29z M2061 640q0 148 -72.5 273t-198 198t-273.5 73q-181 0 -328 -110q127 -116 171 -284h-50q-44 150 -158 253q-114 -103 -158 -253h-50q44 168 171 284q-147 110 -328 110q-148 0 -273.5 -73t-198 -198t-72.5 -273t72.5 -273t198 -198t273.5 -73q181 0 328 110 q-120 111 -165 264h50q46 -138 152 -233q106 95 152 233h50q-45 -153 -165 -264q147 -110 328 -110q148 0 273.5 73t198 198t72.5 273zM2304 1280v-1280q0 -52 -38 -90t-90 -38h-2048q-52 0 -90 38t-38 90v1280q0 52 38 90t90 38h2048q52 0 90 -38t38 -90z" />
<glyph unicode="&#xf1f2;" horiz-adv-x="2304" d="M313 759q0 -51 -36 -84q-29 -26 -89 -26h-17v220h17q61 0 89 -27q36 -31 36 -83zM2089 824q0 -52 -64 -52h-19v101h20q63 0 63 -49zM380 759q0 74 -50 120.5t-129 46.5h-95v-333h95q74 0 119 38q60 51 60 128zM410 593h65v333h-65v-333zM730 694q0 40 -20.5 62t-75.5 42 q-29 10 -39.5 19t-10.5 23q0 16 13.5 26.5t34.5 10.5q29 0 53 -27l34 44q-41 37 -98 37q-44 0 -74 -27.5t-30 -67.5q0 -35 18 -55.5t64 -36.5q37 -13 45 -19q19 -12 19 -34q0 -20 -14 -33.5t-36 -13.5q-48 0 -71 44l-42 -40q44 -64 115 -64q51 0 83 30.5t32 79.5zM1008 604 v77q-37 -37 -78 -37q-49 0 -80.5 32.5t-31.5 82.5q0 48 31.5 81.5t77.5 33.5q43 0 81 -38v77q-40 20 -80 20q-74 0 -125.5 -50.5t-51.5 -123.5t51 -123.5t125 -50.5q42 0 81 19zM2240 0v527q-65 -40 -144.5 -84t-237.5 -117t-329.5 -137.5t-417.5 -134.5t-504 -118h1569 q26 0 45 19t19 45zM1389 757q0 75 -53 128t-128 53t-128 -53t-53 -128t53 -128t128 -53t128 53t53 128zM1541 584l144 342h-71l-90 -224l-89 224h-71l142 -342h35zM1714 593h184v56h-119v90h115v56h-115v74h119v57h-184v-333zM2105 593h80l-105 140q76 16 76 94q0 47 -31 73 t-87 26h-97v-333h65v133h9zM2304 1274v-1268q0 -56 -38.5 -95t-93.5 -39h-2040q-55 0 -93.5 39t-38.5 95v1268q0 56 38.5 95t93.5 39h2040q55 0 93.5 -39t38.5 -95z" />
<glyph unicode="&#xf1f3;" horiz-adv-x="2304" d="M119 854h89l-45 108zM740 328l74 79l-70 79h-163v-49h142v-55h-142v-54h159zM898 406l99 -110v217zM1186 453q0 33 -40 33h-84v-69h83q41 0 41 36zM1475 457q0 29 -42 29h-82v-61h81q43 0 43 32zM1197 923q0 29 -42 29h-82v-60h81q43 0 43 31zM1656 854h89l-44 108z M699 1009v-271h-66v212l-94 -212h-57l-94 212v-212h-132l-25 60h-135l-25 -60h-70l116 271h96l110 -257v257h106l85 -184l77 184h108zM1255 453q0 -20 -5.5 -35t-14 -25t-22.5 -16.5t-26 -10t-31.5 -4.5t-31.5 -1t-32.5 0.5t-29.5 0.5v-91h-126l-80 90l-83 -90h-256v271h260 l80 -89l82 89h207q109 0 109 -89zM964 794v-56h-217v271h217v-57h-152v-49h148v-55h-148v-54h152zM2304 235v-229q0 -55 -38.5 -94.5t-93.5 -39.5h-2040q-55 0 -93.5 39.5t-38.5 94.5v678h111l25 61h55l25 -61h218v46l19 -46h113l20 47v-47h541v99l10 1q10 0 10 -14v-86h279 v23q23 -12 55 -18t52.5 -6.5t63 0.5t51.5 1l25 61h56l25 -61h227v58l34 -58h182v378h-180v-44l-25 44h-185v-44l-23 44h-249q-69 0 -109 -22v22h-172v-22q-24 22 -73 22h-628l-43 -97l-43 97h-198v-44l-22 44h-169l-78 -179v391q0 55 38.5 94.5t93.5 39.5h2040 q55 0 93.5 -39.5t38.5 -94.5v-678h-120q-51 0 -81 -22v22h-177q-55 0 -78 -22v22h-316v-22q-31 22 -87 22h-209v-22q-23 22 -91 22h-234l-54 -58l-50 58h-349v-378h343l55 59l52 -59h211v89h21q59 0 90 13v-102h174v99h8q8 0 10 -2t2 -10v-87h529q57 0 88 24v-24h168 q60 0 95 17zM1546 469q0 -23 -12 -43t-34 -29q25 -9 34 -26t9 -46v-54h-65v45q0 33 -12 43.5t-46 10.5h-69v-99h-65v271h154q48 0 77 -15t29 -58zM1269 936q0 -24 -12.5 -44t-33.5 -29q26 -9 34.5 -25.5t8.5 -46.5v-53h-65q0 9 0.5 26.5t0 25t-3 18.5t-8.5 16t-17.5 8.5 t-29.5 3.5h-70v-98h-64v271l153 -1q49 0 78 -14.5t29 -57.5zM1798 327v-56h-216v271h216v-56h-151v-49h148v-55h-148v-54zM1372 1009v-271h-66v271h66zM2065 357q0 -86 -102 -86h-126v58h126q34 0 34 25q0 16 -17 21t-41.5 5t-49.5 3.5t-42 22.5t-17 55q0 39 26 60t66 21 h130v-57h-119q-36 0 -36 -25q0 -16 17.5 -20.5t42 -4t49 -2.5t42 -21.5t17.5 -54.5zM2304 407v-101q-24 -35 -88 -35h-125v58h125q33 0 33 25q0 13 -12.5 19t-31 5.5t-40 2t-40 8t-31 24t-12.5 48.5q0 39 26.5 60t66.5 21h129v-57h-118q-36 0 -36 -25q0 -20 29 -22t68.5 -5 t56.5 -26zM2139 1008v-270h-92l-122 203v-203h-132l-26 60h-134l-25 -60h-75q-129 0 -129 133q0 138 133 138h63v-59q-7 0 -28 1t-28.5 0.5t-23 -2t-21.5 -6.5t-14.5 -13.5t-11.5 -23t-3 -33.5q0 -38 13.5 -58t49.5 -20h29l92 213h97l109 -256v256h99l114 -188v188h66z" />
<glyph unicode="&#xf1f4;" horiz-adv-x="2304" d="M322 689h-15q-19 0 -19 18q0 28 19 85q5 15 15 19.5t28 4.5q77 0 77 -49q0 -41 -30.5 -59.5t-74.5 -18.5zM664 528q-47 0 -47 29q0 62 123 62l3 -3q-5 -88 -79 -88zM1438 687h-15q-19 0 -19 19q0 28 19 85q5 15 14.5 19t28.5 4q77 0 77 -49q0 -41 -30.5 -59.5 t-74.5 -18.5zM1780 527q-47 0 -47 30q0 62 123 62l3 -3q-5 -89 -79 -89zM373 894h-128q-8 0 -14.5 -4t-8.5 -7.5t-7 -12.5q-3 -7 -45 -190t-42 -192q0 -7 5.5 -12.5t13.5 -5.5h62q25 0 32.5 34.5l15 69t32.5 34.5q47 0 87.5 7.5t80.5 24.5t63.5 52.5t23.5 84.5 q0 36 -14.5 61t-41 36.5t-53.5 15.5t-62 4zM719 798q-38 0 -74 -6q-2 0 -8.5 -1t-9 -1.5l-7.5 -1.5t-7.5 -2t-6.5 -3t-6.5 -4t-5 -5t-4.5 -7t-4 -9q-9 -29 -9 -39t9 -10q5 0 21.5 5t19.5 6q30 8 58 8q74 0 74 -36q0 -11 -10 -14q-8 -2 -18 -3t-21.5 -1.5t-17.5 -1.5 q-38 -4 -64.5 -10t-56.5 -19.5t-45.5 -39t-15.5 -62.5q0 -38 26 -59.5t64 -21.5q24 0 45.5 6.5t33 13t38.5 23.5q-3 -7 -3 -15t5.5 -13.5t12.5 -5.5h56q1 1 7 3.5t7.5 3.5t5 3.5t5 5.5t2.5 8l45 194q4 13 4 30q0 81 -145 81zM1247 793h-74q-22 0 -39 -23q-5 -7 -29.5 -51 t-46.5 -81.5t-26 -38.5l-5 4q0 77 -27 166q-1 5 -3.5 8.5t-6 6.5t-6.5 5t-8.5 3t-8.5 1.5t-9.5 1t-9 0.5h-10h-8.5q-38 0 -38 -21l1 -5q5 -53 25 -151t25 -143q2 -16 2 -24q0 -19 -30.5 -61.5t-30.5 -58.5q0 -13 40 -13q61 0 76 25l245 415q10 20 10 26q0 9 -8 9zM1489 892 h-129q-18 0 -29 -23q-6 -13 -46.5 -191.5t-40.5 -190.5q0 -20 43 -20h7.5h9h9t9.5 1t8.5 2t8.5 3t6.5 4.5t5.5 6t3 8.5l21 91q2 10 10.5 17t19.5 7q47 0 87.5 7t80.5 24.5t63.5 52.5t23.5 84q0 36 -14.5 61t-41 36.5t-53.5 15.5t-62 4zM1835 798q-26 0 -74 -6 q-38 -6 -48 -16q-7 -8 -11 -19q-8 -24 -8 -39q0 -10 8 -10q1 0 41 12q30 8 58 8q74 0 74 -36q0 -12 -10 -14q-4 -1 -57 -7q-38 -4 -64.5 -10t-56.5 -19.5t-45.5 -39t-15.5 -62.5t26 -58.5t64 -21.5q24 0 45 6t34 13t38 24q-3 -15 -3 -16q0 -5 2 -8.5t6.5 -5.5t8 -3.5 t10.5 -2t9.5 -0.5h9.5h8q42 0 48 25l45 194q3 15 3 31q0 81 -145 81zM2157 889h-55q-25 0 -33 -40q-10 -44 -36.5 -167t-42.5 -190v-5q0 -16 16 -18h1h57q10 0 18.5 6.5t10.5 16.5l83 374h-1l1 5q0 7 -5.5 12.5t-13.5 5.5zM2304 1280v-1280q0 -52 -38 -90t-90 -38h-2048 q-52 0 -90 38t-38 90v1280q0 52 38 90t90 38h2048q52 0 90 -38t38 -90z" />
<glyph unicode="&#xf1f5;" horiz-adv-x="2304" d="M1597 633q0 -69 -21 -106q-19 -35 -52 -35q-23 0 -41 9v224q29 30 57 30q57 0 57 -122zM2035 669h-110q6 98 56 98q51 0 54 -98zM476 534q0 59 -33 91.5t-101 57.5q-36 13 -52 24t-16 25q0 26 38 26q58 0 124 -33l18 112q-67 32 -149 32q-77 0 -123 -38q-48 -39 -48 -109 q0 -58 32.5 -90.5t99.5 -56.5q39 -14 54.5 -25.5t15.5 -27.5q0 -31 -48 -31q-29 0 -70 12.5t-72 30.5l-18 -113q72 -41 168 -41q81 0 129 37q51 41 51 117zM771 749l19 111h-96v135l-129 -21l-18 -114l-46 -8l-17 -103h62v-219q0 -84 44 -120q38 -30 111 -30q32 0 79 11v118 q-32 -7 -44 -7q-42 0 -42 50v197h77zM1087 724v139q-15 3 -28 3q-32 0 -55.5 -16t-33.5 -46l-10 56h-131v-471h150v306q26 31 82 31q16 0 26 -2zM1124 389h150v471h-150v-471zM1746 638q0 122 -45 179q-40 52 -111 52q-64 0 -117 -56l-8 47h-132v-645l150 25v151 q36 -11 68 -11q83 0 134 56q61 65 61 202zM1278 986q0 33 -23 56t-56 23t-56 -23t-23 -56t23 -56.5t56 -23.5t56 23.5t23 56.5zM2176 629q0 113 -48 176q-50 64 -144 64q-96 0 -151.5 -66t-55.5 -180q0 -128 63 -188q55 -55 161 -55q101 0 160 40l-16 103q-57 -31 -128 -31 q-43 0 -63 19q-23 19 -28 66h248q2 14 2 52zM2304 1280v-1280q0 -52 -38 -90t-90 -38h-2048q-52 0 -90 38t-38 90v1280q0 52 38 90t90 38h2048q52 0 90 -38t38 -90z" />
<glyph unicode="&#xf1f6;" horiz-adv-x="2048" d="M1558 684q61 -356 298 -556q0 -52 -38 -90t-90 -38h-448q0 -106 -75 -181t-181 -75t-180.5 74.5t-75.5 180.5zM1024 -176q16 0 16 16t-16 16q-59 0 -101.5 42.5t-42.5 101.5q0 16 -16 16t-16 -16q0 -73 51.5 -124.5t124.5 -51.5zM2026 1424q8 -10 7.5 -23.5t-10.5 -22.5 l-1872 -1622q-10 -8 -23.5 -7t-21.5 11l-84 96q-8 10 -7.5 23.5t10.5 21.5l186 161q-19 32 -19 66q50 42 91 88t85 119.5t74.5 158.5t50 206t19.5 260q0 152 117 282.5t307 158.5q-8 19 -8 39q0 40 28 68t68 28t68 -28t28 -68q0 -20 -8 -39q124 -18 219 -82.5t148 -157.5 l418 363q10 8 23.5 7t21.5 -11z" />
<glyph unicode="&#xf1f7;" horiz-adv-x="2048" d="M1040 -160q0 16 -16 16q-59 0 -101.5 42.5t-42.5 101.5q0 16 -16 16t-16 -16q0 -73 51.5 -124.5t124.5 -51.5q16 0 16 16zM503 315l877 760q-42 88 -132.5 146.5t-223.5 58.5q-93 0 -169.5 -31.5t-121.5 -80.5t-69 -103t-24 -105q0 -384 -137 -645zM1856 128 q0 -52 -38 -90t-90 -38h-448q0 -106 -75 -181t-181 -75t-180.5 74.5t-75.5 180.5l149 129h757q-166 187 -227 459l111 97q61 -356 298 -556zM1942 1520l84 -96q8 -10 7.5 -23.5t-10.5 -22.5l-1872 -1622q-10 -8 -23.5 -7t-21.5 11l-84 96q-8 10 -7.5 23.5t10.5 21.5l186 161 q-19 32 -19 66q50 42 91 88t85 119.5t74.5 158.5t50 206t19.5 260q0 152 117 282.5t307 158.5q-8 19 -8 39q0 40 28 68t68 28t68 -28t28 -68q0 -20 -8 -39q124 -18 219 -82.5t148 -157.5l418 363q10 8 23.5 7t21.5 -11z" />
<glyph unicode="&#xf1f8;" horiz-adv-x="1408" d="M512 160v704q0 14 -9 23t-23 9h-64q-14 0 -23 -9t-9 -23v-704q0 -14 9 -23t23 -9h64q14 0 23 9t9 23zM768 160v704q0 14 -9 23t-23 9h-64q-14 0 -23 -9t-9 -23v-704q0 -14 9 -23t23 -9h64q14 0 23 9t9 23zM1024 160v704q0 14 -9 23t-23 9h-64q-14 0 -23 -9t-9 -23v-704 q0 -14 9 -23t23 -9h64q14 0 23 9t9 23zM480 1152h448l-48 117q-7 9 -17 11h-317q-10 -2 -17 -11zM1408 1120v-64q0 -14 -9 -23t-23 -9h-96v-948q0 -83 -47 -143.5t-113 -60.5h-832q-66 0 -113 58.5t-47 141.5v952h-96q-14 0 -23 9t-9 23v64q0 14 9 23t23 9h309l70 167 q15 37 54 63t79 26h320q40 0 79 -26t54 -63l70 -167h309q14 0 23 -9t9 -23z" />
<glyph unicode="&#xf1f9;" d="M1150 462v-109q0 -50 -36.5 -89t-94 -60.5t-118 -32.5t-117.5 -11q-205 0 -342.5 139t-137.5 346q0 203 136 339t339 136q34 0 75.5 -4.5t93 -18t92.5 -34t69 -56.5t28 -81v-109q0 -16 -16 -16h-118q-16 0 -16 16v70q0 43 -65.5 67.5t-137.5 24.5q-140 0 -228.5 -91.5 t-88.5 -237.5q0 -151 91.5 -249.5t233.5 -98.5q68 0 138 24t70 66v70q0 7 4.5 11.5t10.5 4.5h119q6 0 11 -4.5t5 -11.5zM768 1280q-130 0 -248.5 -51t-204 -136.5t-136.5 -204t-51 -248.5t51 -248.5t136.5 -204t204 -136.5t248.5 -51t248.5 51t204 136.5t136.5 204t51 248.5 t-51 248.5t-136.5 204t-204 136.5t-248.5 51zM1536 640q0 -209 -103 -385.5t-279.5 -279.5t-385.5 -103t-385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103t385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf1fa;" d="M972 761q0 108 -53.5 169t-147.5 61q-63 0 -124 -30.5t-110 -84.5t-79.5 -137t-30.5 -180q0 -112 53.5 -173t150.5 -61q96 0 176 66.5t122.5 166t42.5 203.5zM1536 640q0 -111 -37 -197t-98.5 -135t-131.5 -74.5t-145 -27.5q-6 0 -15.5 -0.5t-16.5 -0.5q-95 0 -142 53 q-28 33 -33 83q-52 -66 -131.5 -110t-173.5 -44q-161 0 -249.5 95.5t-88.5 269.5q0 157 66 290t179 210.5t246 77.5q87 0 155 -35.5t106 -99.5l2 19l11 56q1 6 5.5 12t9.5 6h118q5 0 13 -11q5 -5 3 -16l-120 -614q-5 -24 -5 -48q0 -39 12.5 -52t44.5 -13q28 1 57 5.5t73 24 t77 50t57 89.5t24 137q0 292 -174 466t-466 174q-130 0 -248.5 -51t-204 -136.5t-136.5 -204t-51 -248.5t51 -248.5t136.5 -204t204 -136.5t248.5 -51q228 0 405 144q11 9 24 8t21 -12l41 -49q8 -12 7 -24q-2 -13 -12 -22q-102 -83 -227.5 -128t-258.5 -45q-156 0 -298 61 t-245 164t-164 245t-61 298t61 298t164 245t245 164t298 61q344 0 556 -212t212 -556z" />
<glyph unicode="&#xf1fb;" horiz-adv-x="1792" d="M1698 1442q94 -94 94 -226.5t-94 -225.5l-225 -223l104 -104q10 -10 10 -23t-10 -23l-210 -210q-10 -10 -23 -10t-23 10l-105 105l-603 -603q-37 -37 -90 -37h-203l-256 -128l-64 64l128 256v203q0 53 37 90l603 603l-105 105q-10 10 -10 23t10 23l210 210q10 10 23 10 t23 -10l104 -104l223 225q93 94 225.5 94t226.5 -94zM512 64l576 576l-192 192l-576 -576v-192h192z" />
<glyph unicode="&#xf1fc;" horiz-adv-x="1792" d="M1615 1536q70 0 122.5 -46.5t52.5 -116.5q0 -63 -45 -151q-332 -629 -465 -752q-97 -91 -218 -91q-126 0 -216.5 92.5t-90.5 219.5q0 128 92 212l638 579q59 54 130 54zM706 502q39 -76 106.5 -130t150.5 -76l1 -71q4 -213 -129.5 -347t-348.5 -134q-123 0 -218 46.5 t-152.5 127.5t-86.5 183t-29 220q7 -5 41 -30t62 -44.5t59 -36.5t46 -17q41 0 55 37q25 66 57.5 112.5t69.5 76t88 47.5t103 25.5t125 10.5z" />
<glyph unicode="&#xf1fd;" horiz-adv-x="1792" d="M1792 128v-384h-1792v384q45 0 85 14t59 27.5t47 37.5q30 27 51.5 38t56.5 11t55.5 -11t52.5 -38q29 -25 47 -38t58 -27t86 -14q45 0 85 14.5t58 27t48 37.5q21 19 32.5 27t31 15t43.5 7q35 0 56.5 -11t51.5 -38q28 -24 47 -37.5t59 -27.5t85 -14t85 14t59 27.5t47 37.5 q30 27 51.5 38t56.5 11q34 0 55.5 -11t51.5 -38q28 -24 47 -37.5t59 -27.5t85 -14zM1792 448v-192q-35 0 -55.5 11t-52.5 38q-29 25 -47 38t-58 27t-85 14q-46 0 -86 -14t-58 -27t-47 -38q-22 -19 -33 -27t-31 -15t-44 -7q-35 0 -56.5 11t-51.5 38q-29 25 -47 38t-58 27 t-86 14q-45 0 -85 -14.5t-58 -27t-48 -37.5q-21 -19 -32.5 -27t-31 -15t-43.5 -7q-35 0 -56.5 11t-51.5 38q-28 24 -47 37.5t-59 27.5t-85 14q-46 0 -86 -14t-58 -27t-47 -38q-30 -27 -51.5 -38t-56.5 -11v192q0 80 56 136t136 56h64v448h256v-448h256v448h256v-448h256v448 h256v-448h64q80 0 136 -56t56 -136zM512 1312q0 -77 -36 -118.5t-92 -41.5q-53 0 -90.5 37.5t-37.5 90.5q0 29 9.5 51t23.5 34t31 28t31 31.5t23.5 44.5t9.5 67q38 0 83 -74t45 -150zM1024 1312q0 -77 -36 -118.5t-92 -41.5q-53 0 -90.5 37.5t-37.5 90.5q0 29 9.5 51 t23.5 34t31 28t31 31.5t23.5 44.5t9.5 67q38 0 83 -74t45 -150zM1536 1312q0 -77 -36 -118.5t-92 -41.5q-53 0 -90.5 37.5t-37.5 90.5q0 29 9.5 51t23.5 34t31 28t31 31.5t23.5 44.5t9.5 67q38 0 83 -74t45 -150z" />
<glyph unicode="&#xf1fe;" horiz-adv-x="2048" d="M2048 0v-128h-2048v1536h128v-1408h1920zM1664 1024l256 -896h-1664v576l448 576l576 -576z" />
<glyph unicode="&#xf200;" horiz-adv-x="1792" d="M768 646l546 -546q-106 -108 -247.5 -168t-298.5 -60q-209 0 -385.5 103t-279.5 279.5t-103 385.5t103 385.5t279.5 279.5t385.5 103v-762zM955 640h773q0 -157 -60 -298.5t-168 -247.5zM1664 768h-768v768q209 0 385.5 -103t279.5 -279.5t103 -385.5z" />
<glyph unicode="&#xf201;" horiz-adv-x="2048" d="M2048 0v-128h-2048v1536h128v-1408h1920zM1920 1248v-435q0 -21 -19.5 -29.5t-35.5 7.5l-121 121l-633 -633q-10 -10 -23 -10t-23 10l-233 233l-416 -416l-192 192l585 585q10 10 23 10t23 -10l233 -233l464 464l-121 121q-16 16 -7.5 35.5t29.5 19.5h435q14 0 23 -9 t9 -23z" />
<glyph unicode="&#xf202;" horiz-adv-x="1792" d="M1292 832q0 -6 10 -41q10 -29 25 -49.5t41 -34t44 -20t55 -16.5q325 -91 325 -332q0 -146 -105.5 -242.5t-254.5 -96.5q-59 0 -111.5 18.5t-91.5 45.5t-77 74.5t-63 87.5t-53.5 103.5t-43.5 103t-39.5 106.5t-35.5 95q-32 81 -61.5 133.5t-73.5 96.5t-104 64t-142 20 q-96 0 -183 -55.5t-138 -144.5t-51 -185q0 -160 106.5 -279.5t263.5 -119.5q177 0 258 95q56 63 83 116l84 -152q-15 -34 -44 -70l1 -1q-131 -152 -388 -152q-147 0 -269.5 79t-190.5 207.5t-68 274.5q0 105 43.5 206t116 176.5t172 121.5t204.5 46q87 0 159 -19t123.5 -50 t95 -80t72.5 -99t58.5 -117t50.5 -124.5t50 -130.5t55 -127q96 -200 233 -200q81 0 138.5 48.5t57.5 128.5q0 42 -19 72t-50.5 46t-72.5 31.5t-84.5 27t-87.5 34t-81 52t-65 82t-39 122.5q-3 16 -3 33q0 110 87.5 192t198.5 78q78 -3 120.5 -14.5t90.5 -53.5h-1 q12 -11 23 -24.5t26 -36t19 -27.5l-129 -99q-26 49 -54 70v1q-23 21 -97 21q-49 0 -84 -33t-35 -83z" />
<glyph unicode="&#xf203;" d="M1432 484q0 173 -234 239q-35 10 -53 16.5t-38 25t-29 46.5q0 2 -2 8.5t-3 12t-1 7.5q0 36 24.5 59.5t60.5 23.5q54 0 71 -15h-1q20 -15 39 -51l93 71q-39 54 -49 64q-33 29 -67.5 39t-85.5 10q-80 0 -142 -57.5t-62 -137.5q0 -7 2 -23q16 -96 64.5 -140t148.5 -73 q29 -8 49 -15.5t45 -21.5t38.5 -34.5t13.5 -46.5v-5q1 -58 -40.5 -93t-100.5 -35q-97 0 -167 144q-23 47 -51.5 121.5t-48 125.5t-54 110.5t-74 95.5t-103.5 60.5t-147 24.5q-101 0 -192 -56t-144 -148t-50 -192v-1q4 -108 50.5 -199t133.5 -147.5t196 -56.5q186 0 279 110 q20 27 31 51l-60 109q-42 -80 -99 -116t-146 -36q-115 0 -191 87t-76 204q0 105 82 189t186 84q112 0 170 -53.5t104 -172.5q8 -21 25.5 -68.5t28.5 -76.5t31.5 -74.5t38.5 -74t45.5 -62.5t55.5 -53.5t66 -33t80 -13.5q107 0 183 69.5t76 174.5zM1536 1120v-960 q0 -119 -84.5 -203.5t-203.5 -84.5h-960q-119 0 -203.5 84.5t-84.5 203.5v960q0 119 84.5 203.5t203.5 84.5h960q119 0 203.5 -84.5t84.5 -203.5z" />
<glyph unicode="&#xf204;" horiz-adv-x="2048" d="M1152 640q0 104 -40.5 198.5t-109.5 163.5t-163.5 109.5t-198.5 40.5t-198.5 -40.5t-163.5 -109.5t-109.5 -163.5t-40.5 -198.5t40.5 -198.5t109.5 -163.5t163.5 -109.5t198.5 -40.5t198.5 40.5t163.5 109.5t109.5 163.5t40.5 198.5zM1920 640q0 104 -40.5 198.5 t-109.5 163.5t-163.5 109.5t-198.5 40.5h-386q119 -90 188.5 -224t69.5 -288t-69.5 -288t-188.5 -224h386q104 0 198.5 40.5t163.5 109.5t109.5 163.5t40.5 198.5zM2048 640q0 -130 -51 -248.5t-136.5 -204t-204 -136.5t-248.5 -51h-768q-130 0 -248.5 51t-204 136.5 t-136.5 204t-51 248.5t51 248.5t136.5 204t204 136.5t248.5 51h768q130 0 248.5 -51t204 -136.5t136.5 -204t51 -248.5z" />
<glyph unicode="&#xf205;" horiz-adv-x="2048" d="M0 640q0 130 51 248.5t136.5 204t204 136.5t248.5 51h768q130 0 248.5 -51t204 -136.5t136.5 -204t51 -248.5t-51 -248.5t-136.5 -204t-204 -136.5t-248.5 -51h-768q-130 0 -248.5 51t-204 136.5t-136.5 204t-51 248.5zM1408 128q104 0 198.5 40.5t163.5 109.5 t109.5 163.5t40.5 198.5t-40.5 198.5t-109.5 163.5t-163.5 109.5t-198.5 40.5t-198.5 -40.5t-163.5 -109.5t-109.5 -163.5t-40.5 -198.5t40.5 -198.5t109.5 -163.5t163.5 -109.5t198.5 -40.5z" />
<glyph unicode="&#xf206;" horiz-adv-x="2304" d="M762 384h-314q-40 0 -57.5 35t6.5 67l188 251q-65 31 -137 31q-132 0 -226 -94t-94 -226t94 -226t226 -94q115 0 203 72.5t111 183.5zM576 512h186q-18 85 -75 148zM1056 512l288 384h-480l-99 -132q105 -103 126 -252h165zM2176 448q0 132 -94 226t-226 94 q-60 0 -121 -24l174 -260q15 -23 10 -49t-27 -40q-15 -11 -36 -11q-35 0 -53 29l-174 260q-93 -95 -93 -225q0 -132 94 -226t226 -94t226 94t94 226zM2304 448q0 -185 -131.5 -316.5t-316.5 -131.5t-316.5 131.5t-131.5 316.5q0 97 39.5 183.5t109.5 149.5l-65 98l-353 -469 q-18 -26 -51 -26h-197q-23 -164 -149 -274t-294 -110q-185 0 -316.5 131.5t-131.5 316.5t131.5 316.5t316.5 131.5q114 0 215 -55l137 183h-224q-26 0 -45 19t-19 45t19 45t45 19h384v-128h435l-85 128h-222q-26 0 -45 19t-19 45t19 45t45 19h256q33 0 53 -28l267 -400 q91 44 192 44q185 0 316.5 -131.5t131.5 -316.5z" />
<glyph unicode="&#xf207;" d="M384 320q0 53 -37.5 90.5t-90.5 37.5t-90.5 -37.5t-37.5 -90.5t37.5 -90.5t90.5 -37.5t90.5 37.5t37.5 90.5zM1408 320q0 53 -37.5 90.5t-90.5 37.5t-90.5 -37.5t-37.5 -90.5t37.5 -90.5t90.5 -37.5t90.5 37.5t37.5 90.5zM1362 716l-72 384q-5 23 -22.5 37.5t-40.5 14.5 h-918q-23 0 -40.5 -14.5t-22.5 -37.5l-72 -384q-5 -30 14 -53t49 -23h1062q30 0 49 23t14 53zM1136 1328q0 20 -14 34t-34 14h-640q-20 0 -34 -14t-14 -34t14 -34t34 -14h640q20 0 34 14t14 34zM1536 603v-603h-128v-128q0 -53 -37.5 -90.5t-90.5 -37.5t-90.5 37.5 t-37.5 90.5v128h-768v-128q0 -53 -37.5 -90.5t-90.5 -37.5t-90.5 37.5t-37.5 90.5v128h-128v603q0 112 25 223l103 454q9 78 97.5 137t230 89t312.5 30t312.5 -30t230 -89t97.5 -137l105 -454q23 -102 23 -223z" />
<glyph unicode="&#xf208;" horiz-adv-x="2048" d="M1463 704q0 -35 -25 -60.5t-61 -25.5h-702q-36 0 -61 25.5t-25 60.5t25 60.5t61 25.5h702q36 0 61 -25.5t25 -60.5zM1677 704q0 86 -23 170h-982q-36 0 -61 25t-25 60q0 36 25 61t61 25h908q-88 143 -235 227t-320 84q-177 0 -327.5 -87.5t-238 -237.5t-87.5 -327 q0 -86 23 -170h982q36 0 61 -25t25 -60q0 -36 -25 -61t-61 -25h-908q88 -143 235.5 -227t320.5 -84q132 0 253 51.5t208 139t139 208t52 253.5zM2048 959q0 -35 -25 -60t-61 -25h-131q17 -85 17 -170q0 -167 -65.5 -319.5t-175.5 -263t-262.5 -176t-319.5 -65.5 q-246 0 -448.5 133t-301.5 350h-189q-36 0 -61 25t-25 61q0 35 25 60t61 25h132q-17 85 -17 170q0 167 65.5 319.5t175.5 263t262.5 176t320.5 65.5q245 0 447.5 -133t301.5 -350h188q36 0 61 -25t25 -61z" />
<glyph unicode="&#xf209;" horiz-adv-x="1280" d="M953 1158l-114 -328l117 -21q165 451 165 518q0 56 -38 56q-57 0 -130 -225zM654 471l33 -88q37 42 71 67l-33 5.5t-38.5 7t-32.5 8.5zM362 1367q0 -98 159 -521q18 10 49 10q15 0 75 -5l-121 351q-75 220 -123 220q-19 0 -29 -17.5t-10 -37.5zM283 608q0 -36 51.5 -119 t117.5 -153t100 -70q14 0 25.5 13t11.5 27q0 24 -32 102q-13 32 -32 72t-47.5 89t-61.5 81t-62 32q-20 0 -45.5 -27t-25.5 -47zM125 273q0 -41 25 -104q59 -145 183.5 -227t281.5 -82q227 0 382 170q152 169 152 427q0 43 -1 67t-11.5 62t-30.5 56q-56 49 -211.5 75.5 t-270.5 26.5q-37 0 -49 -11q-12 -5 -12 -35q0 -34 21.5 -60t55.5 -40t77.5 -23.5t87.5 -11.5t85 -4t70 0h23q24 0 40 -19q15 -19 19 -55q-28 -28 -96 -54q-61 -22 -93 -46q-64 -46 -108.5 -114t-44.5 -137q0 -31 18.5 -88.5t18.5 -87.5l-3 -12q-4 -12 -4 -14 q-137 10 -146 216q-8 -2 -41 -2q2 -7 2 -21q0 -53 -40.5 -89.5t-94.5 -36.5q-82 0 -166.5 78t-84.5 159q0 34 33 67q52 -64 60 -76q77 -104 133 -104q12 0 26.5 8.5t14.5 20.5q0 34 -87.5 145t-116.5 111q-43 0 -70 -44.5t-27 -90.5zM11 264q0 101 42.5 163t136.5 88 q-28 74 -28 104q0 62 61 123t122 61q29 0 70 -15q-163 462 -163 567q0 80 41 130.5t119 50.5q131 0 325 -581q6 -17 8 -23q6 16 29 79.5t43.5 118.5t54 127.5t64.5 123t70.5 86.5t76.5 36q71 0 112 -49t41 -122q0 -108 -159 -550q61 -15 100.5 -46t58.5 -78t26 -93.5 t7 -110.5q0 -150 -47 -280t-132 -225t-211 -150t-278 -55q-111 0 -223 42q-149 57 -258 191.5t-109 286.5z" />
<glyph unicode="&#xf20a;" horiz-adv-x="2048" d="M785 528h207q-14 -158 -98.5 -248.5t-214.5 -90.5q-162 0 -254.5 116t-92.5 316q0 194 93 311.5t233 117.5q148 0 232 -87t97 -247h-203q-5 64 -35.5 99t-81.5 35q-57 0 -88.5 -60.5t-31.5 -177.5q0 -48 5 -84t18 -69.5t40 -51.5t66 -18q95 0 109 139zM1497 528h206 q-14 -158 -98 -248.5t-214 -90.5q-162 0 -254.5 116t-92.5 316q0 194 93 311.5t233 117.5q148 0 232 -87t97 -247h-204q-4 64 -35 99t-81 35q-57 0 -88.5 -60.5t-31.5 -177.5q0 -48 5 -84t18 -69.5t39.5 -51.5t65.5 -18q49 0 76.5 38t33.5 101zM1856 647q0 207 -15.5 307 t-60.5 161q-6 8 -13.5 14t-21.5 15t-16 11q-86 63 -697 63q-625 0 -710 -63q-5 -4 -17.5 -11.5t-21 -14t-14.5 -14.5q-45 -60 -60 -159.5t-15 -308.5q0 -208 15 -307.5t60 -160.5q6 -8 15 -15t20.5 -14t17.5 -12q44 -33 239.5 -49t470.5 -16q610 0 697 65q5 4 17 11t20.5 14 t13.5 16q46 60 61 159t15 309zM2048 1408v-1536h-2048v1536h2048z" />
<glyph unicode="&#xf20b;" d="M992 912v-496q0 -14 -9 -23t-23 -9h-160q-14 0 -23 9t-9 23v496q0 112 -80 192t-192 80h-272v-1152q0 -14 -9 -23t-23 -9h-160q-14 0 -23 9t-9 23v1344q0 14 9 23t23 9h464q135 0 249 -66.5t180.5 -180.5t66.5 -249zM1376 1376v-880q0 -135 -66.5 -249t-180.5 -180.5 t-249 -66.5h-464q-14 0 -23 9t-9 23v960q0 14 9 23t23 9h160q14 0 23 -9t9 -23v-768h272q112 0 192 80t80 192v880q0 14 9 23t23 9h160q14 0 23 -9t9 -23z" />
<glyph unicode="&#xf20c;" d="M1311 694v-114q0 -24 -13.5 -38t-37.5 -14h-202q-24 0 -38 14t-14 38v114q0 24 14 38t38 14h202q24 0 37.5 -14t13.5 -38zM821 464v250q0 53 -32.5 85.5t-85.5 32.5h-133q-68 0 -96 -52q-28 52 -96 52h-130q-53 0 -85.5 -32.5t-32.5 -85.5v-250q0 -22 21 -22h55 q22 0 22 22v230q0 24 13.5 38t38.5 14h94q24 0 38 -14t14 -38v-230q0 -22 21 -22h54q22 0 22 22v230q0 24 14 38t38 14h97q24 0 37.5 -14t13.5 -38v-230q0 -22 22 -22h55q21 0 21 22zM1410 560v154q0 53 -33 85.5t-86 32.5h-264q-53 0 -86 -32.5t-33 -85.5v-410 q0 -21 22 -21h55q21 0 21 21v180q31 -42 94 -42h191q53 0 86 32.5t33 85.5zM1536 1176v-1072q0 -96 -68 -164t-164 -68h-1072q-96 0 -164 68t-68 164v1072q0 96 68 164t164 68h1072q96 0 164 -68t68 -164z" />
<glyph unicode="&#xf20d;" d="M915 450h-294l147 551zM1001 128h311l-324 1024h-440l-324 -1024h311l383 314zM1536 1120v-960q0 -118 -85 -203t-203 -85h-960q-118 0 -203 85t-85 203v960q0 118 85 203t203 85h960q118 0 203 -85t85 -203z" />
<glyph unicode="&#xf20e;" horiz-adv-x="2048" d="M2048 641q0 -21 -13 -36.5t-33 -19.5l-205 -356q3 -9 3 -18q0 -20 -12.5 -35.5t-32.5 -19.5l-193 -337q3 -8 3 -16q0 -23 -16.5 -40t-40.5 -17q-25 0 -41 18h-400q-17 -20 -43 -20t-43 20h-399q-17 -20 -43 -20q-23 0 -40 16.5t-17 40.5q0 8 4 20l-193 335 q-20 4 -32.5 19.5t-12.5 35.5q0 9 3 18l-206 356q-20 5 -32.5 20.5t-12.5 35.5q0 21 13.5 36.5t33.5 19.5l199 344q0 1 -0.5 3t-0.5 3q0 36 34 51l209 363q-4 10 -4 18q0 24 17 40.5t40 16.5q26 0 44 -21h396q16 21 43 21t43 -21h398q18 21 44 21q23 0 40 -16.5t17 -40.5 q0 -6 -4 -18l207 -358q23 -1 39 -17.5t16 -38.5q0 -13 -7 -27l187 -324q19 -4 31.5 -19.5t12.5 -35.5zM1063 -158h389l-342 354h-143l-342 -354h360q18 16 39 16t39 -16zM112 654q1 -4 1 -13q0 -10 -2 -15l208 -360q2 0 4.5 -1t5.5 -2.5l5 -2.5l188 199v347l-187 194 q-13 -8 -29 -10zM986 1438h-388l190 -200l554 200h-280q-16 -16 -38 -16t-38 16zM1689 226q1 6 5 11l-64 68l-17 -79h76zM1583 226l22 105l-252 266l-296 -307l63 -64h463zM1495 -142l16 28l65 310h-427l333 -343q8 4 13 5zM578 -158h5l342 354h-373v-335l4 -6q14 -5 22 -13 zM552 226h402l64 66l-309 321l-157 -166v-221zM359 226h163v189l-168 -177q4 -8 5 -12zM358 1051q0 -1 0.5 -2t0.5 -2q0 -16 -8 -29l171 -177v269zM552 1121v-311l153 -157l297 314l-223 236zM556 1425l-4 -8v-264l205 74l-191 201q-6 -2 -10 -3zM1447 1438h-16l-621 -224 l213 -225zM1023 946l-297 -315l311 -319l296 307zM688 634l-136 141v-284zM1038 270l-42 -44h85zM1374 618l238 -251l132 624l-3 5l-1 1zM1718 1018q-8 13 -8 29v2l-216 376q-5 1 -13 5l-437 -463l310 -327zM522 1142v223l-163 -282zM522 196h-163l163 -283v283zM1607 196 l-48 -227l130 227h-82zM1729 266l207 361q-2 10 -2 14q0 1 3 16l-171 296l-129 -612l77 -82q5 3 15 7z" />
<glyph unicode="&#xf210;" d="M0 856q0 131 91.5 226.5t222.5 95.5h742l352 358v-1470q0 -132 -91.5 -227t-222.5 -95h-780q-131 0 -222.5 95t-91.5 227v790zM1232 102l-176 180v425q0 46 -32 79t-78 33h-484q-46 0 -78 -33t-32 -79v-492q0 -46 32.5 -79.5t77.5 -33.5h770z" />
<glyph unicode="&#xf211;" d="M934 1386q-317 -121 -556 -362.5t-358 -560.5q-20 89 -20 176q0 208 102.5 384.5t278.5 279t384 102.5q82 0 169 -19zM1203 1267q93 -65 164 -155q-389 -113 -674.5 -400.5t-396.5 -676.5q-93 72 -155 162q112 386 395 671t667 399zM470 -67q115 356 379.5 622t619.5 384 q40 -92 54 -195q-292 -120 -516 -345t-343 -518q-103 14 -194 52zM1536 -125q-193 50 -367 115q-135 -84 -290 -107q109 205 274 370.5t369 275.5q-21 -152 -101 -284q65 -175 115 -370z" />
<glyph unicode="&#xf212;" horiz-adv-x="2048" d="M1893 1144l155 -1272q-131 0 -257 57q-200 91 -393 91q-226 0 -374 -148q-148 148 -374 148q-193 0 -393 -91q-128 -57 -252 -57h-5l155 1272q224 127 482 127q233 0 387 -106q154 106 387 106q258 0 482 -127zM1398 157q129 0 232 -28.5t260 -93.5l-124 1021 q-171 78 -368 78q-224 0 -374 -141q-150 141 -374 141q-197 0 -368 -78l-124 -1021q105 43 165.5 65t148.5 39.5t178 17.5q202 0 374 -108q172 108 374 108zM1438 191l-55 907q-211 -4 -359 -155q-152 155 -374 155q-176 0 -336 -66l-114 -941q124 51 228.5 76t221.5 25 q209 0 374 -102q172 107 374 102z" />
<glyph unicode="&#xf213;" horiz-adv-x="2048" d="M1500 165v733q0 21 -15 36t-35 15h-93q-20 0 -35 -15t-15 -36v-733q0 -20 15 -35t35 -15h93q20 0 35 15t15 35zM1216 165v531q0 20 -15 35t-35 15h-101q-20 0 -35 -15t-15 -35v-531q0 -20 15 -35t35 -15h101q20 0 35 15t15 35zM924 165v429q0 20 -15 35t-35 15h-101 q-20 0 -35 -15t-15 -35v-429q0 -20 15 -35t35 -15h101q20 0 35 15t15 35zM632 165v362q0 20 -15 35t-35 15h-101q-20 0 -35 -15t-15 -35v-362q0 -20 15 -35t35 -15h101q20 0 35 15t15 35zM2048 311q0 -166 -118 -284t-284 -118h-1244q-166 0 -284 118t-118 284 q0 116 63 214.5t168 148.5q-10 34 -10 73q0 113 80.5 193.5t193.5 80.5q102 0 180 -67q45 183 194 300t338 117q149 0 275 -73.5t199.5 -199.5t73.5 -275q0 -66 -14 -122q135 -33 221 -142.5t86 -247.5z" />
<glyph unicode="&#xf214;" d="M0 1536h1536v-1392l-776 -338l-760 338v1392zM1436 209v926h-1336v-926l661 -294zM1436 1235v201h-1336v-201h1336zM181 937v-115h-37v115h37zM181 789v-115h-37v115h37zM181 641v-115h-37v115h37zM181 493v-115h-37v115h37zM181 345v-115h-37v115h37zM207 202l15 34 l105 -47l-15 -33zM343 142l15 34l105 -46l-15 -34zM478 82l15 34l105 -46l-15 -34zM614 23l15 33l104 -46l-15 -34zM797 10l105 46l15 -33l-105 -47zM932 70l105 46l15 -34l-105 -46zM1068 130l105 46l15 -34l-105 -46zM1203 189l105 47l15 -34l-105 -46zM259 1389v-36h-114 v36h114zM421 1389v-36h-115v36h115zM583 1389v-36h-115v36h115zM744 1389v-36h-114v36h114zM906 1389v-36h-114v36h114zM1068 1389v-36h-115v36h115zM1230 1389v-36h-115v36h115zM1391 1389v-36h-114v36h114zM181 1049v-79h-37v115h115v-36h-78zM421 1085v-36h-115v36h115z M583 1085v-36h-115v36h115zM744 1085v-36h-114v36h114zM906 1085v-36h-114v36h114zM1068 1085v-36h-115v36h115zM1230 1085v-36h-115v36h115zM1355 970v79h-78v36h115v-115h-37zM1355 822v115h37v-115h-37zM1355 674v115h37v-115h-37zM1355 526v115h37v-115h-37zM1355 378 v115h37v-115h-37zM1355 230v115h37v-115h-37zM760 265q-129 0 -221 91.5t-92 221.5q0 129 92 221t221 92q130 0 221.5 -92t91.5 -221q0 -130 -91.5 -221.5t-221.5 -91.5zM595 646q0 -36 19.5 -56.5t49.5 -25t64 -7t64 -2t49.5 -9t19.5 -30.5q0 -49 -112 -49q-97 0 -123 51 h-3l-31 -63q67 -42 162 -42q29 0 56.5 5t55.5 16t45.5 33t17.5 53q0 46 -27.5 69.5t-67.5 27t-79.5 3t-67 5t-27.5 25.5q0 21 20.5 33t40.5 15t41 3q34 0 70.5 -11t51.5 -34h3l30 58q-3 1 -21 8.5t-22.5 9t-19.5 7t-22 7t-20 4.5t-24 4t-23 1q-29 0 -56.5 -5t-54 -16.5 t-43 -34t-16.5 -53.5z" />
<glyph unicode="&#xf215;" horiz-adv-x="2048" d="M863 504q0 112 -79.5 191.5t-191.5 79.5t-191 -79.5t-79 -191.5t79 -191t191 -79t191.5 79t79.5 191zM1726 505q0 112 -79 191t-191 79t-191.5 -79t-79.5 -191q0 -113 79.5 -192t191.5 -79t191 79.5t79 191.5zM2048 1314v-1348q0 -44 -31.5 -75.5t-76.5 -31.5h-1832 q-45 0 -76.5 31.5t-31.5 75.5v1348q0 44 31.5 75.5t76.5 31.5h431q44 0 76 -31.5t32 -75.5v-161h754v161q0 44 32 75.5t76 31.5h431q45 0 76.5 -31.5t31.5 -75.5z" />
<glyph unicode="&#xf216;" horiz-adv-x="2048" d="M1430 953zM1690 749q148 0 253 -98.5t105 -244.5q0 -157 -109 -261.5t-267 -104.5q-85 0 -162 27.5t-138 73.5t-118 106t-109 126.5t-103.5 132.5t-108.5 126t-117 106t-136 73.5t-159 27.5q-154 0 -251.5 -91.5t-97.5 -244.5q0 -157 104 -250t263 -93q100 0 208 37.5 t193 98.5q5 4 21 18.5t30 24t22 9.5q14 0 24.5 -10.5t10.5 -24.5q0 -24 -60 -77q-101 -88 -234.5 -142t-260.5 -54q-133 0 -245.5 58t-180 165t-67.5 241q0 205 141.5 341t347.5 136q120 0 226.5 -43.5t185.5 -113t151.5 -153t139 -167.5t133.5 -153.5t149.5 -113 t172.5 -43.5q102 0 168.5 61.5t66.5 162.5q0 95 -64.5 159t-159.5 64q-30 0 -81.5 -18.5t-68.5 -18.5q-20 0 -35.5 15t-15.5 35q0 18 8.5 57t8.5 59q0 159 -107.5 263t-266.5 104q-58 0 -111.5 -18.5t-84 -40.5t-55.5 -40.5t-33 -18.5q-15 0 -25.5 10.5t-10.5 25.5 q0 19 25 46q59 67 147 103.5t182 36.5q191 0 318 -125.5t127 -315.5q0 -37 -4 -66q57 15 115 15z" />
<glyph unicode="&#xf217;" horiz-adv-x="1664" d="M1216 832q0 26 -19 45t-45 19h-128v128q0 26 -19 45t-45 19t-45 -19t-19 -45v-128h-128q-26 0 -45 -19t-19 -45t19 -45t45 -19h128v-128q0 -26 19 -45t45 -19t45 19t19 45v128h128q26 0 45 19t19 45zM640 0q0 -53 -37.5 -90.5t-90.5 -37.5t-90.5 37.5t-37.5 90.5 t37.5 90.5t90.5 37.5t90.5 -37.5t37.5 -90.5zM1536 0q0 -53 -37.5 -90.5t-90.5 -37.5t-90.5 37.5t-37.5 90.5t37.5 90.5t90.5 37.5t90.5 -37.5t37.5 -90.5zM1664 1088v-512q0 -24 -16 -42.5t-41 -21.5l-1044 -122q1 -7 4.5 -21.5t6 -26.5t2.5 -22q0 -16 -24 -64h920 q26 0 45 -19t19 -45t-19 -45t-45 -19h-1024q-26 0 -45 19t-19 45q0 14 11 39.5t29.5 59.5t20.5 38l-177 823h-204q-26 0 -45 19t-19 45t19 45t45 19h256q16 0 28.5 -6.5t20 -15.5t13 -24.5t7.5 -26.5t5.5 -29.5t4.5 -25.5h1201q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf218;" horiz-adv-x="1792" d="M1280 832q0 26 -19 45t-45 19t-45 -19l-147 -146v293q0 26 -19 45t-45 19t-45 -19t-19 -45v-293l-147 146q-19 19 -45 19t-45 -19t-19 -45t19 -45l256 -256q19 -19 45 -19t45 19l256 256q19 19 19 45zM640 0q0 -53 -37.5 -90.5t-90.5 -37.5t-90.5 37.5t-37.5 90.5 t37.5 90.5t90.5 37.5t90.5 -37.5t37.5 -90.5zM1536 0q0 -53 -37.5 -90.5t-90.5 -37.5t-90.5 37.5t-37.5 90.5t37.5 90.5t90.5 37.5t90.5 -37.5t37.5 -90.5zM1664 1088v-512q0 -24 -16 -42.5t-41 -21.5l-1044 -122q1 -7 4.5 -21.5t6 -26.5t2.5 -22q0 -16 -24 -64h920 q26 0 45 -19t19 -45t-19 -45t-45 -19h-1024q-26 0 -45 19t-19 45q0 14 11 39.5t29.5 59.5t20.5 38l-177 823h-204q-26 0 -45 19t-19 45t19 45t45 19h256q16 0 28.5 -6.5t20 -15.5t13 -24.5t7.5 -26.5t5.5 -29.5t4.5 -25.5h1201q26 0 45 -19t19 -45z" />
<glyph unicode="&#xf219;" horiz-adv-x="2048" d="M212 768l623 -665l-300 665h-323zM1024 -4l349 772h-698zM538 896l204 384h-262l-288 -384h346zM1213 103l623 665h-323zM683 896h682l-204 384h-274zM1510 896h346l-288 384h-262zM1651 1382l384 -512q14 -18 13 -41.5t-17 -40.5l-960 -1024q-18 -20 -47 -20t-47 20 l-960 1024q-16 17 -17 40.5t13 41.5l384 512q18 26 51 26h1152q33 0 51 -26z" />
<glyph unicode="&#xf21a;" horiz-adv-x="2048" d="M1811 -19q19 19 45 19t45 -19l128 -128l-90 -90l-83 83l-83 -83q-18 -19 -45 -19t-45 19l-83 83l-83 -83q-19 -19 -45 -19t-45 19l-83 83l-83 -83q-19 -19 -45 -19t-45 19l-83 83l-83 -83q-19 -19 -45 -19t-45 19l-83 83l-83 -83q-19 -19 -45 -19t-45 19l-83 83l-83 -83 q-19 -19 -45 -19t-45 19l-83 83l-83 -83q-19 -19 -45 -19t-45 19l-128 128l90 90l83 -83l83 83q19 19 45 19t45 -19l83 -83l83 83q19 19 45 19t45 -19l83 -83l83 83q19 19 45 19t45 -19l83 -83l83 83q19 19 45 19t45 -19l83 -83l83 83q19 19 45 19t45 -19l83 -83l83 83 q19 19 45 19t45 -19l83 -83zM237 19q-19 -19 -45 -19t-45 19l-128 128l90 90l83 -82l83 82q19 19 45 19t45 -19l83 -82l64 64v293l-210 314q-17 26 -7 56.5t40 40.5l177 58v299h128v128h256v128h256v-128h256v-128h128v-299l177 -58q30 -10 40 -40.5t-7 -56.5l-210 -314 v-293l19 18q19 19 45 19t45 -19l83 -82l83 82q19 19 45 19t45 -19l128 -128l-90 -90l-83 83l-83 -83q-18 -19 -45 -19t-45 19l-83 83l-83 -83q-19 -19 -45 -19t-45 19l-83 83l-83 -83q-19 -19 -45 -19t-45 19l-83 83l-83 -83q-19 -19 -45 -19t-45 19l-83 83l-83 -83 q-19 -19 -45 -19t-45 19l-83 83l-83 -83q-19 -19 -45 -19t-45 19l-83 83zM640 1152v-128l384 128l384 -128v128h-128v128h-512v-128h-128z" />
<glyph unicode="&#xf21b;" d="M576 0l96 448l-96 128l-128 64zM832 0l128 640l-128 -64l-96 -128zM992 1010q-2 4 -4 6q-10 8 -96 8q-70 0 -167 -19q-7 -2 -21 -2t-21 2q-97 19 -167 19q-86 0 -96 -8q-2 -2 -4 -6q2 -18 4 -27q2 -3 7.5 -6.5t7.5 -10.5q2 -4 7.5 -20.5t7 -20.5t7.5 -17t8.5 -17t9 -14 t12 -13.5t14 -9.5t17.5 -8t20.5 -4t24.5 -2q36 0 59 12.5t32.5 30t14.5 34.5t11.5 29.5t17.5 12.5h12q11 0 17.5 -12.5t11.5 -29.5t14.5 -34.5t32.5 -30t59 -12.5q13 0 24.5 2t20.5 4t17.5 8t14 9.5t12 13.5t9 14t8.5 17t7.5 17t7 20.5t7.5 20.5q2 7 7.5 10.5t7.5 6.5 q2 9 4 27zM1408 131q0 -121 -73 -190t-194 -69h-874q-121 0 -194 69t-73 190q0 61 4.5 118t19 125.5t37.5 123.5t63.5 103.5t93.5 74.5l-90 220h214q-22 64 -22 128q0 12 2 32q-194 40 -194 96q0 57 210 99q17 62 51.5 134t70.5 114q32 37 76 37q30 0 84 -31t84 -31t84 31 t84 31q44 0 76 -37q36 -42 70.5 -114t51.5 -134q210 -42 210 -99q0 -56 -194 -96q7 -81 -20 -160h214l-82 -225q63 -33 107.5 -96.5t65.5 -143.5t29 -151.5t8 -148.5z" />
<glyph unicode="&#xf21c;" horiz-adv-x="2304" d="M2301 500q12 -103 -22 -198.5t-99 -163.5t-158.5 -106t-196.5 -31q-161 11 -279.5 125t-134.5 274q-12 111 27.5 210.5t118.5 170.5l-71 107q-96 -80 -151 -194t-55 -244q0 -27 -18.5 -46.5t-45.5 -19.5h-256h-69q-23 -164 -149 -274t-294 -110q-185 0 -316.5 131.5 t-131.5 316.5t131.5 316.5t316.5 131.5q76 0 152 -27l24 45q-123 110 -304 110h-64q-26 0 -45 19t-19 45t19 45t45 19h128q78 0 145 -13.5t116.5 -38.5t71.5 -39.5t51 -36.5h512h115l-85 128h-222q-30 0 -49 22.5t-14 52.5q4 23 23 38t43 15h253q33 0 53 -28l70 -105 l114 114q19 19 46 19h101q26 0 45 -19t19 -45v-128q0 -26 -19 -45t-45 -19h-179l115 -172q131 63 275 36q143 -26 244 -134.5t118 -253.5zM448 128q115 0 203 72.5t111 183.5h-314q-35 0 -55 31q-18 32 -1 63l147 277q-47 13 -91 13q-132 0 -226 -94t-94 -226t94 -226 t226 -94zM1856 128q132 0 226 94t94 226t-94 226t-226 94q-60 0 -121 -24l174 -260q15 -23 10 -49t-27 -40q-15 -11 -36 -11q-35 0 -53 29l-174 260q-93 -95 -93 -225q0 -132 94 -226t226 -94z" />
<glyph unicode="&#xf21d;" d="M1408 0q0 -63 -61.5 -113.5t-164 -81t-225 -46t-253.5 -15.5t-253.5 15.5t-225 46t-164 81t-61.5 113.5q0 49 33 88.5t91 66.5t118 44.5t131 29.5q26 5 48 -10.5t26 -41.5q5 -26 -10.5 -48t-41.5 -26q-58 -10 -106 -23.5t-76.5 -25.5t-48.5 -23.5t-27.5 -19.5t-8.5 -12 q3 -11 27 -26.5t73 -33t114 -32.5t160.5 -25t201.5 -10t201.5 10t160.5 25t114 33t73 33.5t27 27.5q-1 4 -8.5 11t-27.5 19t-48.5 23.5t-76.5 25t-106 23.5q-26 4 -41.5 26t-10.5 48q4 26 26 41.5t48 10.5q71 -12 131 -29.5t118 -44.5t91 -66.5t33 -88.5zM1024 896v-384 q0 -26 -19 -45t-45 -19h-64v-384q0 -26 -19 -45t-45 -19h-256q-26 0 -45 19t-19 45v384h-64q-26 0 -45 19t-19 45v384q0 53 37.5 90.5t90.5 37.5h384q53 0 90.5 -37.5t37.5 -90.5zM928 1280q0 -93 -65.5 -158.5t-158.5 -65.5t-158.5 65.5t-65.5 158.5t65.5 158.5t158.5 65.5 t158.5 -65.5t65.5 -158.5z" />
<glyph unicode="&#xf21e;" horiz-adv-x="1792" d="M1280 512h305q-5 -6 -10 -10.5t-9 -7.5l-3 -4l-623 -600q-18 -18 -44 -18t-44 18l-624 602q-5 2 -21 20h369q22 0 39.5 13.5t22.5 34.5l70 281l190 -667q6 -20 23 -33t39 -13q21 0 38 13t23 33l146 485l56 -112q18 -35 57 -35zM1792 940q0 -145 -103 -300h-369l-111 221 q-8 17 -25.5 27t-36.5 8q-45 -5 -56 -46l-129 -430l-196 686q-6 20 -23.5 33t-39.5 13t-39 -13.5t-22 -34.5l-116 -464h-423q-103 155 -103 300q0 220 127 344t351 124q62 0 126.5 -21.5t120 -58t95.5 -68.5t76 -68q36 36 76 68t95.5 68.5t120 58t126.5 21.5q224 0 351 -124 t127 -344z" />
<glyph unicode="&#xf221;" horiz-adv-x="1280" d="M1152 960q0 -221 -147.5 -384.5t-364.5 -187.5v-260h224q14 0 23 -9t9 -23v-64q0 -14 -9 -23t-23 -9h-224v-224q0 -14 -9 -23t-23 -9h-64q-14 0 -23 9t-9 23v224h-224q-14 0 -23 9t-9 23v64q0 14 9 23t23 9h224v260q-150 16 -271.5 103t-186 224t-52.5 292 q11 134 80.5 249t182 188t245.5 88q170 19 319 -54t236 -212t87 -306zM128 960q0 -185 131.5 -316.5t316.5 -131.5t316.5 131.5t131.5 316.5t-131.5 316.5t-316.5 131.5t-316.5 -131.5t-131.5 -316.5z" />
<glyph unicode="&#xf222;" horiz-adv-x="1792" d="M1280 1504q0 14 9 23t23 9h416q26 0 45 -19t19 -45v-416q0 -14 -9 -23t-23 -9h-64q-14 0 -23 9t-9 23v262l-419 -420q87 -104 129.5 -236.5t30.5 -276.5q-22 -250 -200.5 -431t-428.5 -206q-163 -17 -314 39.5t-256.5 162t-162 256.5t-39.5 314q25 250 206 428.5 t431 200.5q144 12 276.5 -30.5t236.5 -129.5l419 419h-261q-14 0 -23 9t-9 23v64zM704 -128q117 0 223.5 45.5t184 123t123 184t45.5 223.5t-45.5 223.5t-123 184t-184 123t-223.5 45.5t-223.5 -45.5t-184 -123t-123 -184t-45.5 -223.5t45.5 -223.5t123 -184t184 -123 t223.5 -45.5z" />
<glyph unicode="&#xf223;" horiz-adv-x="1280" d="M830 1220q145 -72 233.5 -210.5t88.5 -305.5q0 -221 -147.5 -384.5t-364.5 -187.5v-132h96q14 0 23 -9t9 -23v-64q0 -14 -9 -23t-23 -9h-96v-96q0 -14 -9 -23t-23 -9h-64q-14 0 -23 9t-9 23v96h-96q-14 0 -23 9t-9 23v64q0 14 9 23t23 9h96v132q-217 24 -364.5 187.5 t-147.5 384.5q0 167 88.5 305.5t233.5 210.5q-165 96 -228 273q-6 16 3.5 29.5t26.5 13.5h69q21 0 29 -20q44 -106 140 -171t214 -65t214 65t140 171q8 20 37 20h61q17 0 26.5 -13.5t3.5 -29.5q-63 -177 -228 -273zM576 256q185 0 316.5 131.5t131.5 316.5t-131.5 316.5 t-316.5 131.5t-316.5 -131.5t-131.5 -316.5t131.5 -316.5t316.5 -131.5z" />
<glyph unicode="&#xf224;" d="M1024 1504q0 14 9 23t23 9h288q26 0 45 -19t19 -45v-288q0 -14 -9 -23t-23 -9h-64q-14 0 -23 9t-9 23v134l-254 -255q126 -158 126 -359q0 -221 -147.5 -384.5t-364.5 -187.5v-132h96q14 0 23 -9t9 -23v-64q0 -14 -9 -23t-23 -9h-96v-96q0 -14 -9 -23t-23 -9h-64 q-14 0 -23 9t-9 23v96h-96q-14 0 -23 9t-9 23v64q0 14 9 23t23 9h96v132q-149 16 -270.5 103t-186.5 223.5t-53 291.5q16 204 160 353.5t347 172.5q118 14 228 -19t198 -103l255 254h-134q-14 0 -23 9t-9 23v64zM576 256q185 0 316.5 131.5t131.5 316.5t-131.5 316.5 t-316.5 131.5t-316.5 -131.5t-131.5 -316.5t131.5 -316.5t316.5 -131.5z" />
<glyph unicode="&#xf225;" horiz-adv-x="1792" d="M1280 1504q0 14 9 23t23 9h288q26 0 45 -19t19 -45v-288q0 -14 -9 -23t-23 -9h-64q-14 0 -23 9t-9 23v134l-254 -255q126 -158 126 -359q0 -221 -147.5 -384.5t-364.5 -187.5v-132h96q14 0 23 -9t9 -23v-64q0 -14 -9 -23t-23 -9h-96v-96q0 -14 -9 -23t-23 -9h-64 q-14 0 -23 9t-9 23v96h-96q-14 0 -23 9t-9 23v64q0 14 9 23t23 9h96v132q-217 24 -364.5 187.5t-147.5 384.5q0 201 126 359l-52 53l-101 -111q-9 -10 -22 -10.5t-23 7.5l-48 44q-10 8 -10.5 21.5t8.5 23.5l105 115l-111 112v-134q0 -14 -9 -23t-23 -9h-64q-14 0 -23 9 t-9 23v288q0 26 19 45t45 19h288q14 0 23 -9t9 -23v-64q0 -14 -9 -23t-23 -9h-133l106 -107l86 94q9 10 22 10.5t23 -7.5l48 -44q10 -8 10.5 -21.5t-8.5 -23.5l-90 -99l57 -56q158 126 359 126t359 -126l255 254h-134q-14 0 -23 9t-9 23v64zM832 256q185 0 316.5 131.5 t131.5 316.5t-131.5 316.5t-316.5 131.5t-316.5 -131.5t-131.5 -316.5t131.5 -316.5t316.5 -131.5z" />
<glyph unicode="&#xf226;" horiz-adv-x="1792" d="M1790 1007q12 -155 -52.5 -292t-186 -224t-271.5 -103v-260h224q14 0 23 -9t9 -23v-64q0 -14 -9 -23t-23 -9h-224v-224q0 -14 -9 -23t-23 -9h-64q-14 0 -23 9t-9 23v224h-512v-224q0 -14 -9 -23t-23 -9h-64q-14 0 -23 9t-9 23v224h-224q-14 0 -23 9t-9 23v64q0 14 9 23 t23 9h224v260q-150 16 -271.5 103t-186 224t-52.5 292q17 206 164.5 356.5t352.5 169.5q206 21 377 -94q171 115 377 94q205 -19 352.5 -169.5t164.5 -356.5zM896 647q128 131 128 313t-128 313q-128 -131 -128 -313t128 -313zM576 512q115 0 218 57q-154 165 -154 391 q0 224 154 391q-103 57 -218 57q-185 0 -316.5 -131.5t-131.5 -316.5t131.5 -316.5t316.5 -131.5zM1152 128v260q-137 15 -256 94q-119 -79 -256 -94v-260h512zM1216 512q185 0 316.5 131.5t131.5 316.5t-131.5 316.5t-316.5 131.5q-115 0 -218 -57q154 -167 154 -391 q0 -226 -154 -391q103 -57 218 -57z" />
<glyph unicode="&#xf227;" horiz-adv-x="1920" d="M1536 1120q0 14 9 23t23 9h288q26 0 45 -19t19 -45v-288q0 -14 -9 -23t-23 -9h-64q-14 0 -23 9t-9 23v134l-254 -255q76 -95 107.5 -214t9.5 -247q-31 -182 -166 -312t-318 -156q-210 -29 -384.5 80t-241.5 300q-117 6 -221 57.5t-177.5 133t-113.5 192.5t-32 230 q9 135 78 252t182 191.5t248 89.5q118 14 227.5 -19t198.5 -103l255 254h-134q-14 0 -23 9t-9 23v64q0 14 9 23t23 9h288q26 0 45 -19t19 -45v-288q0 -14 -9 -23t-23 -9h-64q-14 0 -23 9t-9 23v134l-254 -255q59 -74 93 -169q182 -9 328 -124l255 254h-134q-14 0 -23 9 t-9 23v64zM1024 704q0 20 -4 58q-162 -25 -271 -150t-109 -292q0 -20 4 -58q162 25 271 150t109 292zM128 704q0 -168 111 -294t276 -149q-3 29 -3 59q0 210 135 369.5t338 196.5q-53 120 -163.5 193t-245.5 73q-185 0 -316.5 -131.5t-131.5 -316.5zM1088 -128 q185 0 316.5 131.5t131.5 316.5q0 168 -111 294t-276 149q3 -29 3 -59q0 -210 -135 -369.5t-338 -196.5q53 -120 163.5 -193t245.5 -73z" />
<glyph unicode="&#xf228;" horiz-adv-x="2048" d="M1664 1504q0 14 9 23t23 9h288q26 0 45 -19t19 -45v-288q0 -14 -9 -23t-23 -9h-64q-14 0 -23 9t-9 23v134l-254 -255q76 -95 107.5 -214t9.5 -247q-32 -180 -164.5 -310t-313.5 -157q-223 -34 -409 90q-117 -78 -256 -93v-132h96q14 0 23 -9t9 -23v-64q0 -14 -9 -23 t-23 -9h-96v-96q0 -14 -9 -23t-23 -9h-64q-14 0 -23 9t-9 23v96h-96q-14 0 -23 9t-9 23v64q0 14 9 23t23 9h96v132q-155 17 -279.5 109.5t-187 237.5t-39.5 307q25 187 159.5 322.5t320.5 164.5q224 34 410 -90q146 97 320 97q201 0 359 -126l255 254h-134q-14 0 -23 9 t-9 23v64zM896 391q128 131 128 313t-128 313q-128 -131 -128 -313t128 -313zM128 704q0 -185 131.5 -316.5t316.5 -131.5q117 0 218 57q-154 167 -154 391t154 391q-101 57 -218 57q-185 0 -316.5 -131.5t-131.5 -316.5zM1216 256q185 0 316.5 131.5t131.5 316.5 t-131.5 316.5t-316.5 131.5q-117 0 -218 -57q154 -167 154 -391t-154 -391q101 -57 218 -57z" />
<glyph unicode="&#xf229;" horiz-adv-x="1792" d="M1728 1536q26 0 45 -19t19 -45v-416q0 -14 -9 -23t-23 -9h-64q-14 0 -23 9t-9 23v262l-229 -230l156 -156q9 -10 9 -23t-9 -22l-46 -46q-9 -9 -22 -9t-23 9l-156 157l-99 -100q87 -104 129.5 -236.5t30.5 -276.5q-22 -250 -200.5 -431t-428.5 -206q-163 -17 -314 39.5 t-256.5 162t-162 256.5t-39.5 314q25 250 206 428.5t431 200.5q144 12 276.5 -30.5t236.5 -129.5l99 99l-156 156q-9 10 -9 23t9 22l46 46q9 9 22 9t23 -9l156 -156l229 229h-261q-14 0 -23 9t-9 23v64q0 14 9 23t23 9h416zM1280 448q0 117 -45.5 223.5t-123 184t-184 123 t-223.5 45.5t-223.5 -45.5t-184 -123t-123 -184t-45.5 -223.5t45.5 -223.5t123 -184t184 -123t223.5 -45.5t223.5 45.5t184 123t123 184t45.5 223.5z" />
<glyph unicode="&#xf22a;" horiz-adv-x="1280" d="M640 892q217 -24 364.5 -187.5t147.5 -384.5q0 -167 -87 -306t-236 -212t-319 -54q-133 15 -245.5 88t-182 188t-80.5 249q-12 155 52.5 292t186 224t271.5 103v132h-160q-14 0 -23 9t-9 23v64q0 14 9 23t23 9h160v165l-92 -92q-10 -9 -23 -9t-22 9l-46 46q-9 9 -9 22 t9 23l202 201q19 19 45 19t45 -19l202 -201q9 -10 9 -23t-9 -22l-46 -46q-9 -9 -22 -9t-23 9l-92 92v-165h160q14 0 23 -9t9 -23v-64q0 -14 -9 -23t-23 -9h-160v-132zM576 -128q185 0 316.5 131.5t131.5 316.5t-131.5 316.5t-316.5 131.5t-316.5 -131.5t-131.5 -316.5 t131.5 -316.5t316.5 -131.5z" />
<glyph unicode="&#xf22b;" horiz-adv-x="2048" d="M2029 685q19 -19 19 -45t-19 -45l-294 -294q-9 -10 -22.5 -10t-22.5 10l-45 45q-10 9 -10 22.5t10 22.5l185 185h-294v-224q0 -14 -9 -23t-23 -9h-64q-14 0 -23 9t-9 23v224h-131q-12 -119 -67 -226t-139 -183.5t-196.5 -121.5t-234.5 -45q-180 0 -330.5 91t-234.5 247 t-74 337q8 162 94 300t226.5 219.5t302.5 85.5q166 4 310.5 -71.5t235.5 -208.5t107 -296h131v224q0 14 9 23t23 9h64q14 0 23 -9t9 -23v-224h294l-185 185q-10 9 -10 22.5t10 22.5l45 45q9 10 22.5 10t22.5 -10zM640 128q104 0 198.5 40.5t163.5 109.5t109.5 163.5 t40.5 198.5t-40.5 198.5t-109.5 163.5t-163.5 109.5t-198.5 40.5t-198.5 -40.5t-163.5 -109.5t-109.5 -163.5t-40.5 -198.5t40.5 -198.5t109.5 -163.5t163.5 -109.5t198.5 -40.5z" />
<glyph unicode="&#xf22c;" horiz-adv-x="1280" d="M1152 960q0 -221 -147.5 -384.5t-364.5 -187.5v-612q0 -14 -9 -23t-23 -9h-64q-14 0 -23 9t-9 23v612q-217 24 -364.5 187.5t-147.5 384.5q0 117 45.5 223.5t123 184t184 123t223.5 45.5t223.5 -45.5t184 -123t123 -184t45.5 -223.5zM576 512q185 0 316.5 131.5 t131.5 316.5t-131.5 316.5t-316.5 131.5t-316.5 -131.5t-131.5 -316.5t131.5 -316.5t316.5 -131.5z" />
<glyph unicode="&#xf22d;" horiz-adv-x="1792" />
<glyph unicode="&#xf22e;" horiz-adv-x="1792" />
<glyph unicode="&#xf22f;" horiz-adv-x="1792" />
<glyph unicode="&#xf230;" d="M1451 1408q35 0 60 -25t25 -60v-1366q0 -35 -25 -60t-60 -25h-391v595h199l30 232h-229v148q0 56 23.5 84t91.5 28l122 1v207q-63 9 -178 9q-136 0 -217.5 -80t-81.5 -226v-171h-200v-232h200v-595h-735q-35 0 -60 25t-25 60v1366q0 35 25 60t60 25h1366z" />
<glyph unicode="&#xf231;" horiz-adv-x="1280" d="M0 939q0 108 37.5 203.5t103.5 166.5t152 123t185 78t202 26q158 0 294 -66.5t221 -193.5t85 -287q0 -96 -19 -188t-60 -177t-100 -149.5t-145 -103t-189 -38.5q-68 0 -135 32t-96 88q-10 -39 -28 -112.5t-23.5 -95t-20.5 -71t-26 -71t-32 -62.5t-46 -77.5t-62 -86.5 l-14 -5l-9 10q-15 157 -15 188q0 92 21.5 206.5t66.5 287.5t52 203q-32 65 -32 169q0 83 52 156t132 73q61 0 95 -40.5t34 -102.5q0 -66 -44 -191t-44 -187q0 -63 45 -104.5t109 -41.5q55 0 102 25t78.5 68t56 95t38 110.5t20 111t6.5 99.5q0 173 -109.5 269.5t-285.5 96.5 q-200 0 -334 -129.5t-134 -328.5q0 -44 12.5 -85t27 -65t27 -45.5t12.5 -30.5q0 -28 -15 -73t-37 -45q-2 0 -17 3q-51 15 -90.5 56t-61 94.5t-32.5 108t-11 106.5z" />
<glyph unicode="&#xf232;" d="M985 562q13 0 97.5 -44t89.5 -53q2 -5 2 -15q0 -33 -17 -76q-16 -39 -71 -65.5t-102 -26.5q-57 0 -190 62q-98 45 -170 118t-148 185q-72 107 -71 194v8q3 91 74 158q24 22 52 22q6 0 18 -1.5t19 -1.5q19 0 26.5 -6.5t15.5 -27.5q8 -20 33 -88t25 -75q0 -21 -34.5 -57.5 t-34.5 -46.5q0 -7 5 -15q34 -73 102 -137q56 -53 151 -101q12 -7 22 -7q15 0 54 48.5t52 48.5zM782 32q127 0 243.5 50t200.5 134t134 200.5t50 243.5t-50 243.5t-134 200.5t-200.5 134t-243.5 50t-243.5 -50t-200.5 -134t-134 -200.5t-50 -243.5q0 -203 120 -368l-79 -233 l242 77q158 -104 345 -104zM782 1414q153 0 292.5 -60t240.5 -161t161 -240.5t60 -292.5t-60 -292.5t-161 -240.5t-240.5 -161t-292.5 -60q-195 0 -365 94l-417 -134l136 405q-108 178 -108 389q0 153 60 292.5t161 240.5t240.5 161t292.5 60z" />
<glyph unicode="&#xf233;" horiz-adv-x="1792" d="M128 128h1024v128h-1024v-128zM128 640h1024v128h-1024v-128zM1696 192q0 40 -28 68t-68 28t-68 -28t-28 -68t28 -68t68 -28t68 28t28 68zM128 1152h1024v128h-1024v-128zM1696 704q0 40 -28 68t-68 28t-68 -28t-28 -68t28 -68t68 -28t68 28t28 68zM1696 1216 q0 40 -28 68t-68 28t-68 -28t-28 -68t28 -68t68 -28t68 28t28 68zM1792 384v-384h-1792v384h1792zM1792 896v-384h-1792v384h1792zM1792 1408v-384h-1792v384h1792z" />
<glyph unicode="&#xf234;" horiz-adv-x="2048" d="M704 640q-159 0 -271.5 112.5t-112.5 271.5t112.5 271.5t271.5 112.5t271.5 -112.5t112.5 -271.5t-112.5 -271.5t-271.5 -112.5zM1664 512h352q13 0 22.5 -9.5t9.5 -22.5v-192q0 -13 -9.5 -22.5t-22.5 -9.5h-352v-352q0 -13 -9.5 -22.5t-22.5 -9.5h-192q-13 0 -22.5 9.5 t-9.5 22.5v352h-352q-13 0 -22.5 9.5t-9.5 22.5v192q0 13 9.5 22.5t22.5 9.5h352v352q0 13 9.5 22.5t22.5 9.5h192q13 0 22.5 -9.5t9.5 -22.5v-352zM928 288q0 -52 38 -90t90 -38h256v-238q-68 -50 -171 -50h-874q-121 0 -194 69t-73 190q0 53 3.5 103.5t14 109t26.5 108.5 t43 97.5t62 81t85.5 53.5t111.5 20q19 0 39 -17q79 -61 154.5 -91.5t164.5 -30.5t164.5 30.5t154.5 91.5q20 17 39 17q132 0 217 -96h-223q-52 0 -90 -38t-38 -90v-192z" />
<glyph unicode="&#xf235;" horiz-adv-x="2048" d="M704 640q-159 0 -271.5 112.5t-112.5 271.5t112.5 271.5t271.5 112.5t271.5 -112.5t112.5 -271.5t-112.5 -271.5t-271.5 -112.5zM1781 320l249 -249q9 -9 9 -23q0 -13 -9 -22l-136 -136q-9 -9 -22 -9q-14 0 -23 9l-249 249l-249 -249q-9 -9 -23 -9q-13 0 -22 9l-136 136 q-9 9 -9 22q0 14 9 23l249 249l-249 249q-9 9 -9 23q0 13 9 22l136 136q9 9 22 9q14 0 23 -9l249 -249l249 249q9 9 23 9q13 0 22 -9l136 -136q9 -9 9 -22q0 -14 -9 -23zM1283 320l-181 -181q-37 -37 -37 -91q0 -53 37 -90l83 -83q-21 -3 -44 -3h-874q-121 0 -194 69 t-73 190q0 53 3.5 103.5t14 109t26.5 108.5t43 97.5t62 81t85.5 53.5t111.5 20q19 0 39 -17q154 -122 319 -122t319 122q20 17 39 17q28 0 57 -6q-28 -27 -41 -50t-13 -56q0 -54 37 -91z" />
<glyph unicode="&#xf236;" horiz-adv-x="2048" d="M256 512h1728q26 0 45 -19t19 -45v-448h-256v256h-1536v-256h-256v1216q0 26 19 45t45 19h128q26 0 45 -19t19 -45v-704zM832 832q0 106 -75 181t-181 75t-181 -75t-75 -181t75 -181t181 -75t181 75t75 181zM2048 576v64q0 159 -112.5 271.5t-271.5 112.5h-704 q-26 0 -45 -19t-19 -45v-384h1152z" />
<glyph unicode="&#xf237;" d="M1536 1536l-192 -448h192v-192h-274l-55 -128h329v-192h-411l-357 -832l-357 832h-411v192h329l-55 128h-274v192h192l-192 448h256l323 -768h378l323 768h256zM768 320l108 256h-216z" />
<glyph unicode="&#xf238;" d="M1088 1536q185 0 316.5 -93.5t131.5 -226.5v-896q0 -130 -125.5 -222t-305.5 -97l213 -202q16 -15 8 -35t-30 -20h-1056q-22 0 -30 20t8 35l213 202q-180 5 -305.5 97t-125.5 222v896q0 133 131.5 226.5t316.5 93.5h640zM768 192q80 0 136 56t56 136t-56 136t-136 56 t-136 -56t-56 -136t56 -136t136 -56zM1344 768v512h-1152v-512h1152z" />
<glyph unicode="&#xf239;" d="M1088 1536q185 0 316.5 -93.5t131.5 -226.5v-896q0 -130 -125.5 -222t-305.5 -97l213 -202q16 -15 8 -35t-30 -20h-1056q-22 0 -30 20t8 35l213 202q-180 5 -305.5 97t-125.5 222v896q0 133 131.5 226.5t316.5 93.5h640zM288 224q66 0 113 47t47 113t-47 113t-113 47 t-113 -47t-47 -113t47 -113t113 -47zM704 768v512h-544v-512h544zM1248 224q66 0 113 47t47 113t-47 113t-113 47t-113 -47t-47 -113t47 -113t113 -47zM1408 768v512h-576v-512h576z" />
<glyph unicode="&#xf23a;" horiz-adv-x="1792" d="M1792 204v-209h-642v209h134v926h-6l-314 -1135h-243l-310 1135h-8v-926h135v-209h-538v209h69q21 0 43 19.5t22 37.5v881q0 18 -22 40t-43 22h-69v209h672l221 -821h6l223 821h670v-209h-71q-19 0 -41 -22t-22 -40v-881q0 -18 21.5 -37.5t41.5 -19.5h71z" />
<glyph unicode="&#xf23b;" horiz-adv-x="1792" />
<glyph unicode="&#xf23c;" horiz-adv-x="1792" />
<glyph unicode="&#xf23d;" horiz-adv-x="1792" />
<glyph unicode="&#xf23e;" horiz-adv-x="1792" />
<glyph unicode="&#xf500;" horiz-adv-x="1792" />
</font>
</defs></svg> 
<?xml version="1.0" standalone="no"?>
<!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd">
<svg xmlns="http://www.w3.org/2000/svg">
<metadata>Generated by Fontastic.me</metadata>
<defs>
<font id="slick" horiz-adv-x="512">
<font-face font-family="slick" units-per-em="512" ascent="480" descent="-32"/>
<missing-glyph horiz-adv-x="512" />

<glyph unicode="&#8594;" d="M241 113l130 130c4 4 6 8 6 13 0 5-2 9-6 13l-130 130c-3 3-7 5-12 5-5 0-10-2-13-5l-29-30c-4-3-6-7-6-12 0-5 2-10 6-13l87-88-87-88c-4-3-6-8-6-13 0-5 2-9 6-12l29-30c3-3 8-5 13-5 5 0 9 2 12 5z m234 143c0-40-9-77-29-110-20-34-46-60-80-80-33-20-70-29-110-29-40 0-77 9-110 29-34 20-60 46-80 80-20 33-29 70-29 110 0 40 9 77 29 110 20 34 46 60 80 80 33 20 70 29 110 29 40 0 77-9 110-29 34-20 60-46 80-80 20-33 29-70 29-110z"/>
<glyph unicode="&#8592;" d="M296 113l29 30c4 3 6 7 6 12 0 5-2 10-6 13l-87 88 87 88c4 3 6 8 6 13 0 5-2 9-6 12l-29 30c-3 3-8 5-13 5-5 0-9-2-12-5l-130-130c-4-4-6-8-6-13 0-5 2-9 6-13l130-130c3-3 7-5 12-5 5 0 10 2 13 5z m179 143c0-40-9-77-29-110-20-34-46-60-80-80-33-20-70-29-110-29-40 0-77 9-110 29-34 20-60 46-80 80-20 33-29 70-29 110 0 40 9 77 29 110 20 34 46 60 80 80 33 20 70 29 110 29 40 0 77-9 110-29 34-20 60-46 80-80 20-33 29-70 29-110z"/>
<glyph unicode="&#8226;" d="M475 256c0-40-9-77-29-110-20-34-46-60-80-80-33-20-70-29-110-29-40 0-77 9-110 29-34 20-60 46-80 80-20 33-29 70-29 110 0 40 9 77 29 110 20 34 46 60 80 80 33 20 70 29 110 29 40 0 77-9 110-29 34-20 60-46 80-80 20-33 29-70 29-110z"/>
<glyph unicode="&#97;" d="M475 439l0-128c0-5-1-9-5-13-4-4-8-5-13-5l-128 0c-8 0-13 3-17 11-3 7-2 14 4 20l40 39c-28 26-62 39-100 39-20 0-39-4-57-11-18-8-33-18-46-32-14-13-24-28-32-46-7-18-11-37-11-57 0-20 4-39 11-57 8-18 18-33 32-46 13-14 28-24 46-32 18-7 37-11 57-11 23 0 44 5 64 15 20 9 38 23 51 42 2 1 4 3 7 3 3 0 5-1 7-3l39-39c2-2 3-3 3-6 0-2-1-4-2-6-21-25-46-45-76-59-29-14-60-20-93-20-30 0-58 5-85 17-27 12-51 27-70 47-20 19-35 43-47 70-12 27-17 55-17 85 0 30 5 58 17 85 12 27 27 51 47 70 19 20 43 35 70 47 27 12 55 17 85 17 28 0 55-5 81-15 26-11 50-26 70-45l37 37c6 6 12 7 20 4 8-4 11-9 11-17z"/>
</font></defs></svg>
<!DOCTYPE html>
<html lang="en">

  <head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content="">
    <meta name="author" content="">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700;800;900&display=swap" rel="stylesheet">

    <title>GROUP 3</title>

    <!-- Bootstrap core CSS -->
    <link href="vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">


    <!-- Additional CSS Files -->
    <link rel="stylesheet" href="assets/css/fontawesome.css">
    <link rel="stylesheet" href="assets/css/templatemo-digimedia-v1.css">
    <link rel="stylesheet" href="assets/css/animated.css">
    <link rel="stylesheet" href="assets/css/owl.css">
<!--

TemplateMo 568 DigiMedia

https://templatemo.com/tm-568-digimedia

-->
  </head>

<body>

  <!-- ***** Preloader Start ***** -->
  <div id="js-preloader" class="js-preloader">
    <div class="preloader-inner">
      <span class="dot"></span>
      <div class="dots">
        <span></span>
        <span></span>
        <span></span>
      </div>
    </div>
  </div>
  <!-- ***** Preloader End ***** -->

  <!-- Pre-header Starts -->
  <div class="pre-header">
    <div class="container">
      <div class="row">
        <div class="col-lg-8 col-sm-8 col-7">
          <ul class="info">
            <li><a href="#"><i class="fa fa-envelope"></i>mnl@eac.edu.ph</a></li>
            <li><a href="#"><i class="fa fa-phone"></i>123456789</a></li>
          </ul>
        </div>
        <div class="col-lg-4 col-sm-4 col-5">
          <ul class="social-media">
          </ul>
        </div>
      </div>
    </div>
  </div>
  <!-- Pre-header End -->

  <!-- ***** Header Area Start ***** -->
  <header class="header-area header-sticky wow slideInDown" data-wow-duration="0.75s" data-wow-delay="0s">
    <div class="container">
      <div class="row">
        <div class="col-12">
          <nav class="main-nav">
            <!-- ***** Logo Start ***** -->
            <a href="index.html"> </a>
            <!-- ***** Menu Start ***** -->
            <ul class="nav">
              <li class="scroll-to-section"><a href="#top" class="active">Home</a></li>
              <li class="scroll-to-section"><a href="#about">About</a></li>
              <li class="scroll-to-section"><a href="#services">Activities</a></li>
              <li class="scroll-to-section"><a href="#portfolio">Contact</a></li>
              <li class="scroll-to-section"><a href="#blog">Content</a></li> 
            </ul>        
            <a class='menu-trigger'>
                <span>Menu</span>
            </a>
            <!-- ***** Menu End ***** -->
          </nav>
        </div>
      </div>
    </div>
  </header>
  <!-- ***** Header Area End ***** -->

  <div class="main-banner wow fadeIn" id="top" data-wow-duration="1s" data-wow-delay="0.5s">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <div class="row">
            <div class="col-lg-6 align-self-center">
              <div class="left-content show-up header-text wow fadeInLeft" data-wow-duration="1s" data-wow-delay="1s">
                <div class="row">
                  <div class="col-lg-12">
                    <h6>GROUP 3</h6>
                    <h2>General Chemistry</h2>
                    <p>Welcome to our General Chemistry website! This platform is dedicated to helping students explore the fascinating world of chemistry.</p>
                  </div>
                  <div class="col-lg-12">
                    <div class="border-first-button scroll-to-section">
                      <a href="#about">Get Started</a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-lg-6">
              <div class="right-image wow fadeInRight" data-wow-duration="1s" data-wow-delay="0.5s">
                <img src="assets/images/basta3.png" alt=""
              div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div id="about" class="about section">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <div class="row">
            <div class="col-lg-6">
              <div class="about-left-image  wow fadeInLeft" data-wow-duration="1s" data-wow-delay="0.5s">
                <img src="assets/images/opo4.png" alt="" height="500" width="400">
              </div>
            </div>
            <div class="col-lg-6 align-self-center  wow fadeInRight" data-wow-duration="1s" data-wow-delay="0.5s">
              <div class="about-right-content">
                <div class="section-heading">
                  <h6>About Us</h6>
                  <h4>General <em>Chemistry</em></h4>
                  <div class="line-dec"></div>
                </div>
                <p> We are dedicated to providing students with an interactive and comprehensive platform to explore the world of chemistry. Our website offers a variety of resources, including hands-on experiments, detailed learning modules, and step-by-step tutorials designed to simplify complex concepts.</p>
                <div class="row">
                  <div class="col-lg-4 col-sm-4">
                    <div class="skill-item first-skill-item wow fadeIn" data-wow-duration="1s" data-wow-delay="0s">
                      <div class="progress" data-percentage="90">
                        <span class="progress-left">
                          <span class="progress-bar"></span>
                        </span>
                        <span class="progress-right">
                          <span class="progress-bar"></span>
                        </span>
                        <div class="progress-value">
                          <div>
                            90%<br>
                            <span>Experimets</span>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="col-lg-4 col-sm-4">
                    <div class="skill-item second-skill-item wow fadeIn" data-wow-duration="1s" data-wow-delay="0s">
                      <div class="progress" data-percentage="80">
                        <span class="progress-left">
                          <span class="progress-bar"></span>
                        </span>
                        <span class="progress-right">
                          <span class="progress-bar"></span>
                        </span>
                        <div class="progress-value">
                          <div>
                            80%<br>
                            <span>Tutorials</span>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="col-lg-4 col-sm-4">
                    <div class="skill-item third-skill-item wow fadeIn" data-wow-duration="1s" data-wow-delay="0s">
                      <div class="progress" data-percentage="80">
                        <span class="progress-left">
                          <span class="progress-bar"></span>
                        </span>
                        <span class="progress-right">
                          <span class="progress-bar"></span>
                        </span>
                        <div class="progress-value">
                          <div>
                            80%<br>
                            <span>Modules</span>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div> 
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div id="services" class="services section">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <div class="section-heading  wow fadeInDown" data-wow-duration="1s" data-wow-delay="0.5s">
            <h6>Our Services</h6>
            <h4>All About <em>Chemistry</em></h4>
            <div class="line-dec"></div>
          </div>
        </div>
        <div class="col-lg-12">
          <div class="naccs">
            <div class="grid">
              <div class="row">
                <div class="col-lg-12">
                  <div class="menu">
                    <div class="first-thumb active">
                      <div class="thumb">
                        <span class="icon"><img src="assets/images/service-icon-01.png" alt=""></span>
                       Stoichiometry
                      </div>
                    </div>
                    <div>
                      <div class="thumb">                 
                        <span class="icon"><img src="assets/images/service-icon-02.png" alt=""></span>
                        Molecular Geometry
                      </div>
                    </div>
                    <div>
                      <div class="thumb">                 
                        <span class="icon"><img src="assets/images/service-icon-03.png" alt=""></span>
                        Tutorials
                      </div>
                    </div>
                    <div>
                      <div class="thumb">                 
                        <span class="icon"><img src="assets/images/service-icon-04.png" alt=""></span>
                        Paper Chromatography
                      </div>
                    </div>
                    <div class="last-thumb">
                      <div class="thumb">                 
                        <span class="icon"><img src="assets/images/service-icon-01.png" alt=""></span>
                        Modules
                      </div>
                    </div>
                  </div>
                </div> 
                <div class="col-lg-12">
                  <ul class="nacc">
                    <li class="active">
                      <div>
                        <div class="thumb">
                          <div class="row">
                            <div class="col-lg-6 align-self-center">
                              <div class="left-text">
                                <h4>Stoichiometry</h4>
                                <p>Stoichiometry is a branch of chemistry that deals with the calculation of reactants and products in chemical reactions. The term comes from the Greek words "stoicheion" (meaning element) and "metron" (meaning measure), and it involves the measurement of elements and compounds involved in a reaction
                                <div class="ticks-list"><span><i class="fa fa-check"></i> Mole Concept</span> <span><i class="fa fa-check"></i> Percent Yield</span> <span><i class="fa fa-check"></i> Mole Ratios</span>
                                  <span><i class="fa fa-check"></i> Balancing Chemical Equations</span> <span><i class="fa fa-check"></i> Limiting Reactants</span> <span><i class="fa fa-check"></i> Reactants</span></div>
                              </div>
                            </div>
                            <div class="col-lg-6 align-self-center">
                              <div class="right-image">
                                <img src="assets/images/basta8.png" alt="">
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </li>
                    <li>
                      <div>
                        <div class="thumb">
                          <div class="row">
                            <div class="col-lg-6 align-self-center">
                              <div class="left-text">
                                <h4>Molecular Geometry</h4> 
                                <p>Molecular geometry refers to the three-dimensional arrangement of atoms in a molecule and the spatial relationship between the atoms within it. Understanding molecular geometry is essential in chemistry because it helps explain many physical and chemical properties of substances, such as their reactivity, polarity, phase of matter, color, magnetism, and biological activity.</p>
                                <div class="ticks-list"><span><i class="fa fa-check"></i> Molecular Polarity</span> <span><i class="fa fa-check"></i> Electron Pairs</span> <span><i class="fa fa-check"></i> Bonding</span>
                                  <span><i class="fa fa-check"></i> Geometries</span> <span><i class="fa fa-check"></i> VSEPR Theory</span> <span><i class="fa fa-check"></i> Applications</span></div>
                              </div>
                            </div>
                            <div class="col-lg-6 align-self-center">
                              <div class="right-image">
                                <img src="assets/images/basta7.png" alt="">
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </li>
                    <li>
                      <div>
                        <div class="thumb">
                          <div class="row">
                            <div class="col-lg-6 align-self-center">
                              <div class="left-text">
                                <h4>Tutorials</h4>
                                <p>This includes educational videos and detailed, in-depth explanations about various topics in chemistry, providing a comprehensive understanding of the subject.</p>
                                <div class="ticks-list"><span><i class="fa fa-check"></i> Topics</span> <span><i class="fa fa-check"></i> Definitions</span> <span><i class="fa fa-check"></i> </span>
                                  <span><i class="fa fa-check"></i> Videos</span> <span><i class="fa fa-check"></i> Explanations</span> <span><i class="fa fa-check"></i> </span></div>
                              </div>
                            </div>
                            <div class="col-lg-6 align-self-center">
                              <div class="right-image">
                                <img src="assets/images/basta9.png" alt="">
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </li>
                    <li>
                      <div>
                        <div class="thumb">
                          <div class="row">
                            <div class="col-lg-6 align-self-center">
                              <div class="left-text">
                                <h4>Paper Chromatography</h4>
                                <p>Paper chromatography is a simple and effective technique used to separate and analyze different components of a mixture. It is widely used in chemistry, biology, and environmental science to identify substances, such as dyes, inks, or plant pigments. The method relies on the differences in the rates at which components in a mixture move through a special type of paper when exposed to a solvent.</p>
                                <div class="ticks-list"><span><i class="fa fa-check"></i> Dye</span> <span><i class="fa fa-check"></i> Inks</span> <span><i class="fa fa-check"></i> Chromatography</span>
                                  <span><i class="fa fa-check"></i> Pigments</span> <span><i class="fa fa-check"></i> Seperation</span> <span><i class="fa fa-check"></i> Compounds</span></div>
                              </div>
                            </div>
                            <div class="col-lg-6 align-self-center">
                              <div class="right-image">
                                <img src="assets/images/opo1.png" alt="">
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </li>
                    <li>
                      <div>
                        <div class="thumb">
                          <div class="row">
                            <div class="col-lg-6 align-self-center">
                              <div class="left-text">
                                <h4>Modules<h4>
                                </p>a collection of interactive modules designed to support your learning and help you master key concepts in chemistry. Each module includes detailed explanations, engaging videos, and practical examples to enhance your understanding of the subject. Whether you're reviewing fundamentals or tackling advanced topics, our resources are here to guide you every step of the way.</p>
                              </div>
                            </div>
                            <div class="col-lg-6 align-self-center">
                              <div class="right-image">
                                <img src="assets/images/opo2.png" alt="">
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </li>
                  </ul>
                </div>          
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  
  <div id="free-quote" class="free-quote">
    <div class="container">
      <div class="row">
        <div class="col-lg-4 offset-lg-4">
          <div class="section-heading  wow fadeIn" data-wow-duration="1s" data-wow-delay="0.3s">
            <h6>Join Our Study</h6>
            <h4>Grow With Us Now</h4>
            <div class="line-dec"></div>
          </div>
        </div>
        <div class="col-lg-8 offset-lg-2  wow fadeIn" data-wow-duration="1s" data-wow-delay="0.8s">
          <form id="search" action="#" method="GET">
            <div class="row">
              <div class="col-lg-4 col-sm-4">
                <fieldset>
                  <input type="web" name="web" class="website" placeholder="General Chemistry" autocomplete="on" required>
                </fieldset>
              </div>
              <div class="col-lg-4 col-sm-4">
                <fieldset>
                  <input type="address" name="address" class="email" placeholder="Email Address..." autocomplete="on" required>
                </fieldset>
              </div>
              <div class="col-lg-4 col-sm-4">
                <fieldset>
                  <button type="submit" class="main-button">Join</button>
                </fieldset>
              </div>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>


  <div id="portfolio" class="our-portfolio section">
    <div class="container">
      <div class="row">
        <div class="col-lg-5">
          <div class="section-heading wow fadeInLeft" data-wow-duration="1s" data-wow-delay="0.3s">
            <h6>Contact US</h6>
            <h4>Get In Touch With Us <em>Now</em></h4>
            <div class="line-dec"></div>
          </div>
        </div>
      </div>
    </div>
    <div class="container-fluid wow fadeIn" data-wow-duration="1s" data-wow-delay="0.7s">
      <div class="row">
        <div class="col-lg-12">
          <div class="loop owl-carousel">
            <div class="item">
              <a href="#">
                <div class="portfolio-item">
                <div class="thumb">
                  <img src="assets/images/ALDEMA.png" alt="">
                </div>
                <div class="down-content">
                   <a href="https://www.facebook.com/justinmeiguel.aldema" target="_justin Meiguel Aldema"> <h4>Justin Meiguel Aldema</h4> </a>
                  <span>justinmieguel.aldema.mnl</span>
                </div>
              </div>
              </a>  
            </div>
            <div class="item">
              <a href="#">
                <div class="portfolio-item">
                <div class="thumb">
                  <img src="assets/images/DAYAG.png" alt="">
                </div>
                <div class="down-content">
                  <a href="https://www.facebook.com/marillaine.dayag" target="_Marillaine Francisco Dayag"> <h4>Marillaine Francisco Dayag</h4> </a>
                  <span>marillaine.dayag.mnl</span>
                </div>
              </div>
              </a>  
            </div>
            <div class="item">
              <a href="#">
                <div class="portfolio-item">
                <div class="thumb">
                  <img src="assets/images/ESPEJO.jpeg" alt="">
                </div>
                <div class="down-content">
                  <a href="https://www.facebook.com/rosette.espejo.1" target="_Anesza Rosette Cometa Espejo"> <h4>Anesza Rosette Cometa Espejo</h4> </a>
                  <span>aneszarosette.espejo.mnl</span>
                </div>
              </div>
              </a>  
            </div>
            <div class="item">
              <a href="#">
                <div class="portfolio-item">
                <div class="thumb">
                  <img src="assets/images/MACABAGO.jpg" alt="">
                </div>
                <div class="down-content">
                  <a href="https://www.facebook.com/norhanida.macabago.2024" target="_Norhanida Macadato Macabago"> <h4>Norhanida Macadato Macabago</h4> </a>
                  <span>norhanida.macabago.mnl</span>
                </div>
              </div>
              </a>  
            </div>
            <div class="item">
              <a href="#">
                <div class="portfolio-item">
                <div class="thumb">
                  <img src="assets/images/RABANO.jpeg" alt="">
                </div>
                <div class="down-content">
                  <a href="https://www.facebook.com/claire.danielle.g.rabano" target="_Claire Danielle Garde Rabano"> <h4>Claire Danielle Garde Rabano</h4> </a>
                  <span>clairedanielle.rabano.mnl@eac.edu.ph</span>
                </div>
              </div>
              </a>
            </div>
            <div class="item">
              <a href="#">
                <div class="portfolio-item">
                <div class="thumb">
                  <img src="assets/images/SISON.png" alt="">
                </div>
                <div class="down-content">
                  <a href="https://www.facebook.com/iyam.sison.7" target="_I-Yam Tresquia Yumol Sison"> <h4>I-Yam Tresquia Yumol Sison</h4> </a>
                  <span>i-yamtresqua.sison.mnl</span>
               </div>
              </div>
              </a> 
            </div> 
            <div class="item">
              <a href="#">
                <div class="portfolio-item">
                <div class="thumb">
                  <img src="assets/images/SY.jpeg" alt="">
               </div>
               <div class="down-content">
                  <a href="https://www.facebook.com/charzellesyy" target="_Anne Charzelle Trinidad Sy"> <h4>Anne Charzelle Trinidad Sy</h4> </a>
                  <span>annecharzelle.sy.mnl</span>
                </div>
               </div>
               </a>  
            </div>
            <div class="item">
              <a href="#">
                <div class="portfolio-item">
                <div class="thumb">
                  <img src="assets/images/TALARO.png" alt="">
               </div>
               <div class="down-content">
                  <a href="https://www.facebook.com/sheyneanica.talaro" target="_Sheyne Anica Granetin Talaro"> <h4>Sheyne Anica Granetin Talaro</h4> </a>
                   <span>sheyneanica.talaro.mnl</span>
                </div>
               </div>
              </a>  
             </div>
            </div>
           </div>
          </div>
         </a>
        </div>
      </div>

  
  <div id="blog" class="blog">
    <div class="container">
      <div class="row">
        <div class="col-lg-4 offset-lg-4  wow fadeInDown" data-wow-duration="1s" data-wow-delay="0.3s">
          <div class="section-heading">
            <h6>Contents</h6>
            <h4>Check Our <em>Contents</em></h4>
            <div class="line-dec"></div>
          </div>
        </div>
        <div class="col-lg-6 show-up wow fadeInUp" data-wow-duration="1s" data-wow-delay="0.3s">
          <div class="blog-post">
            <div class="thumb">
              <a href="#"><img src="assets/images/Picture13.jpg" alt=""></a>
            </div>
            <div class="down-content">.
              <a href="file:///C:/Users/User-PC/Downloads/Paper%20Chromatography.pdf" target="_Paper Chromatography"> <span class="category">Paper Chromatography</span>
              <a href="#"><h4></h4> 
              <span class="author"><img src="assets/images/basta9.png" alt=""></span>
              <div class=""></a></div>
            </div>
          </div>
        </div>
        <div class="col-lg-6 wow fadeInUp" data-wow-duration="1s" data-wow-delay="0.3s">
          <div class="blog-posts">
            <div class="row">
              <div class="col-lg-12">
                <div class="post-item">
                  <div class="thumb">
                    <a href="#"><img src="assets/images/wow.jpg" alt=""></a>
                  </div>
                  <div class="right-content">
                    <a href="file:///C:/Users/User-PC/Downloads/A%20Balancing%20Act.pdf" target="_A Balancing Act"> <span class="category">A Balancing Act</span>
                    <span class="date">2024</span>
                    <a href="#"><h4>Stoichiometry, is the quantitative study of substances as they participate in chemical reactions, is a fundamental chemical concept.</h4></a>
                    <p></p>
                  </div>
                </div>
              </div>
              <div class="col-lg-12">
                <div class="post-item">
                  <div class="thumb">
                    <a href="#"><img src="assets/images/wow1.jpg" alt=""></a>
                  </div>
                  <div class="right-content">
                    <a href="file:///C:/Users/User-PC/Downloads/Molecular%20Modelling%20and%20Geometry%20in%20Real%20Life.pdf" target="_Molecular Modelling and Geometry"> <span class="category">Molecular Modelling and Geometry</span>
                    <span class="date">2024</span>
                    <a href="#"><h4>Molecular geometry, also referred to as the molecular structure, is the three-dimensional structure or arrangement of atoms in a molecule.</h4></a>
                    <p></p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>  

  <footer>
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <p> 
          <br> <a href="https://templatemo.com" target="_parent" title="free css templates"></a></p>
        </div>
      </div>
    </div>
  </footer>


  <!-- Scripts -->
  <script src="vendor/jquery/jquery.min.js"></script>
  <script src="vendor/bootstrap/js/bootstrap.bundle.min.js"></script>
  <script src="assets/js/owl-carousel.js"></script>
  <script src="assets/js/animation.js"></script>
  <script src="assets/js/imagesloaded.js"></script>
  <script src="assets/js/custom.js"></script>

</body>
</html>
<!DOCTYPE html>
<html lang="en">

  <head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content="">
    <meta name="author" content="">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700;800;900&display=swap" rel="stylesheet">

    <title>GROUP 3</title>

    <!-- Bootstrap core CSS -->
    <link href="vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">


    <!-- Additional CSS Files -->
    <link rel="stylesheet" href="assets/css/fontawesome.css">
    <link rel="stylesheet" href="assets/css/templatemo-digimedia-v1.css">
    <link rel="stylesheet" href="assets/css/animated.css">
    <link rel="stylesheet" href="assets/css/owl.css">
<!--

TemplateMo 568 DigiMedia

https://templatemo.com/tm-568-digimedia

-->
  </head>

<body>

  <!-- ***** Preloader Start ***** -->
  <div id="js-preloader" class="js-preloader">
    <div class="preloader-inner">
      <span class="dot"></span>
      <div class="dots">
        <span></span>
        <span></span>
        <span></span>
      </div>
    </div>
  </div>
  <!-- ***** Preloader End ***** -->

  <div class="intro-banner">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <img src="assets/images/logo-v1.png" alt="">
          <h1>GROUP 3</h1>
          <h4>Please choose one of the three variations below.</h4>
          <div class="first-button scroll-to-section">
            <a href="#demos">Choose Demo</a>
          </div>
        </div>
      </div>
    </div>
  </div>


  <div class="demos" id="demos">
    <div class="container">
      <div class="row">
        <div class="col-lg-4">
          <div class="demo-item">
            <a href="homepage_1.html"><img src="assets/images/demo-1.jpg" alt="DigiMedia - variation 1"></a>
            <h4>Version 1</h4>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="demo-item">
            <a href="homepage_2.html"><img src="assets/images/demo-2.jpg" alt="DigiMedia - variation 2"></a>
            <h4>Version 2</h4>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="demo-item">
            <a href="homepage_3.html"><img src="assets/images/demo-3.jpg" alt="DigiMedia - variation 3"></a>
            <h4>Version 3</h4>
          </div>
        </div>
      </div>
    </div>
  </div>


  <footer>
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <p>Copyright © 2022 DigiMedia Co., Ltd. All Rights Reserved. 
          <br>Design: <a href="https://templatemo.com" target="_parent" title="free css templates">TemplateMo</a></p>
        </div>
      </div>
    </div>
  </footer>


  <!-- Scripts -->
  <script src="vendor/jquery/jquery.min.js"></script>
  <script src="vendor/bootstrap/js/bootstrap.bundle.min.js"></script>
  <script src="assets/js/owl-carousel.js"></script>
  <script src="assets/js/animation.js"></script>
  <script src="assets/js/imagesloaded.js"></script>
  <script src="assets/js/custom.js"></script>

</body>

</html>
