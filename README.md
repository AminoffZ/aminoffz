<img src="https://raw.githubusercontent.com/AminoffZ/aminoffz/main/catpop.svg" width=512 height=512 align="center" />

```svg
<?xml version="1.0" encoding="UTF-8"?>
<svg
  width="512"
  height="512"
  version="1.1"
  viewBox="-64 0 512 512"
  xmlns="http://www.w3.org/2000/svg"
  xmlns:cc="http://creativecommons.org/ns#"
  xmlns:dc="http://purl.org/dc/elements/1.1/"
  xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
>
  <title>catpop</title>
  <defs>
    <style>
      .fadeInOut {
        --opacity-start: 1;
        --opacity-end: 0;
        animation: fadeInOut 5s infinite;
      }

      .fadeOutIn {
        --opacity-start: 0;
        --opacity-end: 1;
        animation: fadeInOut 5s infinite;
      }

      #slams {
        --opacity-start: 1;
        --opacity-end: 0;
        animation: fadeInOut 5s infinite;
        animation-delay: 0.1s;
      }

      @keyframes fadeInOut {
        0%,
        3%,
        6%,
        9%,
        12%,
        15%,
        18%,
        21%,
        24%,
        27%,
        30%,
        33%,
        36%,
        39%,
        42%,
        45%,
        48%,
        51%,
        54%,
        57% {
          opacity: var(--opacity-start);
        }
        1.5%,
        4.5%,
        7.5%,
        10.5%,
        13.5%,
        16.5%,
        19.5%,
        22.5%,
        25.5%,
        28.5%,
        31.5%,
        34.5%,
        37.5%,
        40.5%,
        43.5%,
        46.5%,
        49.5%,
        52.5%,
        55.5%,
        58.5%,
        100% {
          opacity: var(--opacity-end);
        }
      }

      @keyframes fadeOutIn {
        0%,
        100% {
          opacity: 0;
        }
        50% {
          opacity: 1;
        }
      }

      @keyframes colorCycle {
        0% {
          filter: drop-shadow(var(--dx) var(--dy) var(--blur) red) invert(75%);
        }
        25% {
          filter: drop-shadow(var(--dx) var(--dy) var(--blur) blue) invert(75%);
        }
        50% {
          filter: drop-shadow(var(--dx) var(--dy) var(--blur) green) invert(75%);
        }
        75% {
          filter: drop-shadow(var(--dx) var(--dy) var(--blur) purple)
            invert(75%);
        }
        100% {
          filter: drop-shadow(var(--dx) var(--dy) var(--blur) red) invert(75%);
        }
      }

      .base-color {
        filter: invert(75%);
      }

      .glow {
        --dx: -16px;
        --dy: 32px;
        --blur: 28px;
        animation: colorCycle 10s infinite;
      }

      #laptop-screen {
        --dx: 4px;
        --dy: -4px;
        --blur: 4px;
        animation: colorCycle 10s infinite;
      }
    </style>
  </defs>
  <g class="glow">
    <path
      d="m210 168 17 20.667 15 4.666 49 19.834 21 11.166 6 2.667 7-2.667 19-7.333c0 7.078 0.394 14.092-1.333 21-0.97 3.877-3.415 7.111-4.334 11-0.848 3.595-0.818 7.405-1.666 11-0.697 2.95-2.419 5.852-1.5 9 1.243 4.263 5.572 8.032 7.666 12 5.766 10.924 13.167 25.353 13.167 38l-44-10c0.632 6 6.053 6.097 11 7.333 10.314 2.579 20.686 4.922 31 7.5 0 0 148.81 31.24 18-1-2.693-0.673-7.699-0.864-9.667-3-1.953-2.119-1.085-5.283-1.333-7.833-0.295-3.033-1.374-6.121-2.333-9-2.718-8.152-5.852-16.456-9.834-24-2.042-3.87-6.062-7.84-7.333-12-0.907-2.968 1.166-6.991 1.5-10 0.615-5.534 2.926-9.777 4.667-15 1.895-5.685 2.333-12.044 2.333-18 0-3.268 0.262-10.405-2.167-12.833-2.983-2.984-7.832 0.666-10.833 1.833-4.304 1.674-8.826 3.196-13 5.167-1.541 0.727-3.203 2.141-5 2.166-2.256 0.032-5.876-1.811-8-2.666-10.834-4.364-20.014-12.061-31-16.334-10.664-4.147-21.456-7.753-32-12-4.937-1.988-11.462-2.268-16-4.833-2.263-1.279-2.98-3.471-4.333-5.5-3.219-4.828-7.961-12.264-12.667-15.667-6.523-4.716-14.057 6.552-18 10.667-2.345 2.447-4.055 5.716-7 7.5-5.132 3.108-12.429 3.947-18 6.5-9.491 4.35-18.85 10.435-27 17-4.58 3.689-9.743 6.931-14 11-1.396 1.334-3.873 3.687-2.5 5.833 0.855 1.336 2.913 1.424 4.167 0.667 5.182-3.127 10.516-8.62 15.333-12.5 8.474-6.826 18.206-13.208 28-17.833 5.789-2.734 13.547-3.287 18.833-6.667 3.284-2.099 5.814-6.508 8.5-9.333 2.695-2.835 5.542-4.28 6.667-8.167m-38 66.5c-7.475 4.204-1.279 16.383 7 12 7.571-4.008 1.061-16.534-7-12m-159.29 5.8644c-4.0314-0.10337 83.286 22.38 83.286 22.38l2-5-42-10.333s-41.843-10.497-41.515-9.6202m191.51 15.209c3.086 7.818 10.971 7.295 18 6-0.215-8.162-6.528-2.501-11-6.167-2.208-1.81-1.701-6.16-5-6.5-2.857-0.294-4.882 2.974-8 2.667-3.164-0.312-5.579-6.582-8.833-4.5-2.921 1.869-0.087 6.756 1.833 8.167 3.258 2.392 9.637 1.749 13 0.333m51 7.333c-8.796 2.974-4.602 17.006 4 12.167 5.48-3.082 3.265-14.622-4-12.167m-107 11.667c0.873 8.294 18.329 7.944 25 9.333 17.706 3.689 35.449 8.113 53 12.5 9.811 2.453 20.895 6.167 31 6.167-0.853-8.099-18.343-8.669-25-10.333-19.896-4.974-39.916-9.816-60-14-7.146-1.489-16.858-5.171-24-3.667z"
      id="cat-and-table"
    />
    <path
      class="fadeInOut"
      d="m97 262c0.7572-4.111 0.342-6.895 0-11-1.0107-12.129-2.9767-26.101 8-34.333 2.969-2.227 5.239-3.127 9-2.5 1.931 0.321 4.223 0.994 6 1.833 7.765 3.667 9.888 14.652 18 17-0.494-4.692-3.356-9.036-5.833-13-7.822-12.515-27.264-16.206-36.834-3-4.9356 6.811-4.3333 17.024-4.3333 25 0 5.921-0.7179 18.003 6 20m171 40c9.419 0 5.09-8.492 5-15-0.157-11.297-1.308-27.046 12-31.667 7.667-2.662 16.502 3.908 20.667 9.667 3.035 4.197 3.65 7.804 9.333 9-0.462-4.386-3.455-7.296-5.667-11-1.701-2.85-2.619-6.547-5.333-8.667-9.927-7.755-25.692-5.794-32.667 4.667-3.212 4.818-3.333 11.462-3.333 17z"
      id="hands-up"
    />
    <path
      class="fadeInOut"
      d="m95 262c6.219 3.764 13.944 4.863 21 6.333 8.104 1.689 15.983 3.829 24 5.834 5.26 1.315 11.521 3.948 14-2.167-4.404-1.97-9.255-2.345-14-3.333-10.086-2.102-19.979-4.968-30-7.334-5.429-1.281-12.27-6.067-15 0.667m147 35 56 13.333 26 4.667c-0.638-5.898-9.99-6.859-15-7.833-16.372-3.184-32.936-6.372-49-10.834-4.901-1.361-17.231-6.442-18 0.667z"
      id="table-under-hands"
    />
    <path
      class="fadeOutIn"
      d="m158 273c-5.719-3.461-10.13-0.382-16 1.167-11.715 3.091-21.714 6.833-34 6.833-9.8015 0-17.768-6.404-13.5-17 1.65-4.096 5.3541-7.293 7.5-11-2.6311 0-5.7908-0.559-8 1.167-6.4159 5.012-7.6729 21.93-1.6667 27.5 4.7342 4.39 10.676 4.333 16.667 4.333 12.299 0 21.5-2.833 33-6.667 5.412-1.804 12.066-2.041 16-6.333m169 37v-1c-5.569-2.345-12.289-0.761-18 0.667-11.443 2.86-22.041 8.333-34 8.333-5.912 0-14.99 1.338-18.5-5-1.163-2.1-0.76-6.663-0.5-9 0.771-6.938 9.279-9.149 10-16-14.747 0-20.686 24.551-9 32.667 4.893 3.397 11.332 2.333 17 2.333 12.426 0 22.239-4.4 34-7.667 6.336-1.76 13.077-2.371 19-5.333"
      id="hands-down"
    />
    <path
      d="m81 275.33c-1.9056 0.296-9.4953 3.17-10.5 4.834-1.5233 2.523 1.1927 4.63 3.5 4.5 2.7652-0.156 7.7788-1.948 9.6667-4 2.1098-2.294 0.5782-5.836-2.6667-5.334m0 13.167c-4.1895 2.186-5.0281 11.267 0.8333 8 1.4126-0.787 4.3978-3.859 4.6667-5.5 0.5158-3.146-3.4048-3.593-5.5-2.5m27 5c-4.543 0.227-4.599 13.36 1 12.333 3.435-0.629 3.221-12.544-1-12.333m132 26.833c-2.396 0.533-7.149 1.633-8.5 3.834-2.12 3.453 1.609 5.303 4.5 4.5 2.242-0.623 7.295-2.061 8.833-3.834 2.989-3.443-2.123-5.102-4.833-4.5m8 9.167c-3.478 1.449-1.878 13.044 2 12.333 5.453-0.999 2.597-14.248-2-12.333m27 1c-2.323 0.363-2.805 2.656-2 4.5 1.108 2.537 6.667 11.889 10 10.5 5.044-2.102-3.525-15.699-8-15z"
      id="slams"
    />
    <path
      class="fadeOutIn"
      d="m94 263c5.6115-0.148 6.782-5.673 9.667-10 5.409-8.114 12.087-15.459 19.333-22 4.15-3.746 8.839-5.883 9-12-6.171 0.162-8.568 4.078-13 7.833-9.903 8.39-25 22.33-25 36.167z"
      id="left-chin"
    />
    <path
      class="fadeInOut"
      d="m105 278c2.707-0.783 4.349-3.023 7-3.833 3.159-0.966 6.902 0.15 10 0.666 6.719 1.12 13.347 2.263 20 3.834 2.294 0.541 9.752 3.198 9.5-1.667-0.163-3.149-8.263-3.805-10.5-4.333-9.337-2.205-18.394-3.667-28-3.667-6.055 0-10.742 2.489-8 9m196 43c-0.171-6.508-5.915-6.119-11-8.167-10.281-4.141-21.266-6.834-32-9.666-2.738-0.723-10.13-4.685-12.667-2.667-5.107 4.062 7.703 7.148 9.667 7.667 2.997 0.791 6.038 1.595 9 2.5 4.97 1.518 9.996 2.776 15 4.166 7.571 2.103 13.906 6.167 22 6.167z"
      id="laptop-under-hands"
    />
    <path
      d="m145 276c1.774 5.967 15.28 7.324 21 8.833 20.329 5.365 40.354 12.153 61 16.167 6.053 1.177 11.954 2.991 18 4.167 1.898 0.369 5.095 1.818 6.5-0.334 1.978-3.028-2.503-4.473-4.5-5-6.284-1.658-12.634-3.174-19-4.5-19.919-4.15-39.281-10.237-59-15.166-7.478-1.87-16.432-7.354-24-4.167m153 41 4 6-14 13-17 15.667-31 25.333c7.356 3.097 13.527-4.591 19-9 11.006-8.866 21.824-17.002 32.167-26.667 2.993-2.797 6.918-4.463 9.833-7.333 6.325-6.228 8.47-16.094-3-17z"
      class="laptop-frame"
    />
    <path
      d="m180 219c-2.247 5.336 2.022 12.838 8 13-0.132-5.033-2.986-11.509-8-13m73 32v2c5.08 2.139 12.342 0.819 17-2v-2c-4.897-2.062-12.293-0.354-17 2z"
      id="eyebrows"
    >
      <animate
        attributeName="opacity"
        values="0;0;0;0;0;0;0;0;0;0;0;1;1;0"
        keyTimes="0;0.05;0.1;0.15;0.2;0.25;0.3;0.4;0.45;0.5;0.79;0.8;0.95;1"
        begin="0s"
        dur="5s"
        repeatCount="indefinite"
      />
    </path>
  </g>
  <path
    id="laptop-screen"
    d="m12.167 246.5c-4.2908 3.089 2.177 13.25 3.6666 16.5 6.3106 13.769 10.124 27.785 17.833 41 1.7413 2.985 2.6628 7.55 5.3333 9.833 2.6775 2.289 5.9333 1.563 9 2.5 4.3384 1.326 8.7224 3.67 13 5.334 6.4098 2.492 13.472 3.49 20 5.666 25.362 8.454 51.654 14.552 77 23 13.014 4.338 25.763 9.007 39 12.5 11.392 3.007 22.794 6.943 34 10.834 2.987 1.037 9.064 5.093 12 3.166 6.735-4.42-2.768-14.485-5.667-18.833-11.114-16.672-23.662-32.453-33.166-50-2.387-4.405-5.215-11.479-9.167-14.667-3.057-2.465-7.326-2.85-11-3.666-8.664-1.926-17.388-3.847-26-6-32.43-8.108-66.036-13.567-98-23.334-11.042-3.374-23.517-5.84-34-10.5-3.069-1.364-10.45-5.769-13.833-3.333z"
  />
  <g>
    <path
      d="m87 119c1.0307-4.896-1.7475-6.433-6-8v-2c4.4883-1.299 6.8772-4.335 7-9-4.1536 0.109-13 5.075-13 10 0 4.534 8.2501 8.605 12 9m-1-12c0 1.063-0.3161 3.012 0.1667 4 2.5359 5.193 9.0259-1.297 3.8333-3.833-0.9885-0.483-2.9369-0.167-4-0.167z"
      id="output-start"
      class="base-color output"
    />
    <path
      d="m259 101h2c0.757-1.7974 1.932-4.8839 0.5-6.8333-2.706-3.6827-4.679 1.412-4.167 3.8333 0.239 1.1269 1.103 2.067 1.667 3m5-8c-0.323 1.532-0.566 2.4321-0.333 4 1.686 11.381 10.137-2.9401 0.333-4m-160 1v10c5.875-0.635 3.979-6.042 2-10h-2m7 0c-1.812 4.3036-1.144 7.861 4 8 0-4.0402 0.283-6.7267-4-8m90 13c-0.177-2.239-0.485-13.34-4.833-10.5-2.441 1.5937-0.167 7.988-0.167 10.5 0 3.531-1.677 12.824 0.5 15.667 1.633 2.132 7.149 1.562 9.5 1.333 7.332-0.713 13.518-9.028 6-14.667-3.088-2.316-7.359-2.333-11-2.333m-83 16c7.374-2.192 1.152-9.385 5.333-13.833 1.979-2.105 5.641-1.332 7.167 0.833 2.435 3.454 1.5 9.035 1.5 13 6.894-0.745 5.946-12.534 2.667-17-2.313-3.149-6.135-3.147-9.667-3-2.411 0.1-6.887 0.375-7.833 3-0.802 2.223-0.167 5.65-0.167 8 0 3.231-0.227 6.085 1 9m25-19c-3.755 8.918 1.799 23.959 13 16 1.098 3.393 2.94 3.289 6 2-0.735-2.792-2.674-5.066-3-8-0.277-2.491 0.693-5.616-0.167-8-0.545-1.512-2.119-2.511-3.666-1.5-2.358 1.54-0.097 14.529-6.167 12-2.872-1.197-2.592-9.685-4-12.5h-2m22 0c0 5.872-2.86 18.788 5 19v-13h4c0.13 4.958-0.241 13.442 5 15 1.296-3.077-0.696-14.769 5-13.833 4.76 0.781 2.109 6.9 3.167 9.833 0.545 1.512 2.119 2.511 3.666 1.5 3.398-2.219 0.789-13.092-2-15-3.222-2.205-6.552-0.514-9.833-0.833-4.62-0.45-9.111-2.538-14-2.667m71 15-13-1c2.738-1.153 7.517 0.168 9.833-1.5 2.55-1.836 1.286-7.534-0.833-9.167-7.343-5.657-16.326 4.115-13.667 11.667 2.351 6.675 16.847 7.786 17.667 0m5 6h2l3.167-13.5 10.833-0.5c-1.681-5.655-12.63-7.289-16.833-2.833-3.313 3.511-1.023 13.121 0.833 16.833m-12-14v2h-5l5-2m-18 6-10 2v-7c5.045 0 7.973-0.136 10 5z"
      id="output-text"
      fill="turquoise"
      class="output"
    />
    <animate
      attributeName="opacity"
      values="0;0;0;0;0;0;0;0;0;0;0;1;1;0"
      keyTimes="0;0.05;0.1;0.15;0.2;0.25;0.3;0.4;0.45;0.5;0.59;0.6;0.9;1"
      begin="0s"
      dur="5s"
      repeatCount="indefinite"
    />
  </g>

  <path
    d="m77 43c-2.5088 5.9585 2.7655 6.1791 4.6667 11 1.5947 4.0437-8.042 5.4306-5.1667 9.8333 2.1421 3.2802 11.619-4.4016 12.667-6.8333 1.9005-4.4119-8.582-12.934-12.167-14z"
    class="line-start"
    id="input-start"
  />
  <path
    d="m77 43c-2.5088 5.9585 2.7655 6.1791 4.6667 11 1.5947 4.0437-8.042 5.4306-5.1667 9.8333 2.1421 3.2802 11.619-4.4016 12.667-6.8333 1.9005-4.4119-8.582-12.934-12.167-14z"
    class="base-color"
  />
  <g class="input-text">
    <g fill="slateblue">
      <path
        d="m111 36v9l-7 1v2l7 2c0 4.3458-1.213 10.383 2.333 13.667 4.904 4.5401 15.469 3.8522 15.667-3.6667-2.122 0.1675-3.941 1.1332-6 1.3333-7.76 0.7545-7-5.7755-7-11.333l9-1-7.833-4.5-2.167-8.5z"
      >
        <animate
          attributeName="opacity"
          values="0;0;1;1;0"
          keyTimes="0;0.04;0.05;0.9;1"
          begin="0s"
          dur="5s"
          repeatCount="indefinite"
        />
      </path>
      <path
        d="m131 50c0.183 6.9613 5.586 11.974 12 14l-4 11c8.961-0.9432 13.009-17.853 10-25h-2l-3.167 7.6667-3.833-1.6667z"
      >
        <animate
          attributeName="opacity"
          values="0;0;0;1;1;0"
          keyTimes="0;0.05;0.09;0.1;0.9;1"
          begin="0s"
          dur="5s"
          repeatCount="indefinite"
        />
      </path>
      <path
        d="m161 63c2.886 0 6.546 0.5571 9-1.3333 3.822-2.9446 1.319-9.0394-2-11.333-2.603-1.7988-7.026-1.7757-10-1-5.868 1.5308-2 13.575-2 18.667 0 2.0056-0.793 6.2943 2 6.8333 4.548 0.8778 3-9.2774 3-11.833m6-5c-3.921 0-6.517 0.4637-7-4 3.79 0 5.852 0.1382 7 4z"
      >
        <animate
          attributeName="opacity"
          values="0;0;0;0;1;1;0"
          keyTimes="0;0.05;0.1;0.14;0.15;0.9;1"
          begin="0s"
          dur="5s"
          repeatCount="indefinite"
        />
      </path>
      <path
        d="m194 62-12-2c2.043-0.3764 5.168-0.5402 6.667-2.1667 3.291-3.5718-0.524-10.522-4.667-11.5-4.489-1.06-6.853 4.1423-7 7.6667-0.174 4.1668-0.546 8.8966 3 11.833 4.796 3.972 13.295 2.8679 14-3.8333m-9-9v1l-3 1v-3z"
      >
        <animate
          attributeName="opacity"
          values="0;0;0;0;0;1;1;0"
          keyTimes="0;0.05;0.1;0.15;0.19;0.2;0.9;1"
          begin="0s"
          dur="5s"
          repeatCount="indefinite"
        />
      </path>
      <path
        d="m201.17 49.5c-2.198 1.3878-2.032 4.2502-2.5 6.5-1.382 6.6304 2.921 15.889 11.333 11.5 9.999-5.2167 0.732-24.041-8.833-18m2.833 4.5c0.847 0.0891 2.231-0.1188 3 0.5 6.785 5.4615-4.359 13.206-4 3.5 0.051-1.3737 0.624-2.7025 1-4z"
      >
        <animate
          attributeName="opacity"
          values="0;0;0;0;0;0;1;1;0"
          keyTimes="0;0.05;0.1;0.15;0.2;0.24;0.25;0.9;1"
          begin="0s"
          dur="5s"
          repeatCount="indefinite"
        />
      </path>
      <path
        d="m219 57 4 1 1 10c4.947-1.4706 4-5.549 4-10 3.079-0.3329 3.667-0.9207 4-4-6.664-2.7018-2.997-8.5892-2-14 1.749 0.8286 7.713 3.7961 6.833-1-0.79-4.3099-8.027-4.4544-10.5-1.8333-3.66 3.88-2.001 9.4049-3.5 13.833-0.812 2.4012-3.069 3.4297-3.833 6z"
      >
        <animate
          attributeName="opacity"
          values="0;0;0;0;0;0;0;1;1;0"
          keyTimes="0;0.05;0.1;0.15;0.2;0.25;0.29;0.3;0.9;1"
          begin="0s"
          dur="5s"
          repeatCount="indefinite"
        />
      </path>
    </g>
    <g class="base-color">
      <path
        d="m285 37v11l-1 11h-1l-9-17-5-3.5-2 7.5 2 21c5.12-2.2587 3-11.956 3-17h1c1.813 6.8903 7.223 17 15 17 1.211-6.5757 2.847-15.368 1.833-22-0.611-3.9992-0.303-7.5103-4.833-8z"
      >
        <animate
          attributeName="opacity"
          values="0;0;0;0;0;0;0;0;1;1;0"
          keyTimes="0;0.05;0.1;0.15;0.2;0.25;0.3;0.39;0.4;0.9;1"
          begin="0s"
          dur="5s"
          repeatCount="indefinite"
        />
      </path>
      <path
        d="m310 65h1l5 2c-0.293-3.7121-2.672-10.895-5.333-13.667-5.651-5.8862-15.931-1.5453-17.334 5.6667-1.73 8.8973 12.239 12.038 16.667 6m-4-2c-1.202 0-2.824 0.2441-4 0l-2-0.5c-6.09-5.8937 5.74-8.9458 6.833-4.5 0.348 1.4139-0.573 3.5897-0.833 5z"
      >
        <animate
          attributeName="opacity"
          values="0;0;0;0;0;0;0;0;0;1;1;0"
          keyTimes="0;0.05;0.1;0.15;0.2;0.25;0.3;0.4;0.44;0.45;0.9;1"
          begin="0s"
          dur="5s"
          repeatCount="indefinite"
        />
      </path>
      <path
        d="m336 58c-5.055-2.9268-7.67-8.4027-11.167-13-1.15-1.5127-2.493-4.2772-4.833-3.8333-2.794 0.5298-2 4.8347-2 6.8333 0 5.2374-2.564 17.29 4 18l1-15h1c1.208 4.5912 4.633 8.3808 7.667 12 1.385 1.653 3.524 4.2332 6 2.5 1.834-1.2841 2.199-4.5214 2.666-6.5 1.518-6.4266 3.272-15.812 0.667-22-5.781 1.7187-5 15.424-5 21z"
      >
        <animate
          attributeName="opacity"
          values="0;0;0;0;0;0;0;0;0;0;1;1;0"
          keyTimes="0;0.05;0.1;0.15;0.2;0.25;0.3;0.4;0.45;0.49;0.5;0.9;1"
          begin="0s"
          dur="5s"
          repeatCount="indefinite"
        />
      </path>
    </g>
  </g>
  <metadata>
    <rdf:RDF>
      <cc:Work rdf:about="">
        <cc:license
          rdf:resource="http://creativecommons.org/licenses/by-nc-sa/4.0/"
        />
        <dc:title>catpop</dc:title>
        <dc:creator>
          <cc:Agent>
            <dc:title>AminoffZ</dc:title>
          </cc:Agent>
        </dc:creator>
        <dc:source
          >https://twitter.com/StrayRogue/status/992994454058381312</dc:source
        >
        <dc:date>2023-10-18</dc:date>
        <dc:identifier
          >https://raw.githubusercontent.com/AminoffZ/aminoffz/main/catpop.svg</dc:identifier
        >
      </cc:Work>
      <cc:License rdf:about="http://creativecommons.org/licenses/by-nc-sa/4.0/">
        <cc:permits rdf:resource="http://creativecommons.org/ns#Reproduction" />
        <cc:permits rdf:resource="http://creativecommons.org/ns#Distribution" />
        <cc:requires rdf:resource="http://creativecommons.org/ns#Notice" />
        <cc:requires rdf:resource="http://creativecommons.org/ns#Attribution" />
        <cc:prohibits
          rdf:resource="http://creativecommons.org/ns#CommercialUse"
        />
        <cc:permits
          rdf:resource="http://creativecommons.org/ns#DerivativeWorks"
        />
        <cc:requires rdf:resource="http://creativecommons.org/ns#ShareAlike" />
      </cc:License>
    </rdf:RDF>
  </metadata>
</svg>

```
