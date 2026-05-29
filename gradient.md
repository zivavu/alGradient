--_gradient-blend-mode: normal;
--_gradient-blur: 0px;

background: radial-gradient(at 11% 21.6%, #0b0b3d 0px, transparent 50%), radial-gradient(at 21.2% 78.4%, #12011f 0px, transparent 50%), radial-gradient(at 50.9% 21.8%, #0b011f 0px, transparent 50%), radial-gradient(at 70% 80%, #031121 0px, transparent 50%), radial-gradient(at 90.5% 21.8%, #361359 0px, transparent 50%) #000000;;
mix-blend-mode: var(--_gradient-blend-mode);

    
.frosted-backdrop {
backdrop-filter: blur(var(--_gradient-blur)) contrast(100%) brightness(100%);
-webkit-backdrop-filter: blur(var(--_gradient-blur)) contrast(100%) brightness(100%);
}

--angle: 45deg;
--gradient: oklab(19.5% 0.007 -0.11), oklab(14.5% 0.051 -0.064), oklab(13.3% 0.034 -0.072), oklab(17.4% -0.016 -0.045), oklab(28.5% 0.075 -0.12);

background: linear-gradient(var(--angle), var(--gradient))
