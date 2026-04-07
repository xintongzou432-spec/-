VITE_GEMINI_API_KEY=

node_modules
dist
.DS_Store
.env

<!doctype html>
<html lang="zh-CN">
  <head>
    <meta charset="UTF-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1.0"
    />
    <meta
      name="description"
      content="一个围绕情绪叙事、呼吸引导与书写疗愈展开的沉浸式网页实验。"
    />
    <title>情绪星海</title>
    <script>
      window.tailwind = { config: {} };
    </script>
    <script src="https://cdn.tailwindcss.com"></script>
  </head>
  <body>
    <div id="root"></div>
    <script type="module" src="/src/main.jsx"></script>
  </body>
</html>

{
  "name": "emotion-sea",
  "private": true,
  "version": "0.1.0",
  "type": "module",
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "preview": "vite preview"
  },
  "dependencies": {
    "lucide-react": "^0.453.0",
    "react": "^18.3.1",
    "react-dom": "^18.3.1"
  },
  "devDependencies": {
    "vite": "^5.4.10"
  }
}

{
  "name": "emotion-sea",
  "version": "0.1.0",
  "lockfileVersion": 3,
  "requires": true,
  "packages": {
    "": {
      "name": "emotion-sea",
      "version": "0.1.0",
      "dependencies": {
        "lucide-react": "^0.453.0",
        "react": "^18.3.1",
        "react-dom": "^18.3.1"
      },
      "devDependencies": {
        "vite": "^5.4.10"
      }
    },
    "node_modules/@esbuild/aix-ppc64": {
      "version": "0.21.5",
      "resolved": "https://registry.npmjs.org/@esbuild/aix-ppc64/-/aix-ppc64-0.21.5.tgz",
      "integrity": "sha512-1SDgH6ZSPTlggy1yI6+Dbkiz8xzpHJEVAlF/AM1tHPLsf5STom9rwtjE4hKAF20FfXXNTFqEYXyJNWh1GiZedQ==",
      "cpu": [
        "ppc64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "aix"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/android-arm": {
      "version": "0.21.5",
      "resolved": "https://registry.npmjs.org/@esbuild/android-arm/-/android-arm-0.21.5.tgz",
      "integrity": "sha512-vCPvzSjpPHEi1siZdlvAlsPxXl7WbOVUBBAowWug4rJHb68Ox8KualB+1ocNvT5fjv6wpkX6o/iEpbDrf68zcg==",
      "cpu": [
        "arm"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "android"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/android-arm64": {
      "version": "0.21.5",
      "resolved": "https://registry.npmjs.org/@esbuild/android-arm64/-/android-arm64-0.21.5.tgz",
      "integrity": "sha512-c0uX9VAUBQ7dTDCjq+wdyGLowMdtR/GoC2U5IYk/7D1H1JYC0qseD7+11iMP2mRLN9RcCMRcjC4YMclCzGwS/A==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "android"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/android-x64": {
      "version": "0.21.5",
      "resolved": "https://registry.npmjs.org/@esbuild/android-x64/-/android-x64-0.21.5.tgz",
      "integrity": "sha512-D7aPRUUNHRBwHxzxRvp856rjUHRFW1SdQATKXH2hqA0kAZb1hKmi02OpYRacl0TxIGz/ZmXWlbZgjwWYaCakTA==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "android"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/darwin-arm64": {
      "version": "0.21.5",
      "resolved": "https://registry.npmjs.org/@esbuild/darwin-arm64/-/darwin-arm64-0.21.5.tgz",
      "integrity": "sha512-DwqXqZyuk5AiWWf3UfLiRDJ5EDd49zg6O9wclZ7kUMv2WRFr4HKjXp/5t8JZ11QbQfUS6/cRCKGwYhtNAY88kQ==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "darwin"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/darwin-x64": {
      "version": "0.21.5",
      "resolved": "https://registry.npmjs.org/@esbuild/darwin-x64/-/darwin-x64-0.21.5.tgz",
      "integrity": "sha512-se/JjF8NlmKVG4kNIuyWMV/22ZaerB+qaSi5MdrXtd6R08kvs2qCN4C09miupktDitvh8jRFflwGFBQcxZRjbw==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "darwin"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/freebsd-arm64": {
      "version": "0.21.5",
      "resolved": "https://registry.npmjs.org/@esbuild/freebsd-arm64/-/freebsd-arm64-0.21.5.tgz",
      "integrity": "sha512-5JcRxxRDUJLX8JXp/wcBCy3pENnCgBR9bN6JsY4OmhfUtIHe3ZW0mawA7+RDAcMLrMIZaf03NlQiX9DGyB8h4g==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "freebsd"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/freebsd-x64": {
      "version": "0.21.5",
      "resolved": "https://registry.npmjs.org/@esbuild/freebsd-x64/-/freebsd-x64-0.21.5.tgz",
      "integrity": "sha512-J95kNBj1zkbMXtHVH29bBriQygMXqoVQOQYA+ISs0/2l3T9/kj42ow2mpqerRBxDJnmkUDCaQT/dfNXWX/ZZCQ==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "freebsd"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-arm": {
      "version": "0.21.5",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-arm/-/linux-arm-0.21.5.tgz",
      "integrity": "sha512-bPb5AHZtbeNGjCKVZ9UGqGwo8EUu4cLq68E95A53KlxAPRmUyYv2D6F0uUI65XisGOL1hBP5mTronbgo+0bFcA==",
      "cpu": [
        "arm"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-arm64": {
      "version": "0.21.5",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-arm64/-/linux-arm64-0.21.5.tgz",
      "integrity": "sha512-ibKvmyYzKsBeX8d8I7MH/TMfWDXBF3db4qM6sy+7re0YXya+K1cem3on9XgdT2EQGMu4hQyZhan7TeQ8XkGp4Q==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-ia32": {
      "version": "0.21.5",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-ia32/-/linux-ia32-0.21.5.tgz",
      "integrity": "sha512-YvjXDqLRqPDl2dvRODYmmhz4rPeVKYvppfGYKSNGdyZkA01046pLWyRKKI3ax8fbJoK5QbxblURkwK/MWY18Tg==",
      "cpu": [
        "ia32"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-loong64": {
      "version": "0.21.5",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-loong64/-/linux-loong64-0.21.5.tgz",
      "integrity": "sha512-uHf1BmMG8qEvzdrzAqg2SIG/02+4/DHB6a9Kbya0XDvwDEKCoC8ZRWI5JJvNdUjtciBGFQ5PuBlpEOXQj+JQSg==",
      "cpu": [
        "loong64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-mips64el": {
      "version": "0.21.5",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-mips64el/-/linux-mips64el-0.21.5.tgz",
      "integrity": "sha512-IajOmO+KJK23bj52dFSNCMsz1QP1DqM6cwLUv3W1QwyxkyIWecfafnI555fvSGqEKwjMXVLokcV5ygHW5b3Jbg==",
      "cpu": [
        "mips64el"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-ppc64": {
      "version": "0.21.5",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-ppc64/-/linux-ppc64-0.21.5.tgz",
      "integrity": "sha512-1hHV/Z4OEfMwpLO8rp7CvlhBDnjsC3CttJXIhBi+5Aj5r+MBvy4egg7wCbe//hSsT+RvDAG7s81tAvpL2XAE4w==",
      "cpu": [
        "ppc64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-riscv64": {
      "version": "0.21.5",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-riscv64/-/linux-riscv64-0.21.5.tgz",
      "integrity": "sha512-2HdXDMd9GMgTGrPWnJzP2ALSokE/0O5HhTUvWIbD3YdjME8JwvSCnNGBnTThKGEB91OZhzrJ4qIIxk/SBmyDDA==",
      "cpu": [
        "riscv64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-s390x": {
      "version": "0.21.5",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-s390x/-/linux-s390x-0.21.5.tgz",
      "integrity": "sha512-zus5sxzqBJD3eXxwvjN1yQkRepANgxE9lgOW2qLnmr8ikMTphkjgXu1HR01K4FJg8h1kEEDAqDcZQtbrRnB41A==",
      "cpu": [
        "s390x"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-x64": {
      "version": "0.21.5",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-x64/-/linux-x64-0.21.5.tgz",
      "integrity": "sha512-1rYdTpyv03iycF1+BhzrzQJCdOuAOtaqHTWJZCWvijKD2N5Xu0TtVC8/+1faWqcP9iBCWOmjmhoH94dH82BxPQ==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/netbsd-x64": {
      "version": "0.21.5",
      "resolved": "https://registry.npmjs.org/@esbuild/netbsd-x64/-/netbsd-x64-0.21.5.tgz",
      "integrity": "sha512-Woi2MXzXjMULccIwMnLciyZH4nCIMpWQAs049KEeMvOcNADVxo0UBIQPfSmxB3CWKedngg7sWZdLvLczpe0tLg==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "netbsd"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/openbsd-x64": {
      "version": "0.21.5",
      "resolved": "https://registry.npmjs.org/@esbuild/openbsd-x64/-/openbsd-x64-0.21.5.tgz",
      "integrity": "sha512-HLNNw99xsvx12lFBUwoT8EVCsSvRNDVxNpjZ7bPn947b8gJPzeHWyNVhFsaerc0n3TsbOINvRP2byTZ5LKezow==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "openbsd"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/sunos-x64": {
      "version": "0.21.5",
      "resolved": "https://registry.npmjs.org/@esbuild/sunos-x64/-/sunos-x64-0.21.5.tgz",
      "integrity": "sha512-6+gjmFpfy0BHU5Tpptkuh8+uw3mnrvgs+dSPQXQOv3ekbordwnzTVEb4qnIvQcYXq6gzkyTnoZ9dZG+D4garKg==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "sunos"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/win32-arm64": {
      "version": "0.21.5",
      "resolved": "https://registry.npmjs.org/@esbuild/win32-arm64/-/win32-arm64-0.21.5.tgz",
      "integrity": "sha512-Z0gOTd75VvXqyq7nsl93zwahcTROgqvuAcYDUr+vOv8uHhNSKROyU961kgtCD1e95IqPKSQKH7tBTslnS3tA8A==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "win32"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/win32-ia32": {
      "version": "0.21.5",
      "resolved": "https://registry.npmjs.org/@esbuild/win32-ia32/-/win32-ia32-0.21.5.tgz",
      "integrity": "sha512-SWXFF1CL2RVNMaVs+BBClwtfZSvDgtL//G/smwAc5oVK/UPu2Gu9tIaRgFmYFFKrmg3SyAjSrElf0TiJ1v8fYA==",
      "cpu": [
        "ia32"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "win32"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/win32-x64": {
      "version": "0.21.5",
      "resolved": "https://registry.npmjs.org/@esbuild/win32-x64/-/win32-x64-0.21.5.tgz",
      "integrity": "sha512-tQd/1efJuzPC6rCFwEvLtci/xNFcTZknmXs98FYDfGE4wP9ClFV98nyKrzJKVPMhdDnjzLhdUyMX4PsQAPjwIw==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "win32"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@rollup/rollup-android-arm-eabi": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-android-arm-eabi/-/rollup-android-arm-eabi-4.60.1.tgz",
      "integrity": "sha512-d6FinEBLdIiK+1uACUttJKfgZREXrF0Qc2SmLII7W2AD8FfiZ9Wjd+rD/iRuf5s5dWrr1GgwXCvPqOuDquOowA==",
      "cpu": [
        "arm"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "android"
      ]
    },
    "node_modules/@rollup/rollup-android-arm64": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-android-arm64/-/rollup-android-arm64-4.60.1.tgz",
      "integrity": "sha512-YjG/EwIDvvYI1YvYbHvDz/BYHtkY4ygUIXHnTdLhG+hKIQFBiosfWiACWortsKPKU/+dUwQQCKQM3qrDe8c9BA==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "android"
      ]
    },
    "node_modules/@rollup/rollup-darwin-arm64": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-darwin-arm64/-/rollup-darwin-arm64-4.60.1.tgz",
      "integrity": "sha512-mjCpF7GmkRtSJwon+Rq1N8+pI+8l7w5g9Z3vWj4T7abguC4Czwi3Yu/pFaLvA3TTeMVjnu3ctigusqWUfjZzvw==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "darwin"
      ]
    },
    "node_modules/@rollup/rollup-darwin-x64": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-darwin-x64/-/rollup-darwin-x64-4.60.1.tgz",
      "integrity": "sha512-haZ7hJ1JT4e9hqkoT9R/19XW2QKqjfJVv+i5AGg57S+nLk9lQnJ1F/eZloRO3o9Scy9CM3wQ9l+dkXtcBgN5Ew==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "darwin"
      ]
    },
    "node_modules/@rollup/rollup-freebsd-arm64": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-freebsd-arm64/-/rollup-freebsd-arm64-4.60.1.tgz",
      "integrity": "sha512-czw90wpQq3ZsAVBlinZjAYTKduOjTywlG7fEeWKUA7oCmpA8xdTkxZZlwNJKWqILlq0wehoZcJYfBvOyhPTQ6w==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "freebsd"
      ]
    },
    "node_modules/@rollup/rollup-freebsd-x64": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-freebsd-x64/-/rollup-freebsd-x64-4.60.1.tgz",
      "integrity": "sha512-KVB2rqsxTHuBtfOeySEyzEOB7ltlB/ux38iu2rBQzkjbwRVlkhAGIEDiiYnO2kFOkJp+Z7pUXKyrRRFuFUKt+g==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "freebsd"
      ]
    },
    "node_modules/@rollup/rollup-linux-arm-gnueabihf": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-arm-gnueabihf/-/rollup-linux-arm-gnueabihf-4.60.1.tgz",
      "integrity": "sha512-L+34Qqil+v5uC0zEubW7uByo78WOCIrBvci69E7sFASRl0X7b/MB6Cqd1lky/CtcSVTydWa2WZwFuWexjS5o6g==",
      "cpu": [
        "arm"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-arm-musleabihf": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-arm-musleabihf/-/rollup-linux-arm-musleabihf-4.60.1.tgz",
      "integrity": "sha512-n83O8rt4v34hgFzlkb1ycniJh7IR5RCIqt6mz1VRJD6pmhRi0CXdmfnLu9dIUS6buzh60IvACM842Ffb3xd6Gg==",
      "cpu": [
        "arm"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-arm64-gnu": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-arm64-gnu/-/rollup-linux-arm64-gnu-4.60.1.tgz",
      "integrity": "sha512-Nql7sTeAzhTAja3QXeAI48+/+GjBJ+QmAH13snn0AJSNL50JsDqotyudHyMbO2RbJkskbMbFJfIJKWA6R1LCJQ==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-arm64-musl": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-arm64-musl/-/rollup-linux-arm64-musl-4.60.1.tgz",
      "integrity": "sha512-+pUymDhd0ys9GcKZPPWlFiZ67sTWV5UU6zOJat02M1+PiuSGDziyRuI/pPue3hoUwm2uGfxdL+trT6Z9rxnlMA==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-loong64-gnu": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-loong64-gnu/-/rollup-linux-loong64-gnu-4.60.1.tgz",
      "integrity": "sha512-VSvgvQeIcsEvY4bKDHEDWcpW4Yw7BtlKG1GUT4FzBUlEKQK0rWHYBqQt6Fm2taXS+1bXvJT6kICu5ZwqKCnvlQ==",
      "cpu": [
        "loong64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-loong64-musl": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-loong64-musl/-/rollup-linux-loong64-musl-4.60.1.tgz",
      "integrity": "sha512-4LqhUomJqwe641gsPp6xLfhqWMbQV04KtPp7/dIp0nzPxAkNY1AbwL5W0MQpcalLYk07vaW9Kp1PBhdpZYYcEw==",
      "cpu": [
        "loong64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-ppc64-gnu": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-ppc64-gnu/-/rollup-linux-ppc64-gnu-4.60.1.tgz",
      "integrity": "sha512-tLQQ9aPvkBxOc/EUT6j3pyeMD6Hb8QF2BTBnCQWP/uu1lhc9AIrIjKnLYMEroIz/JvtGYgI9dF3AxHZNaEH0rw==",
      "cpu": [
        "ppc64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-ppc64-musl": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-ppc64-musl/-/rollup-linux-ppc64-musl-4.60.1.tgz",
      "integrity": "sha512-RMxFhJwc9fSXP6PqmAz4cbv3kAyvD1etJFjTx4ONqFP9DkTkXsAMU4v3Vyc5BgzC+anz7nS/9tp4obsKfqkDHg==",
      "cpu": [
        "ppc64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-riscv64-gnu": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-riscv64-gnu/-/rollup-linux-riscv64-gnu-4.60.1.tgz",
      "integrity": "sha512-QKgFl+Yc1eEk6MmOBfRHYF6lTxiiiV3/z/BRrbSiW2I7AFTXoBFvdMEyglohPj//2mZS4hDOqeB0H1ACh3sBbg==",
      "cpu": [
        "riscv64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-riscv64-musl": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-riscv64-musl/-/rollup-linux-riscv64-musl-4.60.1.tgz",
      "integrity": "sha512-RAjXjP/8c6ZtzatZcA1RaQr6O1TRhzC+adn8YZDnChliZHviqIjmvFwHcxi4JKPSDAt6Uhf/7vqcBzQJy0PDJg==",
      "cpu": [
        "riscv64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-s390x-gnu": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-s390x-gnu/-/rollup-linux-s390x-gnu-4.60.1.tgz",
      "integrity": "sha512-wcuocpaOlaL1COBYiA89O6yfjlp3RwKDeTIA0hM7OpmhR1Bjo9j31G1uQVpDlTvwxGn2nQs65fBFL5UFd76FcQ==",
      "cpu": [
        "s390x"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-x64-gnu": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-x64-gnu/-/rollup-linux-x64-gnu-4.60.1.tgz",
      "integrity": "sha512-77PpsFQUCOiZR9+LQEFg9GClyfkNXj1MP6wRnzYs0EeWbPcHs02AXu4xuUbM1zhwn3wqaizle3AEYg5aeoohhg==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-x64-musl": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-x64-musl/-/rollup-linux-x64-musl-4.60.1.tgz",
      "integrity": "sha512-5cIATbk5vynAjqqmyBjlciMJl1+R/CwX9oLk/EyiFXDWd95KpHdrOJT//rnUl4cUcskrd0jCCw3wpZnhIHdD9w==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-openbsd-x64": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-openbsd-x64/-/rollup-openbsd-x64-4.60.1.tgz",
      "integrity": "sha512-cl0w09WsCi17mcmWqqglez9Gk8isgeWvoUZ3WiJFYSR3zjBQc2J5/ihSjpl+VLjPqjQ/1hJRcqBfLjssREQILw==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "openbsd"
      ]
    },
    "node_modules/@rollup/rollup-openharmony-arm64": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-openharmony-arm64/-/rollup-openharmony-arm64-4.60.1.tgz",
      "integrity": "sha512-4Cv23ZrONRbNtbZa37mLSueXUCtN7MXccChtKpUnQNgF010rjrjfHx3QxkS2PI7LqGT5xXyYs1a7LbzAwT0iCA==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "openharmony"
      ]
    },
    "node_modules/@rollup/rollup-win32-arm64-msvc": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-win32-arm64-msvc/-/rollup-win32-arm64-msvc-4.60.1.tgz",
      "integrity": "sha512-i1okWYkA4FJICtr7KpYzFpRTHgy5jdDbZiWfvny21iIKky5YExiDXP+zbXzm3dUcFpkEeYNHgQ5fuG236JPq0g==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "win32"
      ]
    },
    "node_modules/@rollup/rollup-win32-ia32-msvc": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-win32-ia32-msvc/-/rollup-win32-ia32-msvc-4.60.1.tgz",
      "integrity": "sha512-u09m3CuwLzShA0EYKMNiFgcjjzwqtUMLmuCJLeZWjjOYA3IT2Di09KaxGBTP9xVztWyIWjVdsB2E9goMjZvTQg==",
      "cpu": [
        "ia32"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "win32"
      ]
    },
    "node_modules/@rollup/rollup-win32-x64-gnu": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-win32-x64-gnu/-/rollup-win32-x64-gnu-4.60.1.tgz",
      "integrity": "sha512-k+600V9Zl1CM7eZxJgMyTUzmrmhB/0XZnF4pRypKAlAgxmedUA+1v9R+XOFv56W4SlHEzfeMtzujLJD22Uz5zg==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "win32"
      ]
    },
    "node_modules/@rollup/rollup-win32-x64-msvc": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-win32-x64-msvc/-/rollup-win32-x64-msvc-4.60.1.tgz",
      "integrity": "sha512-lWMnixq/QzxyhTV6NjQJ4SFo1J6PvOX8vUx5Wb4bBPsEb+8xZ89Bz6kOXpfXj9ak9AHTQVQzlgzBEc1SyM27xQ==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "win32"
      ]
    },
    "node_modules/@types/estree": {
      "version": "1.0.8",
      "resolved": "https://registry.npmjs.org/@types/estree/-/estree-1.0.8.tgz",
      "integrity": "sha512-dWHzHa2WqEXI/O1E9OjrocMTKJl2mSrEolh1Iomrv6U+JuNwaHXsXx9bLu5gG7BUWFIN0skIQJQ/L1rIex4X6w==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/esbuild": {
      "version": "0.21.5",
      "resolved": "https://registry.npmjs.org/esbuild/-/esbuild-0.21.5.tgz",
      "integrity": "sha512-mg3OPMV4hXywwpoDxu3Qda5xCKQi+vCTZq8S9J/EpkhB2HzKXq4SNFZE3+NK93JYxc8VMSep+lOUSC/RVKaBqw==",
      "dev": true,
      "hasInstallScript": true,
      "license": "MIT",
      "bin": {
        "esbuild": "bin/esbuild"
      },
      "engines": {
        "node": ">=12"
      },
      "optionalDependencies": {
        "@esbuild/aix-ppc64": "0.21.5",
        "@esbuild/android-arm": "0.21.5",
        "@esbuild/android-arm64": "0.21.5",
        "@esbuild/android-x64": "0.21.5",
        "@esbuild/darwin-arm64": "0.21.5",
        "@esbuild/darwin-x64": "0.21.5",
        "@esbuild/freebsd-arm64": "0.21.5",
        "@esbuild/freebsd-x64": "0.21.5",
        "@esbuild/linux-arm": "0.21.5",
        "@esbuild/linux-arm64": "0.21.5",
        "@esbuild/linux-ia32": "0.21.5",
        "@esbuild/linux-loong64": "0.21.5",
        "@esbuild/linux-mips64el": "0.21.5",
        "@esbuild/linux-ppc64": "0.21.5",
        "@esbuild/linux-riscv64": "0.21.5",
        "@esbuild/linux-s390x": "0.21.5",
        "@esbuild/linux-x64": "0.21.5",
        "@esbuild/netbsd-x64": "0.21.5",
        "@esbuild/openbsd-x64": "0.21.5",
        "@esbuild/sunos-x64": "0.21.5",
        "@esbuild/win32-arm64": "0.21.5",
        "@esbuild/win32-ia32": "0.21.5",
        "@esbuild/win32-x64": "0.21.5"
      }
    },
    "node_modules/fsevents": {
      "version": "2.3.3",
      "resolved": "https://registry.npmjs.org/fsevents/-/fsevents-2.3.3.tgz",
      "integrity": "sha512-5xoDfX+fL7faATnagmWPpbFtwh/R77WmMMqqHGS65C3vvB0YHrgF+B1YmZ3441tMj5n63k0212XNoJwzlhffQw==",
      "dev": true,
      "hasInstallScript": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "darwin"
      ],
      "engines": {
        "node": "^8.16.0 || ^10.6.0 || >=11.0.0"
      }
    },
    "node_modules/js-tokens": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/js-tokens/-/js-tokens-4.0.0.tgz",
      "integrity": "sha512-RdJUflcE3cUzKiMqQgsCu06FPu9UdIJO0beYbPhHN4k6apgJtifcoCtT9bcxOpYBtpD2kCM6Sbzg4CausW/PKQ==",
      "license": "MIT"
    },
    "node_modules/loose-envify": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/loose-envify/-/loose-envify-1.4.0.tgz",
      "integrity": "sha512-lyuxPGr/Wfhrlem2CL/UcnUc1zcqKAImBDzukY7Y5F/yQiNdko6+fRLevlw1HgMySw7f611UIY408EtxRSoK3Q==",
      "license": "MIT",
      "dependencies": {
        "js-tokens": "^3.0.0 || ^4.0.0"
      },
      "bin": {
        "loose-envify": "cli.js"
      }
    },
    "node_modules/lucide-react": {
      "version": "0.453.0",
      "resolved": "https://registry.npmjs.org/lucide-react/-/lucide-react-0.453.0.tgz",
      "integrity": "sha512-kL+RGZCcJi9BvJtzg2kshO192Ddy9hv3ij+cPrVPWSRzgCWCVazoQJxOjAwgK53NomL07HB7GPHW120FimjNhQ==",
      "license": "ISC",
      "peerDependencies": {
        "react": "^16.5.1 || ^17.0.0 || ^18.0.0 || ^19.0.0-rc"
      }
    },
    "node_modules/nanoid": {
      "version": "3.3.11",
      "resolved": "https://registry.npmjs.org/nanoid/-/nanoid-3.3.11.tgz",
      "integrity": "sha512-N8SpfPUnUp1bK+PMYW8qSWdl9U+wwNWI4QKxOYDy9JAro3WMX7p2OeVRF9v+347pnakNevPmiHhNmZ2HbFA76w==",
      "dev": true,
      "funding": [
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ],
      "license": "MIT",
      "bin": {
        "nanoid": "bin/nanoid.cjs"
      },
      "engines": {
        "node": "^10 || ^12 || ^13.7 || ^14 || >=15.0.1"
      }
    },
    "node_modules/picocolors": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/picocolors/-/picocolors-1.1.1.tgz",
      "integrity": "sha512-xceH2snhtb5M9liqDsmEw56le376mTZkEX/jEb/RxNFyegNul7eNslCXP9FDj/Lcu0X8KEyMceP2ntpaHrDEVA==",
      "dev": true,
      "license": "ISC"
    },
    "node_modules/postcss": {
      "version": "8.5.8",
      "resolved": "https://registry.npmjs.org/postcss/-/postcss-8.5.8.tgz",
      "integrity": "sha512-OW/rX8O/jXnm82Ey1k44pObPtdblfiuWnrd8X7GJ7emImCOstunGbXUpp7HdBrFQX6rJzn3sPT397Wp5aCwCHg==",
      "dev": true,
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/postcss/"
        },
        {
          "type": "tidelift",
          "url": "https://tidelift.com/funding/github/npm/postcss"
        },
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ],
      "license": "MIT",
      "dependencies": {
        "nanoid": "^3.3.11",
        "picocolors": "^1.1.1",
        "source-map-js": "^1.2.1"
      },
      "engines": {
        "node": "^10 || ^12 || >=14"
      }
    },
    "node_modules/react": {
      "version": "18.3.1",
      "resolved": "https://registry.npmjs.org/react/-/react-18.3.1.tgz",
      "integrity": "sha512-wS+hAgJShR0KhEvPJArfuPVN1+Hz1t0Y6n5jLrGQbkb4urgPE/0Rve+1kMB1v/oWgHgm4WIcV+i7F2pTVj+2iQ==",
      "license": "MIT",
      "dependencies": {
        "loose-envify": "^1.1.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/react-dom": {
      "version": "18.3.1",
      "resolved": "https://registry.npmjs.org/react-dom/-/react-dom-18.3.1.tgz",
      "integrity": "sha512-5m4nQKp+rZRb09LNH59GM4BxTh9251/ylbKIbpe7TpGxfJ+9kv6BLkLBXIjjspbgbnIBNqlI23tRnTWT0snUIw==",
      "license": "MIT",
      "dependencies": {
        "loose-envify": "^1.1.0",
        "scheduler": "^0.23.2"
      },
      "peerDependencies": {
        "react": "^18.3.1"
      }
    },
    "node_modules/rollup": {
      "version": "4.60.1",
      "resolved": "https://registry.npmjs.org/rollup/-/rollup-4.60.1.tgz",
      "integrity": "sha512-VmtB2rFU/GroZ4oL8+ZqXgSA38O6GR8KSIvWmEFv63pQ0G6KaBH9s07PO8XTXP4vI+3UJUEypOfjkGfmSBBR0w==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@types/estree": "1.0.8"
      },
      "bin": {
        "rollup": "dist/bin/rollup"
      },
      "engines": {
        "node": ">=18.0.0",
        "npm": ">=8.0.0"
      },
      "optionalDependencies": {
        "@rollup/rollup-android-arm-eabi": "4.60.1",
        "@rollup/rollup-android-arm64": "4.60.1",
        "@rollup/rollup-darwin-arm64": "4.60.1",
        "@rollup/rollup-darwin-x64": "4.60.1",
        "@rollup/rollup-freebsd-arm64": "4.60.1",
        "@rollup/rollup-freebsd-x64": "4.60.1",
        "@rollup/rollup-linux-arm-gnueabihf": "4.60.1",
        "@rollup/rollup-linux-arm-musleabihf": "4.60.1",
        "@rollup/rollup-linux-arm64-gnu": "4.60.1",
        "@rollup/rollup-linux-arm64-musl": "4.60.1",
        "@rollup/rollup-linux-loong64-gnu": "4.60.1",
        "@rollup/rollup-linux-loong64-musl": "4.60.1",
        "@rollup/rollup-linux-ppc64-gnu": "4.60.1",
        "@rollup/rollup-linux-ppc64-musl": "4.60.1",
        "@rollup/rollup-linux-riscv64-gnu": "4.60.1",
        "@rollup/rollup-linux-riscv64-musl": "4.60.1",
        "@rollup/rollup-linux-s390x-gnu": "4.60.1",
        "@rollup/rollup-linux-x64-gnu": "4.60.1",
        "@rollup/rollup-linux-x64-musl": "4.60.1",
        "@rollup/rollup-openbsd-x64": "4.60.1",
        "@rollup/rollup-openharmony-arm64": "4.60.1",
        "@rollup/rollup-win32-arm64-msvc": "4.60.1",
        "@rollup/rollup-win32-ia32-msvc": "4.60.1",
        "@rollup/rollup-win32-x64-gnu": "4.60.1",
        "@rollup/rollup-win32-x64-msvc": "4.60.1",
        "fsevents": "~2.3.2"
      }
    },
    "node_modules/scheduler": {
      "version": "0.23.2",
      "resolved": "https://registry.npmjs.org/scheduler/-/scheduler-0.23.2.tgz",
      "integrity": "sha512-UOShsPwz7NrMUqhR6t0hWjFduvOzbtv7toDH1/hIrfRNIDBnnBWd0CwJTGvTpngVlmwGCdP9/Zl/tVrDqcuYzQ==",
      "license": "MIT",
      "dependencies": {
        "loose-envify": "^1.1.0"
      }
    },
    "node_modules/source-map-js": {
      "version": "1.2.1",
      "resolved": "https://registry.npmjs.org/source-map-js/-/source-map-js-1.2.1.tgz",
      "integrity": "sha512-UXWMKhLOwVKb728IUtQPXxfYU+usdybtUrK/8uGE8CQMvrhOpwvzDBwj0QhSL7MQc7vIsISBG8VQ8+IDQxpfQA==",
      "dev": true,
      "license": "BSD-3-Clause",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/vite": {
      "version": "5.4.21",
      "resolved": "https://registry.npmjs.org/vite/-/vite-5.4.21.tgz",
      "integrity": "sha512-o5a9xKjbtuhY6Bi5S3+HvbRERmouabWbyUcpXXUA1u+GNUKoROi9byOJ8M0nHbHYHkYICiMlqxkg1KkYmm25Sw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "esbuild": "^0.21.3",
        "postcss": "^8.4.43",
        "rollup": "^4.20.0"
      },
      "bin": {
        "vite": "bin/vite.js"
      },
      "engines": {
        "node": "^18.0.0 || >=20.0.0"
      },
      "funding": {
        "url": "https://github.com/vitejs/vite?sponsor=1"
      },
      "optionalDependencies": {
        "fsevents": "~2.3.3"
      },
      "peerDependencies": {
        "@types/node": "^18.0.0 || >=20.0.0",
        "less": "*",
        "lightningcss": "^1.21.0",
        "sass": "*",
        "sass-embedded": "*",
        "stylus": "*",
        "sugarss": "*",
        "terser": "^5.4.0"
      },
      "peerDependenciesMeta": {
        "@types/node": {
          "optional": true
        },
        "less": {
          "optional": true
        },
        "lightningcss": {
          "optional": true
        },
        "sass": {
          "optional": true
        },
        "sass-embedded": {
          "optional": true
        },
        "stylus": {
          "optional": true
        },
        "sugarss": {
          "optional": true
        },
        "terser": {
          "optional": true
        }
      }
    }
  }
}

# 情绪星海

当前目录已经补成一个可运行的 Vite + React 项目，核心界面源码仍然来自 [情绪.txt](./情绪.txt)。

## 启动

1. 安装依赖：`npm install`
2. 启动开发环境：`npm run dev`
3. 打包：`npm run build`

## 说明

- `情绪.txt` 不是普通说明文档，而是一份完整度很高的 React 组件源码。
- `vite.config.js` 里加了一个自定义 loader，把 `情绪.txt` 当作 JSX 模块编译，所以暂时不需要手工改名成 `.jsx`。
- 用户写下的内容和星海参数会保存到浏览器 `localStorage`。
- 如果不配置 `VITE_GEMINI_API_KEY`，提交故事时会直接回退到默认标题，不会因为空 key 反复请求。

## 仍然依赖外部资源

- Tailwind 通过 CDN 注入。
- 字体通过 Google Fonts 拉取。
- 背景音乐来自外部音频链接。
- 如果需要 AI 标题，还要额外提供 Gemini API Key。

import { readFile } from 'node:fs/promises';
import { defineConfig, transformWithEsbuild } from 'vite';

function emotionTextLoader() {
  return {
    name: 'emotion-text-loader',
    enforce: 'pre',
    async load(id) {
      const [filepath] = id.split('?');
      if (!filepath.endsWith('/情绪.txt')) {
        return null;
      }

      const source = await readFile(filepath, 'utf8');
      return transformWithEsbuild(source, filepath, {
        loader: 'jsx',
        jsx: 'automatic',
      });
    },
  };
}

export default defineConfig({
  plugins: [emotionTextLoader()],
  server: {
    host: '0.0.0.0',
    port: 5173,
  },
});

import React, { useState, useEffect, useRef, useCallback, useMemo } from 'react';
import { Play, Wind, Sun, Star, ArrowRight, X, Heart, Volume2, VolumeX, ChevronLeft, ChevronRight, SlidersHorizontal, Flame, Feather, Maximize, Palette, Activity, Music } from 'lucide-react';

// --- 常量与预设数据 ---
const STAGES = {
  GATE: 'gate',
  INTRO: 'intro',
  CASES: 'cases',
  MEMORY: 'memory',
  DIARY_PROMPT: 'diary_prompt',
  CREATE: 'create',
  OUTRO: 'outro',
};

// “同龄人的焦虑”置于第一位
const INITIAL_CASES = [
  { id: 'c6', title: "同龄人的焦虑", text: "我发现人总是很容易陷入某种焦虑之中，关于学业、关于家庭、关于事业，最近我的焦虑其实来自于同龄人。说实话，我已经有很多次同龄焦虑了。在这个信息爆炸的时代，我们接受着来自各种渠道的各种声音和消息，看到了各种人，各种生活。身为00后的一代，有人年少成名，声名显赫；有人考入高校，前程似锦；有人在自己的专业领域绽放光彩；有人早早踏入社会，吃得百苦。而像我这样不上不下，高不成低不就，依旧拿着父母生活费迷茫度日，忧心未来的也有很多。\n\n但每每看到这些优秀同龄人的生活，似乎总觉得自己差了不少。就像回到小时候听到父母口中说别人家的孩子那样，不禁感慨，我怎么就没有活成那样呢？这中间是不是出了什么差错？" },
  { id: 'c7', title: "敏感的我", text: "很早就习惯了，对环境过度觉察，对坏天气感到成倍的沮丧，在一米外嗅到尴尬的味道，在半分钟的沉默里如坐针毡。“你太敏感了”，朋友这么说，老师这么说，妈妈也这么说，我太敏感了！朋友眼中的毛毛雨，却使我鞋袜都湿透。情绪像雨后泥泞和水汽，我忘我地感受，却反复地品尝痛苦。于是不知道从哪天起，我藏起了我汹涌的情绪，把自己伪装成面带笑容积极乐观的大人形象。我擅长感受，却拙于开口。我常常不太喜欢这样的自己，是我“想太多”了吗？\n\n不是的，不是的，坚强才不是敏感的反义词，我想麻木才是。我想人不会因为一场大雨就死掉，而我更害怕变成苟活在伞下的无聊的大人。我有多讨厌暴雨天，就有多喜欢暴雨天。我感激我充沛的感知力和表达欲，仍能欣喜地伸手触碰枝桠间投下的阳光，小心翼翼地接住一只飞鸟的羽毛，为宿舍楼下被领养的小猫欢呼雀跃，饱有拥抱他人的热情和能力。敏感就像倾盆大雨，而我是不撑伞的人。那祝大家能够手中有伞，也有不撑伞看花落的勇敢。" },
  { id: 'c1', title: "友情中的异位", text: "我们曾经形影不离。直到有天，我看到她发的朋友圈，合照里有所有人，唯独没有我。我点了个赞，关掉手机，那种感觉就像在热闹的舞池里突然被按下了静音键。我没问，她也没说，后来我们就像两艘慢慢驶离的船，再也没有了联系。" },
  { id: 'c2', title: "亲情中的高压", text: "每次视频电话，电话那头总是那句：‘我们都是为你好’，那一刻，我就像一个被塞满棉花的布娃娃，所有想反驳的话都变成了无声的叹息。我很想大喊‘我长大了’，但我只是说：‘知道了，挂了’" },
  { id: 'c3', title: "爱情中的失语", text: "分手那天，他把东西都搬走了。房间空了，但我却觉得异常拥挤，因为到处都塞满了他留下的习惯。我看着空荡荡的衣柜，很想问一句：‘你真的努力过吗’但我只是回了一个字：‘嗯’。" },
  { id: 'c4', title: "学业中的迷雾", text: "自习室的灯亮到凌晨两点，我翻着永远背不完的重点，突然不知道自己为了什么在拼命。周围的人都在谈论保研和实习，而我像是一个在迷雾里踩着跑步机的人，精疲力尽，却还在原地。" },
  { id: 'c5', title: "社交中的内耗", text: "聚会结束后的第一件事，是在脑海里疯狂重播自己刚才说过的每一句话。‘我是不是说错话了？’‘他们那个眼神是不是觉得我很蠢？’这种对外的极度敏感，让我觉得哪怕只是呼吸，都很耗费力气。" },
];

// 优化精简后的引导词
const DIARY_PROMPT_LINES = [
  "那些未被表达的情绪",
  "他们并未消失，只是在等待一个出口",
  "此刻，不需要完美的表达",
  "只需敲下你的故事，让情绪在这里安全落地"
];

// --- 提取为全局常量，避免组件重绘时重新生成导致动画重复 ---
const INTRO_SCENES = [
  [
    "欢迎来到情绪星海",
    "这是一个只属于你和情绪的隐秘角落",
    "这里的空气很安静，这里的耳朵不带审判"
  ],
  [
    "请放松你的额头，放松肩膀……",
    "把注意力的触角，从繁杂的外部世界收回来",
    "慢慢探向你的内心"
  ],
  [
    "在你的人际关系中，是否总有一些时刻",
    "像一根刺，拔不出来，也无法忽视",
    "是否有一些话，到了嘴边",
    "又被生生咽下，变成了胸口的一团闷气"
  ]
];

const CASES_INTRO_LINES = [
  "这里，散落着一些和你一样的碎片", 
  "或许，你能在其中看到自己的影子"
];

const MUSIC_TRACKS = [
  { id: 'm1', name: '专属音乐 (My Music)', url: 'https://files.catbox.moe/6knrwi.ogg' },
  { id: 'm2', name: '深海沉浮 (Deep Sea)', url: 'https://cdn.pixabay.com/download/audio/2021/08/04/audio_12b0c7443c.mp3?filename=underwater-ambience-6201.mp3' },
  { id: 'm3', name: '微风白噪 (Soft Wind)', url: 'https://cdn.pixabay.com/download/audio/2021/09/06/audio_034f71a067.mp3?filename=soft-rain-ambient-111154.mp3' }
];

const STORAGE_KEYS = {
  userStories: 'emotion-sea-user-stories',
  particleSettings: 'emotion-sea-particle-settings',
};

const DEFAULT_PARTICLE_SETTINGS = {
  size: 1.0,
  hue: 220,
  amplitude: 1.0,
  speed: 1.0,
};

const DEFAULT_GENERATED_TITLE = '未命名的心绪';

const loadStoredJson = (key, fallback) => {
  if (typeof window === 'undefined') return fallback;

  try {
    const raw = window.localStorage.getItem(key);
    return raw ? JSON.parse(raw) : fallback;
  } catch (error) {
    console.warn(`读取本地存储失败: ${key}`, error);
    return fallback;
  }
};

// --- 极简科技风滑块组件 ---
const CustomSlider = ({ icon: Icon, label, value, min, max, step, onChange }) => {
  const percentage = ((value - min) / (max - min)) * 100;
  return (
    <div className="mb-6">
      <div className="flex justify-between items-center text-[#78c8ff] text-[12px] font-serif-sc mb-3 tracking-widest">
        <div className="flex items-center gap-3 opacity-80">
          {Icon && <Icon size={14} className="text-[#a3e6cd]" />}
          <span>{label}</span>
        </div>
        <span className="text-white/90 font-mono">{value.toFixed(2)}</span>
      </div>
      <div className="relative h-[2px] bg-white/10 rounded-full flex items-center group">
        <input
          type="range" min={min} max={max} step={step} value={value}
          onChange={(e) => onChange(parseFloat(e.target.value))}
          className="absolute w-full h-full opacity-0 cursor-pointer z-10"
        />
        <div className="absolute h-full bg-gradient-to-r from-[#78c8ff]/50 to-[#a3e6cd]/80 rounded-full pointer-events-none" style={{ width: `${percentage}%` }}></div>
        <div className="absolute w-3 h-3 bg-[#a3e6cd] rounded-full shadow-[0_0_12px_#a3e6cd] pointer-events-none transition-transform group-hover:scale-125" style={{ left: `calc(${percentage}% - 6px)` }}></div>
      </div>
    </div>
  );
};

// --- 全局居中星云粉尘实体 ---
const DustEntity = ({ breathPhase, settings }) => {
  const canvasRef = useRef(null);
  const breathRef = useRef(breathPhase);
  const settingsRef = useRef(settings);

  useEffect(() => {
    breathRef.current = breathPhase;
  }, [breathPhase]);

  useEffect(() => {
    settingsRef.current = settings;
  }, [settings]);

  useEffect(() => {
    const canvas = canvasRef.current;
    if (!canvas) return;
    const ctx = canvas.getContext('2d');
    let animationId;
    let w, h, cx, cy;

    const numParticles = 5000;
    const particles = [];

    const resize = () => {
      w = canvas.width = window.innerWidth;
      h = canvas.height = window.innerHeight;
      cx = w / 2;
      cy = h / 2; 
    };
    resize();
    window.addEventListener('resize', resize);

    for (let i = 0; i < numParticles; i++) {
      const u = Math.random();
      const v = Math.random();
      const theta = 2 * Math.PI * u;
      const phi = Math.acos(2 * v - 1);
      
      const maxR = w < 768 ? 450 : 800;
      const r = Math.pow(Math.random(), 2) * maxR; 

      const x = r * Math.sin(phi) * Math.cos(theta);
      const y = r * Math.sin(phi) * Math.sin(theta);
      const z = r * Math.cos(phi);

      particles.push({
        origX: x, origY: y, origZ: z,
        size: Math.random() * 1.8 + 0.5,
        baseAlpha: Math.random() * 0.5 + 0.1,
        offset: Math.random() * Math.PI * 2
      });
    }

    let time = 0;
    let targetMouseX = -1000;
    let targetMouseY = -1000;
    let mouseX = -1000;
    let mouseY = -1000;

    let breathExpand = 1.0;
    let breathSpeed = 0.005;

    const onMouseMove = (e) => {
      targetMouseX = e.clientX;
      targetMouseY = e.clientY;
    };
    window.addEventListener('mousemove', onMouseMove);

    const animate = () => {
      ctx.clearRect(0, 0, w, h);
      const currentSettings = settingsRef.current;
      
      if (breathRef.current === 'inhale') {
        breathExpand += (1.4 - breathExpand) * 0.005; 
        breathSpeed += (0.018 - breathSpeed) * 0.01;  
      } else if (breathRef.current === 'exhale') {
        breathExpand += (0.75 - breathExpand) * 0.005; 
        breathSpeed += (0.002 - breathSpeed) * 0.01;   
      } else {
        breathExpand += (1.0 - breathExpand) * 0.01;   
        breathSpeed += (0.005 - breathSpeed) * 0.01;
      }
      
      time += breathSpeed * currentSettings.speed;

      mouseX += (targetMouseX - mouseX) * 0.15;
      mouseY += (targetMouseY - mouseY) * 0.15;

      const rotX = time * 0.3;
      const rotY = time * 0.5;
      
      const cosX = Math.cos(rotX), sinX = Math.sin(rotX);
      const cosY = Math.cos(rotY), sinY = Math.sin(rotY);

      if (mouseX > -500) {
         const mouseGlow = ctx.createRadialGradient(mouseX, mouseY, 0, mouseX, mouseY, 180);
         mouseGlow.addColorStop(0, `hsla(${currentSettings.hue}, 80%, 70%, 0.12)`);
         mouseGlow.addColorStop(1, 'hsla(0, 0%, 0%, 0)');
         ctx.fillStyle = mouseGlow;
         ctx.fillRect(mouseX - 180, mouseY - 180, 360, 360);
      }

      const gradientRadius = w < 768 ? 500 : 800;
      const gradient = ctx.createRadialGradient(cx, cy, 0, cx, cy, gradientRadius);
      gradient.addColorStop(0, `hsla(${currentSettings.hue}, 70%, 50%, ${0.06 * breathExpand})`); 
      gradient.addColorStop(1, 'hsla(0, 0%, 0%, 0)');
      ctx.fillStyle = gradient;
      ctx.fillRect(cx - gradientRadius, cy - gradientRadius, gradientRadius * 2, gradientRadius * 2);

      ctx.globalCompositeOperation = 'screen';

      for (let i = 0; i < particles.length; i++) {
        const p = particles[i];

        const noise = Math.sin(time * 3 + p.offset) * 15 * currentSettings.amplitude;
        let px = p.origX * (1 + noise/200) * breathExpand;
        let py = p.origY * (1 + noise/200) * breathExpand;
        let pz = p.origZ * (1 + noise/200) * breathExpand;

        let rx1 = px * cosY - pz * sinY;
        let rz1 = px * sinY + pz * cosY;
        let ry1 = py;

        let rx2 = rx1;
        let ry2 = ry1 * cosX - rz1 * sinX;
        let rz2 = ry1 * sinX + rz1 * cosX;

        const fov = 400;
        const zOff = 300;
        
        const zDepth = fov + rz2 + zOff;
        
        if (zDepth < 30) continue; 
        
        const scale = Math.min(fov / zDepth, 4.0); 
        
        let screenX = cx + rx2 * scale;
        let screenY = cy + ry2 * scale;

        const dxMouse = screenX - mouseX;
        const dyMouse = screenY - mouseY;
        const dist = Math.sqrt(dxMouse * dxMouse + dyMouse * dyMouse);
        const interactionRadius = 150; 
        let interactionAlphaBoost = 0;

        if (dist < interactionRadius && mouseX > -500) {
           const force = Math.pow((interactionRadius - dist) / interactionRadius, 2);
           screenX += (dxMouse / dist) * force * 55;
           screenY += (dyMouse / dist) * force * 55;
           interactionAlphaBoost = force * 0.6;
        }

        if (scale > 0 && screenX > 0 && screenX < w && screenY > 0 && screenY < h) {
          const nearFade = zDepth < 150 ? (zDepth - 30) / 120 : 1;
          const alpha = Math.min(1, (p.baseAlpha * scale * (rz2 > 0 ? 0.8 : 0.3)) + interactionAlphaBoost) * nearFade;
          
          let fillColor = "";
          if (interactionAlphaBoost > 0) {
             fillColor = `hsla(${currentSettings.hue}, 100%, 90%, ${alpha})`;
          } else {
             const lightness = Math.floor(60 + (rz2/200) * 25);
             fillColor = `hsla(${currentSettings.hue}, 80%, ${lightness}%, ${alpha})`;
          }
          
          ctx.fillStyle = fillColor;
          ctx.strokeStyle = fillColor;

          ctx.beginPath();
          ctx.arc(screenX, screenY, p.size * scale * currentSettings.size, 0, Math.PI * 2);
          ctx.fill();
        }
      }
      ctx.globalCompositeOperation = 'source-over';

      animationId = requestAnimationFrame(animate);
    };

    animate();

    return () => {
      window.removeEventListener('resize', resize);
      window.removeEventListener('mousemove', onMouseMove);
      cancelAnimationFrame(animationId);
    };
  }, []);

  return <canvas ref={canvasRef} className="absolute inset-0 z-0 pointer-events-none" />;
};


// --- 打字机文本组件 ---
const TypewriterText = ({ textLines, onComplete, slowMode = true }) => {
  const [currentLine, setCurrentLine] = useState(0);
  const [currentChar, setCurrentChar] = useState(0);
  const hasCompleted = useRef(false);
  const onCompleteRef = useRef(onComplete);

  // 缓存最新的 onComplete 函数，避免作为 useEffect 依赖导致重复触发
  useEffect(() => {
    onCompleteRef.current = onComplete;
  }, [onComplete]);

  // 将数组转为字符串作为稳定依赖，防止父组件重绘带来新的数组引用
  const textLinesStr = textLines.join('|');

  useEffect(() => {
    if (currentLine >= textLines.length) {
      if (!hasCompleted.current) {
        hasCompleted.current = true;
        onCompleteRef.current && onCompleteRef.current();
      }
      return;
    }

    const line = textLines[currentLine];
    if (currentChar < line.length) {
      const timeout = setTimeout(() => {
        setCurrentChar(prev => prev + 1);
      }, slowMode ? 90 : 45); 
      return () => clearTimeout(timeout);
    } else {
      const timeout = setTimeout(() => {
        setCurrentLine(prev => prev + 1);
        setCurrentChar(0);
      }, slowMode ? 1500 : 700); 
      return () => clearTimeout(timeout);
    }
  }, [currentLine, currentChar, textLinesStr, slowMode, textLines.length]); // 依赖替换为稳定的属性

  return (
    <div className="space-y-8 md:space-y-12 max-w-3xl mx-auto text-center font-serif-sc font-light tracking-[0.2em] text-lg md:text-xl leading-[2.5] text-white/90 px-6">
      {textLines.map((line, index) => {
        const isVisible = index <= currentLine;
        
        return (
          <div key={index} className="min-h-[2.5em] transition-opacity duration-1000" style={{ opacity: isVisible ? 1 : 0 }}>
            {index < currentLine ? line : index === currentLine ? line.substring(0, currentChar) : ""}
          </div>
        );
      })}
    </div>
  );
};

// --- 逐句浮现文本组件 ---
const FadeInSentences = ({ textLines, onComplete, delayBetween = 2500 }) => {
  const [visibleCount, setVisibleCount] = useState(0);
  const onCompleteRef = useRef(onComplete);

  // 缓存最新的 onComplete 函数
  useEffect(() => {
    onCompleteRef.current = onComplete;
  }, [onComplete]);

  // 稳定依赖
  const textLinesStr = textLines.join('|');

  useEffect(() => {
    let timers = [];
    setVisibleCount(0); // 确保文字切换时从0开始
    
    textLines.forEach((_, index) => {
      const timer = setTimeout(() => {
        setVisibleCount(index + 1);
        if (index === textLines.length - 1 && onCompleteRef.current) {
           // 最后一句话浮现后，多等一会儿再显示“下一步”按钮或进行跳转
           setTimeout(() => {
             if (onCompleteRef.current) onCompleteRef.current();
           }, 1500); 
        }
      }, index * delayBetween + 1000); // 增加了1秒的初始缓冲时间
      timers.push(timer);
    });

    return () => timers.forEach(clearTimeout);
  }, [textLinesStr, delayBetween, textLines.length]); // 核心修复：仅当文本内容实际改变时才重新执行

  return (
    <div className="space-y-8 md:space-y-12 max-w-3xl mx-auto text-center font-serif-sc font-light tracking-[0.2em] text-lg md:text-xl leading-[2.5] text-white/90 px-6">
      {textLines.map((line, index) => (
        <div
          key={index}
          // 动画过渡时间从 1500ms 延长至 2500ms
          className={`transition-all duration-[2500ms] ease-out min-h-[2.5em] ${
            index < visibleCount ? 'opacity-100 translate-y-0' : 'opacity-0 translate-y-4'
          }`}
        >
          {line}
        </div>
      ))}
    </div>
  );
};

// --- 主要应用组件 ---
export default function App() {
  // 初始化 Tailwind
  useEffect(() => {
    if (typeof window !== 'undefined' && typeof window.tailwind === 'undefined') {
      window.tailwind = { config: {} }; 
      const script = document.createElement('script');
      script.src = 'https://cdn.tailwindcss.com';
      script.async = true;
      document.head.appendChild(script);
    }
  }, []);

  const [stage, setStage] = useState(STAGES.GATE); 
  const [fadeState, setFadeState] = useState('in');
  
  const [gatePhase, setGatePhase] = useState(0);
  const [casesPhase, setCasesPhase] = useState(0);
  const [hasSeenCasesIntro, setHasSeenCasesIntro] = useState(false);

  // --- 高级面板与弹窗状态 ---
  const [particleSettings, setParticleSettings] = useState(() => {
    const stored = loadStoredJson(STORAGE_KEYS.particleSettings, DEFAULT_PARTICLE_SETTINGS);
    return stored && typeof stored === 'object'
      ? { ...DEFAULT_PARTICLE_SETTINGS, ...stored }
      : DEFAULT_PARTICLE_SETTINGS;
  });
  const [isSettingsOpen, setIsSettingsOpen] = useState(false);
  const [isMusicPanelOpen, setIsMusicPanelOpen] = useState(false);
  const [expandedCase, setExpandedCase] = useState(null); 

  // --- 音频播放系统 ---
  const audioRef = useRef(null);
  const [currentMusicId, setCurrentMusicId] = useState('m1'); // 默认选中第一首“专属音乐”
  const [isPlaying, setIsPlaying] = useState(false);

  useEffect(() => {
    if (audioRef.current) {
      if (isPlaying) {
        audioRef.current.play().catch(e => console.log("Audio play prevented:", e));
      } else {
        audioRef.current.pause();
      }
    }
  }, [isPlaying, currentMusicId]);

  const handleToggleMusic = (id) => {
    if (currentMusicId === id) {
      setIsPlaying(!isPlaying);
    } else {
      setCurrentMusicId(id);
      setIsPlaying(true);
    }
  };


  useEffect(() => {
    if (stage === STAGES.GATE) {
      const t1 = setTimeout(() => setGatePhase(1), 500); 
      const t2 = setTimeout(() => setGatePhase(2), 3500); 
      const t3 = setTimeout(() => setGatePhase(3), 7500); 
      const t4 = setTimeout(() => setGatePhase(4), 11500); 
      return () => { clearTimeout(t1); clearTimeout(t2); clearTimeout(t3); clearTimeout(t4); }
    }
  }, [stage]);

  const [casesList, setCasesList] = useState(() => {
    const storedStories = loadStoredJson(STORAGE_KEYS.userStories, []);
    const userStories = Array.isArray(storedStories) ? storedStories.filter(item => item?.isUser) : [];
    return [...userStories, ...INITIAL_CASES];
  });
  const [activeCaseIndex, setActiveCaseIndex] = useState(0); 
  
  const [emotionText, setEmotionText] = useState("");
  const [isGenerating, setIsGenerating] = useState(false); 
  const [paperStatus, setPaperStatus] = useState('idle'); 

  const [introStep, setIntroStep] = useState(0); 
  const [introFinished, setIntroFinished] = useState(false);
  const [diaryPromptFinished, setDiaryPromptFinished] = useState(false);

  const [breathPhase, setBreathPhase] = useState('idle'); 
  
  const cursorRef = useRef(null);

  useEffect(() => {
    const cursor = cursorRef.current;
    if (!cursor) return;

    let isFirstMove = true;

    const onMouseMove = (e) => {
      if (isFirstMove) {
        cursor.style.opacity = 1;
        isFirstMove = false;
      }
      cursor.style.transform = `translate3d(${e.clientX}px, ${e.clientY}px, 0)`;
    };
    
    const onMouseDown = () => cursor.classList.add('cursor-clicked');
    const onMouseUp = () => cursor.classList.remove('cursor-clicked');

    window.addEventListener('mousemove', onMouseMove);
    window.addEventListener('mousedown', onMouseDown);
    window.addEventListener('mouseup', onMouseUp);

    return () => {
      window.removeEventListener('mousemove', onMouseMove);
      window.removeEventListener('mousedown', onMouseDown);
      window.removeEventListener('mouseup', onMouseUp);
    };
  }, []);

  // 已将 INTRO_SCENES 移至组件外部全局定义

  useEffect(() => {
    if (stage === STAGES.CREATE) {
      setPaperStatus('entering');
      const timer = setTimeout(() => {
        setPaperStatus('idle');
      }, 100);
      return () => clearTimeout(timer);
    }
  }, [stage]);

  useEffect(() => {
    if (typeof window === 'undefined') return;

    const userStories = casesList.filter(item => item.isUser);
    window.localStorage.setItem(STORAGE_KEYS.userStories, JSON.stringify(userStories));
  }, [casesList]);

  useEffect(() => {
    if (typeof window === 'undefined') return;

    window.localStorage.setItem(STORAGE_KEYS.particleSettings, JSON.stringify(particleSettings));
  }, [particleSettings]);

  const changeStage = (newStage) => {
    if (stage === newStage) return; 
    setFadeState('out');
    setTimeout(() => {
      setStage(newStage);
      if (newStage === STAGES.CASES) {
          // 如果用户已经看过了引导，直接跳到展示阶段（Phase 4）
          setCasesPhase(hasSeenCasesIntro ? 4 : 0); 
      }
      setFadeState('in');
    }, 1000); 
  };

  const handleBreatheClick = () => {
    if (breathPhase !== 'idle' || !introFinished) return;
    
    setBreathPhase('inhale');
    
    setTimeout(() => {
        setBreathPhase('exhale');
        
        setTimeout(() => {
            // 提前更新步骤以防止文字淡入时显示上一次的引导语
            setIntroStep(prev => prev + 1);
            setIntroFinished(false); 
            setBreathPhase('idle');
        }, 4000);
    }, 4000);
  };

  const handleNextIntroStep = () => {
    setIntroFinished(false);
    setTimeout(() => {
        setIntroStep(prev => prev + 1);
    }, 500); 
  };

  const handleEnterCases = () => {
    setFadeState('out');
    setTimeout(() => {
        setIntroFinished(false);
        changeStage(STAGES.CASES); 
    }, 1000);
  };

  const handleCasesIntroComplete = () => {
    setTimeout(() => {
      setCasesPhase(1); // 引导语淡出
      setTimeout(() => {
        setCasesPhase(2); // “情绪故事汇”标题在中间浮现（字体放大）
        setTimeout(() => {
          setCasesPhase(3); // “情绪故事汇”标题原地淡出（不位移，稍微放大变模糊）
          setTimeout(() => {
            setCasesPhase(4); // 故事卡片轮播图出现
            setHasSeenCasesIntro(true); 
          }, 1500);
        }, 2500); // 标题悬停展示2.5秒
      }, 1000);
    }, 2000); 
  };

  const handlePrevCase = () => {
    setActiveCaseIndex(prev => (prev - 1 + casesList.length) % casesList.length);
  };

  const handleNextCase = () => {
    setActiveCaseIndex(prev => (prev + 1) % casesList.length);
  };

  const handleStartExperience = () => {
    setIsPlaying(true); 
    // 关键修复：直接在用户的点击事件中同步触发播放，防止被浏览器拦截
    if (audioRef.current) {
        audioRef.current.play().catch(e => console.log("Audio play prevented:", e));
    }
    changeStage(STAGES.INTRO);
  };

  const handleSaveStory = async (actionType) => {
    if (!emotionText.trim() || isGenerating) return;
    
    setIsGenerating(true);
    setPaperStatus(actionType); 
    
    const aiPromise = (async () => {
        const dynamicTitle = DEFAULT_GENERATED_TITLE;
        const apiKey = import.meta.env.VITE_GEMINI_API_KEY?.trim();

        if (!apiKey) {
          return dynamicTitle;
        }

        const url = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-09-2025:generateContent?key=${apiKey}`;
        const prompt = `请根据以下情绪日记，生成一个简短且富有诗意的标题，严格遵循“XX中的XX”的格式（例如“友情中的异位”、“亲情里的高压”、“独处时的空洞”）。不要包含任何标点符号、书名号、括号或多余解释，只返回这几个字。\n\n日记内容：${emotionText}`;

        const payload = {
          contents: [{ parts: [{ text: prompt }] }]
        };

        const delays = [1000, 2000, 4000, 8000, 16000];
        for (let i = 0; i < 5; i++) {
            try {
                const response = await fetch(url, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                });
                if (response.ok) {
                    const result = await response.json();
                    const aiText = result.candidates?.[0]?.content?.parts?.[0]?.text?.trim();
                    if (aiText) {
                        return aiText.replace(/[【】\[\]"'\n\r。，,.]/g, '');
                    }
                }
                if (i < delays.length - 1) {
                    await new Promise(resolve => setTimeout(resolve, delays[i]));
                }
            } catch (error) {
                if (i === 4) console.error("AI 标题生成失败", error);
                if (i < delays.length - 1) {
                    await new Promise(resolve => setTimeout(resolve, delays[i]));
                }
            }
        }
        return dynamicTitle;
    })();

    const timerPromise = new Promise(resolve => setTimeout(resolve, 2000));
    const [dynamicTitle] = await Promise.all([aiPromise, timerPromise]);

    const newStory = {
      id: 'usr_' + Date.now(),
      title: dynamicTitle,
      text: emotionText,
      isUser: true
    };
    
    setCasesList(prev => [newStory, ...prev]);
    setActiveCaseIndex(0); 
    setEmotionText("");
    setIsGenerating(false); 
    
    // 提交后进入新的疗愈结语页面
    changeStage(STAGES.OUTRO); 
  };

  const renderUI = () => {
    const fadeClass = `transition-opacity duration-1000 ${fadeState === 'in' ? 'opacity-100' : 'opacity-0'}`;

    const TopNav = () => (
      <div className="absolute top-0 left-0 w-full p-6 md:p-8 flex justify-center z-50 pointer-events-none">
         <div className="flex gap-6 md:gap-8 text-[12px] md:text-sm tracking-[0.2em] font-sans font-light text-white/40 pointer-events-auto uppercase">
            <span onClick={() => changeStage(STAGES.CASES)} className={`cursor-pointer transition-colors pb-1 border-b ${stage === STAGES.CASES ? 'text-white border-white/30' : 'border-transparent hover:text-white/80 hover:border-white/30'}`}>DIARY</span>
            <span onClick={() => changeStage(STAGES.MEMORY)} className={`cursor-pointer transition-colors pb-1 border-b ${stage === STAGES.MEMORY ? 'text-white border-white/30' : 'border-transparent hover:text-white/80 hover:border-white/30'}`}>MEMORY</span>
            <span onClick={() => setIsMusicPanelOpen(true)} className="cursor-pointer transition-colors pb-1 border-b border-transparent hover:text-white/80 hover:border-white/30">MUSIC</span>
            <span onClick={() => setIsSettingsOpen(true)} className="cursor-pointer transition-colors pb-1 border-b border-transparent hover:text-white/80 hover:border-white/30">SETTINGS</span>
         </div>
      </div>
    );

    switch (stage) {
      case STAGES.GATE:
        return (
          <div className={`absolute inset-0 z-50 flex flex-col items-center justify-center text-white bg-transparent transition-opacity duration-[2000ms] ${fadeState === 'in' ? 'opacity-100' : 'opacity-0 pointer-events-none overflow-hidden'}`}>
            <div 
              className="relative z-10 flex flex-col items-center max-w-md text-center px-6 transition-all duration-[4000ms] ease-out"
              style={{
                 opacity: gatePhase >= 3 ? 1 : 0,
                 transform: gatePhase >= 3 ? 'translateY(0)' : 'translateY(30px)',
                 filter: gatePhase >= 3 ? 'blur(0px)' : 'blur(20px)'
              }}
            >
               <h1 
                 className="text-4xl md:text-6xl font-normal tracking-[0.3em] mb-4 drop-shadow-2xl opacity-95 font-serif-sc"
                 style={{ textShadow: '0 0 50px rgba(255,255,255,0.6)' }}
               >
                 情绪星海
               </h1>
               <p className="text-white/50 text-[10px] md:text-sm tracking-[0.6em] uppercase mb-16 font-light">
                 Sea of Emotions
               </p>
               
               <div className={`transition-opacity duration-[2500ms] ${gatePhase >= 4 ? 'opacity-100' : 'opacity-0'}`}>
                 <p className="text-white/40 text-xs md:text-sm tracking-widest leading-[2.5] mb-12">
                   这只是您的隐秘角落，<br/>一切数据仅在本地流转，不会被上传。
                 </p>
                 <button 
                   onClick={handleStartExperience} 
                   className="px-10 py-4 border border-white/20 rounded-full hover:bg-white/10 hover:border-white/50 transition-all duration-500 tracking-[0.2em] font-light text-base shadow-[0_0_20px_rgba(255,255,255,0.05)] hover:shadow-[0_0_30px_rgba(255,255,255,0.2)] pointer-events-auto"
                 >
                   进入旅程
                 </button>
               </div>
            </div>
          </div>
        );

      case STAGES.INTRO:
        const isLastStep = introStep === INTRO_SCENES.length - 1;

        return (
          <div className={`flex flex-col items-center justify-center h-full text-white pt-20 pb-10 bg-transparent ${fadeClass}`}>
            {/* --- 新的高级版呼吸律动 UI --- */}
            <div className={`absolute inset-0 flex flex-col items-center justify-center z-30 pointer-events-none transition-all ${breathPhase !== 'idle' ? 'duration-1000 opacity-100 delay-300' : 'duration-500 opacity-0'}`}>
                <div 
                  className="absolute rounded-full border-[1px] border-white/30"
                  style={{
                    width: '300px', height: '300px',
                    transform: breathPhase === 'inhale' ? 'scale(1.8)' : breathPhase === 'exhale' ? 'scale(0.8)' : 'scale(0.5)',
                    opacity: breathPhase === 'inhale' ? 0.3 : breathPhase === 'exhale' ? 0.1 : 0,
                    transition: 'all 4000ms cubic-bezier(0.4, 0, 0.2, 1)'
                  }}
                />
                <div 
                  className="absolute rounded-full bg-cyan-100/10 blur-[40px]"
                  style={{
                    width: '200px', height: '200px',
                    transform: breathPhase === 'inhale' ? 'scale(1.5)' : breathPhase === 'exhale' ? 'scale(0.6)' : 'scale(0.2)',
                    opacity: breathPhase === 'inhale' ? 0.6 : 0,
                    transition: 'all 4000ms cubic-bezier(0.4, 0, 0.2, 1)'
                  }}
                />
                <span 
                   className="text-2xl md:text-3xl font-serif-sc font-light tracking-[0.5em] text-white/90 z-10"
                   style={{
                      transform: breathPhase === 'inhale' ? 'scale(1.05)' : breathPhase === 'exhale' ? 'scale(0.95)' : 'scale(0.9)',
                      opacity: breathPhase !== 'idle' ? 1 : 0,
                      transition: 'all 4000ms ease-in-out',
                      textShadow: '0 0 20px rgba(255,255,255,0.2)'
                   }}
                >
                   {breathPhase === 'inhale' ? '深深吸气' : breathPhase === 'exhale' ? '缓缓呼气' : ''}
                </span>
            </div>

            <div 
              className={`flex-1 flex flex-col items-center justify-center w-full relative z-10 transition-all ${breathPhase !== 'idle' ? 'duration-500 opacity-0 scale-95 pointer-events-none' : 'duration-1000 opacity-100 scale-100'}`}
            >
              {/* 根据索引切换展示效果 */}
              {introStep === 0 ? (
                <TypewriterText 
                  key={`intro-${introStep}`} 
                  textLines={INTRO_SCENES[introStep]} 
                  onComplete={() => setIntroFinished(true)} 
                />
              ) : (
                <FadeInSentences 
                  key={`intro-${introStep}`} 
                  textLines={INTRO_SCENES[introStep]} 
                  onComplete={() => setIntroFinished(true)} 
                />
              )}
            </div>

            <div className={`absolute bottom-20 transition-all z-20 ${(introFinished && breathPhase === 'idle') ? 'duration-1000 opacity-100 translate-y-0' : 'duration-300 opacity-0 translate-y-4 pointer-events-none'}`}>
              <button 
                onClick={isLastStep ? handleEnterCases : (introStep === 0 ? handleBreatheClick : handleNextIntroStep)}
                className="relative px-10 py-4 border border-white/20 rounded-full hover:bg-white/10 hover:border-white/50 transition-all duration-500 tracking-[0.2em] font-light text-base shadow-[0_0_20px_rgba(255,255,255,0.05)] hover:shadow-[0_0_30px_rgba(255,255,255,0.2)] bg-transparent pointer-events-auto"
              >
                <span className="relative z-10 text-white/90">
                  {isLastStep ? "进入情绪日记空间" : (introStep === 0 ? "点击深呼吸" : "继续")}
                </span>
              </button>
            </div>
          </div>
        );

      case STAGES.CASES:
        return (
          <div className={`flex flex-col h-full text-white w-full mx-auto bg-transparent ${fadeClass} overflow-hidden relative`}>
             <TopNav />
             
             {/* 文本过渡层动画 */}
             <div className="absolute inset-0 flex flex-col items-center justify-center z-20 pointer-events-none">
                {/* 第一步：引导语展示并消失 (位于中下方) */}
                <div className={`absolute bottom-[20vh] transition-all duration-1000 w-full flex justify-center 
                  ${casesPhase === 0 ? 'opacity-100 translate-y-0' : 
                    casesPhase === 1 ? 'opacity-0 -translate-y-8' : 'hidden'}`}
                >
                  {casesPhase <= 1 && !hasSeenCasesIntro && (
                    <FadeInSentences 
                      key={`cases_intro`} 
                      textLines={CASES_INTRO_LINES} 
                      onComplete={handleCasesIntroComplete} 
                      delayBetween={2500}
                    />
                  )}
                </div>
                
                {/* 第二步：情绪故事汇 放大直接在中间出现，并在第三步原地消散 */}
                <div className={`absolute transition-all duration-[2000ms] ease-[cubic-bezier(0.4,0,0.2,1)] flex items-center justify-center w-full h-full
                  ${casesPhase === 2 ? 'opacity-100 scale-100' : 
                    casesPhase >= 3 ? 'opacity-0 scale-110 blur-[8px] pointer-events-none' : 
                    'opacity-0 scale-95 hidden'}`}
                >
                   <h2 className="text-4xl md:text-5xl lg:text-6xl font-serif-sc tracking-[0.5em] font-light text-white/90 drop-shadow-[0_0_40px_rgba(255,255,255,0.6)] text-center">
                      情绪故事汇
                   </h2>
                </div>
             </div>
             
             {/* 故事轮播卡片层 (在阶段4出现) */}
             <div className={`absolute inset-0 flex flex-col items-center justify-end pb-12 transition-all duration-1000 delay-500 z-30 pointer-events-none
                ${casesPhase >= 4 ? 'opacity-100 translate-y-0 pointer-events-auto' : 'opacity-0 translate-y-12'}`}
             >
                <div className="relative w-full max-w-4xl flex items-center justify-center pointer-events-auto mb-8">
                  <button 
                    onClick={handlePrevCase}
                    className="absolute left-4 md:left-12 z-30 p-4 transition-all duration-300 opacity-40 hover:opacity-100 hover:scale-110 pointer-events-auto"
                  >
                    <ChevronLeft size={40} className="drop-shadow-lg" />
                  </button>

                  <div className="relative w-[85vw] md:w-[500px] h-[300px] flex items-center justify-center perspective-1000 mt-[15vh]">
                    {casesList.map((item, idx) => {
                      const diff = (idx - activeCaseIndex + casesList.length) % casesList.length;
                      let transformStyle = '';
                      if (diff === 0) {
                        transformStyle = 'translate-x-0 opacity-100 scale-100 z-20 pointer-events-auto';
                      } else if (diff <= casesList.length / 2) {
                        transformStyle = 'translate-x-16 opacity-0 scale-90 z-0 pointer-events-none';
                      } else {
                        transformStyle = '-translate-x-16 opacity-0 scale-90 z-0 pointer-events-none';
                      }

                      return (
                        <div 
                          key={item.id} 
                          className={`absolute inset-0 p-8 rounded-2xl flex flex-col gap-4 border transition-all duration-700 ease-in-out ${transformStyle} ${item.isUser ? 'bg-white/[0.08] border-white/30 shadow-[0_0_50px_rgba(255,255,255,0.08)] backdrop-blur-2xl' : 'bg-black/40 border-white/10 backdrop-blur-xl shadow-2xl'}`}
                        >
                          <button
                            onClick={() => setExpandedCase(item)}
                            className="absolute top-5 right-5 text-white/30 hover:text-white/90 hover:scale-110 transition-all duration-300 pointer-events-auto z-50"
                          >
                            <Maximize size={18} />
                          </button>

                          <div className="flex justify-between items-start border-b border-white/10 pb-3 pr-6 shrink-0">
                            <div className="flex items-center gap-3">
                              <div className="w-1.5 h-1.5 rounded-full bg-cyan-400/70 shadow-[0_0_8px_rgba(34,211,238,0.8)]"/>
                              <h3 className={`font-serif-sc tracking-[0.2em] font-normal text-sm md:text-base ${item.isUser ? 'text-white' : 'text-white/80'}`}>
                                {item.title}
                              </h3>
                            </div>
                            {item.isUser && <span className="text-xs text-orange-200/80 border border-orange-200/30 bg-orange-500/10 px-3 py-1 rounded-full font-light tracking-widest">你的星光</span>}
                          </div>
                          
                          <div className="flex-1 overflow-y-auto custom-scrollbar pr-2 text-justify relative mt-1">
                            <span className="absolute -top-4 -left-2 text-5xl text-white/5 font-serif font-bold select-none pointer-events-none">"</span>
                            <p className="font-serif-sc font-light text-white/70 leading-[2.2] tracking-[0.1em] text-[14px] z-10 relative pt-1 whitespace-pre-wrap">
                              {item.text}
                            </p>
                          </div>
                        </div>
                      );
                    })}
                  </div>

                  <button 
                    onClick={handleNextCase}
                    className="absolute right-4 md:right-12 z-30 p-4 transition-all duration-300 opacity-40 hover:opacity-100 hover:scale-110 pointer-events-auto"
                  >
                    <ChevronRight size={40} className="drop-shadow-lg" />
                  </button>
                </div>

                <div className="flex gap-3 mb-6 pointer-events-auto">
                  {casesList.map((_, idx) => (
                    <div 
                      key={idx} 
                      className={`h-1.5 rounded-full transition-all duration-500 ${idx === activeCaseIndex ? 'w-4 bg-white/90 shadow-[0_0_10px_rgba(255,255,255,0.5)]' : 'w-1.5 bg-white/20'}`} 
                    />
                  ))}
                </div>

                <button 
                  onClick={() => changeStage(STAGES.DIARY_PROMPT)}
                  className="group flex items-center gap-3 px-8 py-3 text-white/50 hover:text-white transition-colors duration-500 pointer-events-auto"
                >
                  <span className="tracking-[0.2em] font-light text-sm border-b border-transparent group-hover:border-white/60 pb-1">
                    我也想说...
                  </span>
                </button>
             </div>

             {/* 放大的故事详情模态框 */}
             {expandedCase && (
                <div className="fixed inset-0 z-[200] flex items-center justify-center p-6 bg-[#030305]/80 backdrop-blur-md transition-opacity duration-500 pointer-events-auto opacity-100">
                  <div className="relative w-full max-w-2xl bg-white/[0.05] border border-white/20 rounded-2xl p-8 md:p-12 shadow-[0_0_50px_rgba(0,0,0,0.6)] backdrop-blur-2xl animate-[fadeIn_0.5s_ease-out_forwards]">
                    <button
                      onClick={() => setExpandedCase(null)}
                      className="absolute top-6 right-6 text-white/40 hover:text-white transition-colors"
                    >
                      <X size={24} />
                    </button>
                    <div className="flex items-center gap-3 mb-8 border-b border-white/10 pb-4">
                      <div className="w-2 h-2 rounded-full bg-cyan-400/70 shadow-[0_0_12px_rgba(34,211,238,0.8)]"/>
                      <h3 className="font-serif-sc tracking-[0.2em] font-normal text-xl md:text-2xl text-white/90">
                        {expandedCase.title}
                      </h3>
                    </div>
                    <div className="max-h-[60vh] overflow-y-auto custom-scrollbar pr-4">
                      <p className="font-serif-sc font-light text-white/80 leading-[2.5] tracking-[0.1em] text-[15px] md:text-lg text-justify whitespace-pre-wrap">
                        {expandedCase.text}
                      </p>
                    </div>
                  </div>
                </div>
             )}
          </div>
        );

      case STAGES.MEMORY:
        const userStories = casesList.filter(c => c.isUser);
        return (
          <div className={`flex flex-col h-full text-white w-full mx-auto bg-transparent ${fadeClass} overflow-hidden relative`}>
             <TopNav />
             
             <div className="relative z-10 flex flex-col items-center pt-32 h-full w-full max-w-4xl mx-auto px-6">
                <h2 className="text-2xl md:text-3xl font-serif-sc tracking-[0.4em] font-light text-white/90 mb-12 drop-shadow-[0_0_20px_rgba(255,255,255,0.3)]">
                   记忆回廊
                </h2>
                
                <div className="flex-1 w-full overflow-y-auto custom-scrollbar pb-20 space-y-6">
                   {userStories.length === 0 ? (
                      <div className="text-center text-white/30 mt-20 font-light tracking-widest text-sm">
                          你的记忆瓶还是空的...
                      </div>
                   ) : (
                      userStories.map((item, idx) => (
                         <div key={item.id} className="bg-white/[0.03] border border-white/10 backdrop-blur-xl p-8 rounded-2xl shadow-2xl hover:bg-white/[0.05] transition-colors duration-500">
                            <div className="flex justify-between items-center mb-4 border-b border-white/10 pb-4">
                                <h3 className="font-serif-sc tracking-widest text-white/90 text-lg">{item.title}</h3>
                                <span className="text-[10px] text-white/30 tracking-widest font-sans">NO. {String(idx + 1).padStart(3, '0')}</span>
                            </div>
                            <p className="font-serif-sc font-light text-white/60 leading-[2.4] tracking-[0.1em] text-[15px] text-justify whitespace-pre-wrap">
                               {item.text}
                            </p>
                         </div>
                      ))
                   )}
                </div>
             </div>
          </div>
        );

      case STAGES.DIARY_PROMPT:
        return (
          <div className={`flex flex-col items-center justify-center h-full text-white bg-transparent pt-20 pb-10 ${fadeClass}`}>
            <div className="flex-1 flex flex-col items-center justify-center w-full">
              <TypewriterText 
                key="diary_prompt"
                textLines={DIARY_PROMPT_LINES} 
                onComplete={() => setDiaryPromptFinished(true)} 
              />
              
              <div className={`mt-16 transition-all duration-1000 ${diaryPromptFinished ? 'opacity-100 translate-y-0' : 'opacity-0 translate-y-4 pointer-events-none'}`}>
                <button 
                  onClick={() => changeStage(STAGES.CREATE)}
                  className="group flex items-center gap-3 px-10 py-4 border border-white/20 rounded-full hover:bg-white/10 hover:border-white/50 transition-all duration-500 backdrop-blur-sm pointer-events-auto"
                >
                  <span className="tracking-[0.2em] font-light text-base">开始书写</span>
                  <ArrowRight size={18} className="group-hover:translate-x-2 transition-transform duration-500" />
                </button>
              </div>
            </div>
          </div>
        );

      case STAGES.CREATE:
        return (
          <div className={`flex flex-col items-center justify-center h-full w-full mx-auto bg-transparent p-6 ${fadeClass} overflow-hidden perspective-1000`}>
            
            <div className={`relative w-full max-w-lg bg-white/[0.03] backdrop-blur-2xl text-white/90 p-8 md:p-12 shadow-[0_0_50px_rgba(0,0,0,0.5)] border border-white/10 rounded-2xl transition-all duration-[2000ms] ease-in-out font-serif-sc pointer-events-auto
                ${paperStatus === 'entering' ? 'translate-y-[30px] opacity-0 blur-md' : ''}
                ${paperStatus === 'idle' ? 'translate-y-0 opacity-100 blur-0 scale-100' : ''}
                ${paperStatus === 'burning' ? 'animate-burn-effect pointer-events-none' : ''} 
                ${paperStatus === 'releasing' ? 'translate-y-[-80px] scale-110 opacity-0 blur-2xl brightness-[1.5] pointer-events-none' : ''}
            `}>
              
              <div className="absolute top-0 left-1/2 -translate-x-1/2 w-32 h-[1px] bg-gradient-to-r from-transparent via-white/30 to-transparent"></div>
              
              <h2 className="text-xl md:text-2xl font-serif-sc text-white/80 mb-6 text-center border-b border-white/10 pb-4 tracking-[0.3em]">
                 情绪纸条
              </h2>
              
              <textarea 
                  className="w-full h-48 md:h-64 bg-transparent border-none focus:outline-none resize-none text-white/90 font-serif-sc leading-[2.5] tracking-[0.1em] text-[15px] md:text-[16px] custom-scrollbar placeholder-white/20 disabled:opacity-50"
                  placeholder="写下那个瞬间..."
                  value={emotionText}
                  onChange={(e) => setEmotionText(e.target.value)}
                  disabled={paperStatus === 'burning' || paperStatus === 'releasing'}
              />
              
              <div className="flex gap-4 mt-8 relative z-10">
                  <button 
                      onClick={() => handleSaveStory('burning')}
                      disabled={!emotionText.trim() || isGenerating}
                      className="flex-1 py-3 flex justify-center items-center gap-2 border border-red-500/20 text-red-400/80 hover:bg-red-500/10 hover:border-red-500/50 hover:text-red-300 transition-colors rounded-xl font-serif-sc tracking-widest disabled:opacity-30 disabled:bg-transparent pointer-events-auto"
                  >
                      {isGenerating && paperStatus === 'burning' ? <span className="animate-pulse">化为灰烬...</span> : <><Flame size={16} /> 燃烧它</>}
                  </button>
                  <button 
                      onClick={() => handleSaveStory('releasing')}
                      disabled={!emotionText.trim() || isGenerating}
                      className="flex-1 py-3 flex justify-center items-center gap-2 border border-cyan-500/20 text-cyan-400/80 hover:bg-cyan-500/10 hover:border-cyan-500/50 hover:text-cyan-300 transition-colors rounded-xl font-serif-sc tracking-widest disabled:opacity-30 disabled:bg-transparent pointer-events-auto"
                  >
                      {isGenerating && paperStatus === 'releasing' ? <span className="animate-pulse">随风而去...</span> : <><Feather size={16} /> 释怀它</>}
                  </button>
              </div>

              {paperStatus === 'burning' && (
                  <div className="absolute inset-0 pointer-events-none z-50 overflow-hidden rounded-2xl">
                      {Array.from({ length: 30 }).map((_, i) => (
                          <div key={i} className="absolute bottom-0 w-1.5 h-1.5 rounded-full bg-orange-400 blur-[1px] shadow-[0_0_8px_rgba(251,146,60,0.8)]"
                               style={{
                                   left: `${Math.random() * 100}%`,
                                   animation: `embers ${1 + Math.random() * 2}s forwards ease-out`,
                                   animationDelay: `${Math.random() * 0.5}s`
                               }}
                          />
                      ))}
                  </div>
              )}

            </div>
          </div>
        );

      // 新增疗愈结语过渡页面
      case STAGES.OUTRO:
        return (
          <div className={`flex flex-col items-center justify-center h-full text-white bg-transparent pt-20 pb-10 ${fadeClass}`}>
            <div className="flex-1 flex flex-col items-center justify-center w-full">
              <FadeInSentences 
                key="outro_prompt"
                textLines={[
                  "感谢您赴约这场情绪的疗愈之旅",
                  "愿你所有的情绪最终都能被看见、被接纳、被深深地理解"
                ]} 
                delayBetween={2500}
                onComplete={() => {
                  setTimeout(() => {
                    changeStage(STAGES.CASES); // 停留8秒左右自动返回故事汇
                  }, 8000); 
                }} 
              />
            </div>
          </div>
        );

      default:
        return null;
    }
  };

  return (
    <div className="relative w-full h-screen bg-[#030305] overflow-hidden font-sans selection:bg-white/30 cursor-none">
      {/* 隐藏的全局音频标签 */}
      <audio 
         ref={audioRef} 
         src={currentMusicId ? MUSIC_TRACKS.find(t => t.id === currentMusicId)?.url : ''} 
         loop 
         preload="auto"
      />

      {/* 全局通用背景：星云粉尘与光晕 */}
      <DustEntity breathPhase={breathPhase} settings={particleSettings} />
      
      <div className="absolute inset-0 z-10 pointer-events-none">{renderUI()}</div>

      {/* --- 中央音乐选择面板 --- */}
      <div className={`fixed inset-0 z-[100] transition-all duration-500 flex items-center justify-center ${isMusicPanelOpen ? 'pointer-events-auto opacity-100' : 'pointer-events-none opacity-0'}`}>
         <div className="absolute inset-0 bg-black/60 backdrop-blur-md" onClick={() => setIsMusicPanelOpen(false)}></div>
         <div className={`relative bg-white/[0.03] border border-white/10 rounded-2xl p-8 max-w-sm w-full backdrop-blur-3xl shadow-[0_0_50px_rgba(0,0,0,0.8)] transition-transform duration-500 ${isMusicPanelOpen ? 'scale-100 translate-y-0' : 'scale-95 translate-y-8'}`}>
            <button onClick={() => setIsMusicPanelOpen(false)} className="absolute top-6 right-6 text-white/30 hover:text-white/80 transition-colors"><X size={20}/></button>
            <h3 className="text-[#78c8ff] text-sm font-serif-sc tracking-[0.3em] mb-8 border-b border-white/10 pb-4 text-center">星海之音</h3>
            
            <div className="space-y-4">
               {MUSIC_TRACKS.map(track => (
                  <div 
                    key={track.id} 
                    onClick={() => handleToggleMusic(track.id)}
                    className={`flex items-center justify-between p-4 rounded-xl cursor-pointer transition-all duration-300 border ${currentMusicId === track.id ? 'bg-white/10 border-white/30 shadow-[0_0_15px_rgba(255,255,255,0.1)]' : 'bg-transparent border-white/5 hover:bg-white/5'}`}
                  >
                     <span className={`font-serif-sc tracking-widest text-sm ${currentMusicId === track.id ? 'text-white' : 'text-white/60'}`}>{track.name}</span>
                     {currentMusicId === track.id && isPlaying ? <Volume2 size={16} className="text-[#a3e6cd] animate-pulse" /> : <VolumeX size={16} className="text-white/20" />}
                  </div>
               ))}
            </div>
            
            {currentMusicId && (
              <div className="mt-8 flex justify-center">
                 <button onClick={() => { setCurrentMusicId(null); setIsPlaying(false); }} className="text-xs text-white/40 tracking-[0.2em] font-serif-sc hover:text-white transition-colors border-b border-transparent hover:border-white/40 pb-1">停止播放</button>
              </div>
            )}
         </div>
      </div>

      {/* --- 高级科技风右侧边栏控制台 (无遮罩模式，可边看故事边调参数) --- */}
      <div 
        className={`fixed top-0 right-0 h-full w-[85vw] max-w-[380px] bg-[#0a0d14]/70 border-l border-white/10 shadow-[-20px_0_50px_rgba(0,0,0,0.5)] backdrop-blur-xl transform transition-transform duration-700 ease-[cubic-bezier(0.16,1,0.3,1)] flex flex-col z-[100] ${isSettingsOpen ? 'translate-x-0 pointer-events-auto' : 'translate-x-full pointer-events-none'}`}
      >
        <div className="flex-shrink-0 p-8 pt-12 relative">
            <button onClick={() => setIsSettingsOpen(false)} className="absolute top-8 right-8 text-white/30 hover:text-white/80 transition-colors"><X size={20}/></button>
            <div className="flex justify-between items-end mb-8 border-b border-white/10 pb-4 mt-4">
               <h3 className="text-[#78c8ff] text-sm font-serif-sc tracking-[0.2em]">星海环境参数</h3>
               <span className="text-white/30 font-mono text-[10px]">V2.1.0</span>
            </div>
        </div>
        
        <div className="flex-1 overflow-y-auto px-8 pb-12 custom-scrollbar space-y-8">
           <CustomSlider icon={Maximize} label="星辰大小" min={0.1} max={3} step={0.1} value={particleSettings.size} onChange={(val) => setParticleSettings({...particleSettings, size: val})} />
           <CustomSlider icon={Palette} label="星空色调" min={0} max={360} step={1} value={particleSettings.hue} onChange={(val) => setParticleSettings({...particleSettings, hue: val})} />
           <CustomSlider icon={Activity} label="波动幅度" min={0} max={5} step={0.1} value={particleSettings.amplitude} onChange={(val) => setParticleSettings({...particleSettings, amplitude: val})} />
           <CustomSlider icon={Wind} label="流转速度" min={0.1} max={5} step={0.1} value={particleSettings.speed} onChange={(val) => setParticleSettings({...particleSettings, speed: val})} />
        </div>
      </div>
      
      <div 
        ref={cursorRef} 
        className="fixed top-0 left-0 pointer-events-none z-[99999] opacity-0 transition-opacity duration-300 mix-blend-difference"
        style={{ willChange: 'transform' }}
      >
        <div className="cursor-inner w-8 h-8 -ml-4 -mt-4 rounded-full border border-white/50 shadow-[0_0_15px_rgba(255,255,255,0.3)] flex items-center justify-center transition-all duration-200 ease-out">
          <div className="cursor-dot w-1 h-1 bg-white rounded-full opacity-40 transition-all duration-200" />
        </div>
      </div>
      
      <style>{`
        @import url('https://fonts.googleapis.com/css2?family=Noto+Serif+SC:wght@300;400&display=swap');
        
        * { cursor: none !important; }
        
        .cursor-clicked .cursor-inner {
          transform: scale(0.6);
          background-color: rgba(255, 255, 255, 0.15);
          box-shadow: 0 0 25px rgba(255, 255, 255, 0.6);
          border-color: rgba(255, 255, 255, 0.9);
        }
        .cursor-clicked .cursor-dot {
          opacity: 1;
          transform: scale(1.5);
        }

        .font-serif-sc {
          font-family: 'Noto Serif SC', 'Songti SC', 'STSong', serif;
        }

        .custom-scrollbar::-webkit-scrollbar { display: none; }
        .custom-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }

        @keyframes fadeIn {
          from { opacity: 0; transform: translateY(10px) scale(0.98); }
          to { opacity: 1; transform: translateY(0) scale(1); }
        }

        @keyframes burn-effect {
          0% { transform: translateY(0) scale(1); opacity: 1; filter: sepia(0) brightness(1); clip-path: inset(0 0 0 0); }
          40% { filter: sepia(0.5) brightness(1.2) saturate(3) hue-rotate(-20deg); clip-path: inset(0 0 0 0); }
          100% { transform: translateY(-30px) scale(0.95); opacity: 0; filter: sepia(1) brightness(0.3) saturate(5) hue-rotate(-40deg); clip-path: inset(0 0 100% 0); }
        }
        .animate-burn-effect {
          animation: burn-effect 2s forwards cubic-bezier(0.4, 0, 0.2, 1);
        }
        
        @keyframes embers {
          0% { opacity: 1; transform: translateY(0) scale(1) translateX(0); }
          100% { opacity: 0; transform: translateY(-150px) scale(0) translateX(30px); }
        }
      `}</style>
    </div>
  );
}
