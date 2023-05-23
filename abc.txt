(window["@jfrog/ui-platform-microfrontend-client"] = window["@jfrog/ui-platform-microfrontend-client"] || []).push([["login"], {
    "0035": function(t, e, n) {
        "use strict";
        n("81fb")
    },
    "0129": function(t, e) {},
    "0513": function(t, e, n) {
        "use strict";
        var o = n("44c9");
        n.o(o, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return o["LoginFlow"]
        }));
        var r = n("8073");
        n.o(r, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return r["LoginFlow"]
        }));
        n("50b3");
        var i = n("58c3");
        n.o(i, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return i["LoginFlow"]
        }));
        var s = n("3f84");
        n.o(s, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return s["LoginFlow"]
        }));
        var a = n("be47");
        n.o(a, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return a["LoginFlow"]
        }));
        var c = n("1f64");
        n.o(c, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return c["LoginFlow"]
        }));
        var u = n("87ae");
        n.o(u, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return u["LoginFlow"]
        }));
        var l = n("e336");
        n.o(l, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return l["LoginFlow"]
        }));
        var d = n("5ac8");
        n.o(d, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return d["LoginFlow"]
        }));
        n("dd7a");
        var f = n("7569");
        n.o(f, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return f["LoginFlow"]
        }))
    },
    "0566": function(t, e) {},
    "0cbf": function(t, e, n) {
        "use strict";
        n("2665")
    },
    "189d5": function(t, e, n) {},
    "18c8": function(t, e) {},
    "1f64": function(t, e, n) {
        "use strict";
        var o = n("cc19");
        n.o(o, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return o["LoginFlow"]
        }))
    },
    2549 : function(t, e) {},
    2665 : function(t, e, n) {},
    "27e3": function(t, e) {},
    "2ebb": function(t, e) {},
    3456 : function(t, e) {},
    "3c0b": function(t, e, n) {},
    "3f84": function(t, e, n) {
        "use strict";
        var o = n("8ca6");
        n.o(o, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return o["LoginFlow"]
        }))
    },
    "44c9": function(t, e, n) {
        "use strict";
        var o = n("ae5d");
        n.o(o, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return o["LoginFlow"]
        }))
    },
    "45b9": function(t, e, n) {
        "use strict";
        n("cd82")
    },
    4825 : function(t, e) {},
    "50b3": function(t, e, n) {
        "use strict";
        var o; (function(t) {
            t["USERS"] = "users",
            t["GROUPS"] = "groups"
        })(o || (o = {}))
    },
    53523 : function(t, e) {},
    "540e": function(t, e) {},
    56672 : function(t, e) {},
    "58c3": function(t, e, n) {
        "use strict";
        var o = n("dfdf");
        n.o(o, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return o["LoginFlow"]
        }));
        var r = n("b04c");
        n.o(r, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return r["LoginFlow"]
        }));
        var i = n("668d");
        n.o(i, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return i["LoginFlow"]
        }));
        var s = n("27e3");
        n.o(s, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return s["LoginFlow"]
        }));
        n("d036");
        var a = n("5cc5");
        n.o(a, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return a["LoginFlow"]
        }));
        var c = n("d4db");
        n.d(e, "LoginFlow", (function() {
            return c["a"]
        }));
        n("6988"),
        n("2549"),
        n("df72"),
        n("a583"),
        n("3456"),
        n("8466"),
        n("a866"),
        n("4825"),
        n("56672")
    },
    "590d": function(t, e, n) {
        "use strict";
        n.d(e, "a", (function() {
            return o
        }));
        var o = Function.prototype
    },
    5927 : function(t, e) {},
    "5ac8": function(t, e) {},
    "5ada": function(t, e, n) {
        "use strict";
        n("189d5")
    },
    "5b1c": function(t, e, n) {
        "use strict";
        var o = function() {
            var t = this,
            e = t.$createElement,
            n = t._self._c || e;
            return n("el-button", {
                staticClass: "login-provider-button",
                attrs: {
                    type: "floating",
                    "data-cy": "loginProviderButton"
                },
                on: {
                    click: t.handleClick
                }
            },
            [n("jf-icon", {
                attrs: {
                    icon: t.icon,
                    size: "huge"
                }
            }), n("tooltip-on-overflow", {
                attrs: {
                    "open-delay": 800
                }
            },
            [n("span", [t._v(t._s(t.buttonText))])])], 1)
        },
        r = [],
        i = {
            name: "ProviderButton",
            props: {
                payload: Object,
                icon: String,
                buttonText: String,
                buttonFn: Function
            },
            methods: {
                handleClick: function() {
                    this.buttonFn(this.payload)
                }
            }
        },
        s = i,
        a = (n("0cbf"), n("2877")),
        c = Object(a["a"])(s, o, r, !1, null, "0ff9f18c", null);
        e["a"] = c.exports
    },
    "5b44": function(t, e) {},
    "5b71": function(t, e) {},
    "5cc5": function(t, e) {},
    "609e": function(t, e, n) {
        "use strict";
        n("c517")
    },
    "61d0": function(t, e, n) {
        "use strict";
        n("d685")
    },
    "651ba": function(t, e, n) {
        t.exports = n.p + "img/banner.b3c1f029.svg"
    },
    "668d": function(t, e) {},
    6988 : function(t, e) {},
    "6cc2": function(t, e, n) {
        "use strict";
        var o = n("7eec");
        n.o(o, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return o["LoginFlow"]
        }));
        var r = n("e8f2");
        n.o(r, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return r["LoginFlow"]
        }))
    },
    "70f1": function(t, e) {},
    7188 : function(t, e, n) {
        t.exports = n.p + "img/computer.0539f095.svg"
    },
    "734b": function(t, e, n) {
        "use strict";
        var o = function() {
            var t = this,
            e = t.$createElement,
            n = t._self._c || e;
            return t.isMobile && t.showOverlay ? n("div", {
                staticClass: "mobile-overlay",
                attrs: {
                    "data-cy": "mobileOverlay"
                }
            },
            [n("img", {
                staticClass: "width--full",
                attrs: {
                    src: t.banner,
                    alt: "",
                    "data-cy": "bannerImg"
                }
            }), n("img", {
                staticClass: "width--full",
                attrs: {
                    src: t.computer,
                    alt: "",
                    "data-cy": "computerImg"
                }
            }), n("jf-text", {
                staticClass: "padding--l-48 padding--r-48 margin--t-24 margin--b-0 big-title",
                attrs: {
                    size: "large",
                    "data-cy": "mobileTitle"
                }
            },
            [t._v("\n\t\tUse a desktop browser for optimal experience\n\t")]), n("jf-text", {
                staticClass: "padding--l-48 padding--r-48 margin--t-24 margin--b-24",
                attrs: {
                    size: "large",
                    weight: 400,
                    "data-cy": "mobileBody"
                }
            },
            [t._v("\n\t\tThe JFrog platform is designed for a desktop browser. Using mobile browsers is not recommended.\n\t")]), t.isFromCli ? t._e() : n("a", {
                staticClass: "padding--l-48 jf-link font--size-large continue padding--b-24",
                attrs: {
                    href: "javascript:void(0)",
                    "data-cy": "continueAnywayLink"
                },
                on: {
                    click: function(e) {
                        t.showOverlay = !1
                    }
                }
            },
            [t._v("Continue anyway")])], 1) : t._e()
        },
        r = [],
        i = n("8df8"),
        s = n.n(i),
        a = n("7188"),
        c = n.n(a),
        u = n("651ba"),
        l = n.n(u),
        d = n("4a4e"),
        f = {
            name: "MobileWelcomeScreen",
            components: {
                JfText: d["a"]
            },
            data: function() {
                return {
                    isMobile: s()(),
                    body: document.body,
                    showOverlay: !0,
                    computer: c.a,
                    banner: l.a
                }
            },
            computed: {
                isFromCli: function() {
                    var t = this.$route.query.source;
                    return "cli" === t
                }
            }
        },
        g = f,
        h = (n("45b9"), n("2877")),
        p = Object(h["a"])(g, o, r, !1, null, "0147caca", null);
        e["a"] = p.exports
    },
    7480 : function(t, e) {},
    7569 : function(t, e, n) {
        "use strict";
        var o = n("f0ef");
        n.o(o, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return o["LoginFlow"]
        }))
    },
    "7eec": function(t, e) {},
    8073 : function(t, e, n) {
        "use strict";
        var o = n("9a36");
        n.o(o, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return o["LoginFlow"]
        }));
        var r = n("0129");
        n.o(r, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return r["LoginFlow"]
        }));
        var i = n("7480");
        n.o(i, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return i["LoginFlow"]
        }));
        var s = n("540e");
        n.o(s, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return s["LoginFlow"]
        }));
        n("94f9")
    },
    "81fb": function(t, e, n) {},
    8466 : function(t, e) {},
    "87ae": function(t, e, n) {
        "use strict";
        var o = n("6cc2");
        n.o(o, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return o["LoginFlow"]
        }))
    },
    "88b0": function(t, e, n) {
        "use strict";
        n.r(e);
        var o = function() {
            var t = this,
            e = t.$createElement,
            n = t._self._c || e;
            return n("div", {
                staticClass: "auth-provider-page-content flex height--full"
            },
            [n("mobile-welcome-screen"), n("div", {
                staticClass: "login-modal-image flex height--full flex--justify-c flex--align-center"
            },
            [n("jf-icon", {
                style: {
                    "--width": "210px",
                    "--height": "210px"
                },
                attrs: {
                    icon: "colorful/navigation/logo-jfrog",
                    size: "large"
                }
            })], 1), n("div", {
                staticClass: "flex flex--dir-col flex--align-center flex--justify-c width--full flex--1"
            },
            [t.loading ? n("div", {
                directives: [{
                    name: "loading",
                    rawName: "v-loading",
                    value: t.loading,
                    expression: "loading"
                }],
                staticClass: "spinner"
            }) : t._e(), n("jf-text", {
                attrs: {
                    size: "large",
                    color: "color--text-bright"
                }
            },
            [t._v(" " + t._s(t.loadingMessage) + " ")])], 1)], 1)
        },
        r = [],
        i = n("a34a"),
        s = n.n(i),
        a = n("6189"),
        c = {
            npmLogin: function(t, e) {
                return t.put(a["b"], e)
            }
        },
        u = n("dae9"),
        l = n("ccf4"),
        d = n("1e4c"),
        f = n("c791"),
        g = n.n(f),
        h = n("734b"),
        p = n("4a4e"),
        w = n("7468");
        function m(t, e) {
            return S(t) || F(t, e) || b(t, e) || v()
        }
        function v() {
            throw new TypeError("Invalid attempt to destructure non-iterable instance.\nIn order to be iterable, non-array objects must have a [Symbol.iterator]() method.")
        }
        function b(t, e) {
            if (t) {
                if ("string" === typeof t) return L(t, e);
                var n = Object.prototype.toString.call(t).slice(8, -1);
                return "Object" === n && t.constructor && (n = t.constructor.name),
                "Map" === n || "Set" === n ? Array.from(t) : "Arguments" === n || /^(?:Ui|I)nt(?:8|16|32)(?:Clamped)?Array$/.test(n) ? L(t, e) : void 0
            }
        }
        function L(t, e) { (null == e || e > t.length) && (e = t.length);
            for (var n = 0,
            o = new Array(e); n < e; n++) o[n] = t[n];
            return o
        }
        function F(t, e) {
            var n = null == t ? null: "undefined" !== typeof Symbol && t[Symbol.iterator] || t["@@iterator"];
            if (null != n) {
                var o, r, i = [],
                s = !0,
                a = !1;
                try {
                    for (n = n.call(t); ! (s = (o = n.next()).done); s = !0) if (i.push(o.value), e && i.length === e) break
                } catch(c) {
                    a = !0,
                    r = c
                } finally {
                    try {
                        s || null == n["return"] || n["return"]()
                    } finally {
                        if (a) throw r
                    }
                }
                return i
            }
        }
        function S(t) {
            if (Array.isArray(t)) return t
        }
        function y(t, e, n, o, r, i, s) {
            try {
                var a = t[i](s),
                c = a.value
            } catch(u) {
                return void n(u)
            }
            a.done ? e(c) : Promise.resolve(c).then(o, r)
        }
        function O(t) {
            return function() {
                var e = this,
                n = arguments;
                return new Promise((function(o, r) {
                    var i = t.apply(e, n);
                    function s(t) {
                        y(i, o, r, s, a, "next", t)
                    }
                    function a(t) {
                        y(i, o, r, s, a, "throw", t)
                    }
                    s(void 0)
                }))
            }
        }
        var C = {
            name: "authProviderLogin",
            components: {
                MobileWelcomeScreen: h["a"],
                JfText: p["a"],
                JfIcon: w["a"]
            },
            data: function() {
                return {
                    loading: !0,
                    success: !1,
                    errorMessage: "",
                    logoImg: g.a
                }
            },
            mounted: function() {
                switch (window.hideSplashPulse(), this.$route.params.type) {
                case "npm":
                    this.doNpmLogin();
                    break;
                default:
                    this.goToHome()
                }
            },
            computed: {
                loadingMessage: function() {
                    var t;
                    switch (!0) {
                    case this.loading:
                        return "Connecting to npm registry...";
                    case this.success:
                        return "Login performed successfully. Redirecting to home page.";
                    default:
                        return null !== (t = this.errorMessage) && void 0 !== t ? t: "Error connecting to Artifactory."
                    }
                }
            },
            methods: {
                doNpmLogin: function() {
                    var t = O(s.a.mark((function t() {
                        var e, n, o, r, i;
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                return t.prev = 0,
                                e = this.$route.query,
                                t.next = 4,
                                c.npmLogin(this.$store.$apiClient, e);
                            case 4:
                                this.success = !0,
                                setTimeout(this.goToHome.bind(this), 5e3),
                                t.next = 14;
                                break;
                            case 8:
                                t.prev = 8,
                                t.t0 = t["catch"](0),
                                n = new l["b"](t.t0),
                                o = n.errors,
                                r = m(o, 1),
                                i = r[0].message,
                                this.errorMessage = null !== i && void 0 !== i ? i: "",
                                console.error("Error connecting npm registry.", i);
                            case 14:
                                return t.prev = 14,
                                this.loading = !1,
                                this.cleanUp(),
                                t.finish(14);
                            case 18:
                            case "end":
                                return t.stop()
                            }
                        }), t, this, [[0, 8, 14, 18]])
                    })));
                    function e() {
                        return t.apply(this, arguments)
                    }
                    return e
                } (),
                goToHome: function() {
                    var t = O(s.a.mark((function t() {
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                return t.next = 2,
                                this.$store.dispatch(u["a"].actions.NAVIGATE, {
                                    name: "home"
                                });
                            case 2:
                            case "end":
                                return t.stop()
                            }
                        }), t, this)
                    })));
                    function e() {
                        return t.apply(this, arguments)
                    }
                    return e
                } (),
                cleanUp: function() {
                    Object(d["a"])()
                }
            }
        },
        A = C,
        x = (n("609e"), n("2877")),
        E = Object(x["a"])(A, o, r, !1, null, "7ebc9f54", null);
        e["default"] = E.exports
    },
    "8b82": function(t, e, n) {
        t.exports = n.p + "img/free-tier.2ec1d21b.svg"
    },
    "8ca6": function(t, e) {},
    "8df8": function(t, e, n) {
        "use strict";
        t.exports = i,
        t.exports.isMobile = i,
        t.exports.
    default = i;
        const o = /(android|bb\d+|meego).+mobile|armv7l|avantgo|bada\/|blackberry|blazer|compal|elaine|fennec|hiptop|iemobile|ip(hone|od)|iris|kindle|lge |maemo|midp|mmp|mobile.+firefox|netfront|opera m(ob|in)i|palm( os)?|phone|p(ixi|re)\/|plucker|pocket|psp|series[46]0|symbian|treo|up\.(browser|link)|vodafone|wap|windows (ce|phone)|xda|xiino/i,
        r = /android|ipad|playbook|silk/i;
        function i(t) {
            t || (t = {});
            let e = t.ua;
            if (e || "undefined" === typeof navigator || (e = navigator.userAgent), e && e.headers && "string" === typeof e.headers["user-agent"] && (e = e.headers["user-agent"]), "string" !== typeof e) return ! 1;
            let n = o.test(e) || !!t.tablet && r.test(e);
            return ! n && t.tablet && t.featureDetect && navigator && navigator.maxTouchPoints > 1 && -1 !== e.indexOf("Macintosh") && -1 !== e.indexOf("Safari") && (n = !0),
            n
        }
    },
    "94f9": function(t, e, n) {
        "use strict";
        var o; (function(t) {
            t["COLD"] = "COLD",
            t["WARM"] = "WARM"
        })(o || (o = {}))
    },
    9812 : function(t, e, n) {
        "use strict";
        n("3c0b")
    },
    "9a36": function(t, e) {},
    a583: function(t, e) {},
    a58c: function(t, e) {},
    a866: function(t, e) {},
    add1: function(t, e, n) {
        "use strict";
        var o; (function(t) {
            t["X_ARTIFACTORY_FILENAME"] = "x-artifactory-filename",
            t["CONTENT_DISPOSITION"] = "content-disposition",
            t["CONTENT_TYPE"] = "content-type",
            t["X_FORWARDED_FOR"] = "x-forwarded-for",
            t["X_ORIGIN_USERNAME"] = "x-origin-username",
            t["X_ORIGIN_USER_ADDRESS"] = "x-origin-user-address"
        })(o || (o = {}))
    },
    ae5d: function(t, e) {},
    b04c: function(t, e) {},
    b3ef: function(t, e, n) {
        "use strict";
        n.r(e);
        var o = function() {
            var t = this,
            e = t.$createElement,
            n = t._self._c || e;
            return n("div", {
                staticClass: "login-page-form-container"
            },
            [n("login-form-title"), t.isModeFetched && t.isRegularScreenMode ? n("el-form", {
                ref: "loginForm",
                staticClass: "login-page-form-content",
                attrs: {
                    model: t.model,
                    rules: t.rules,
                    autocomplete: "off",
                    "label-position": "top",
                    name: "LoginForm"
                },
                nativeOn: {
                    submit: function(e) {
                        return e.preventDefault(),
                        t.onLoginClick.apply(null, arguments)
                    }
                }
            },
            [n("el-form-item", {
                staticClass: "form-error",
                attrs: {
                    error: t.serverErrorMessage
                },
                scopedSlots: t._u([{
                    key: "error",
                    fn: function(t) {
                        var e = t.error;
                        return [n("el-alert", {
                            attrs: {
                                closable: !1,
                                "show-icon": !0,
                                title: e,
                                type: "error"
                            }
                        })]
                    }
                }], null, !1, 2808025597)
            }), t.hideBasicMode ? t._e() : n("div", {
                staticClass: "basic-auth-container"
            },
            [n("el-form-item", {
                staticClass: "el-form-item-input-container",
                attrs: {
                    label: "Username",
                    prop: "username"
                }
            },
            [n("el-input", {
                ref: "username",
                staticClass: "login-form-input",
                attrs: {
                    autocomplete: "on",
                    name: "username"
                },
                model: {
                    value: t.model.username,
                    callback: function(e) {
                        t.$set(t.model, "username", e)
                    },
                    expression: "model.username"
                }
            }), t.isSaas ? n("div", {
                staticClass: "cloud-help-tooltip-free-tier"
            },
            [n("help-tooltip", {
                attrs: {
                    html: t.saasTooltip,
                    tabindex: -1,
                    effect: "dark",
                    placement: "top",
                    "popper-class": "login-help-tooltip-popper"
                }
            })], 1) : t._e()], 1), n("el-form-item", {
                staticClass: "el-form-item-input-container",
                attrs: {
                    label: "Password",
                    prop: "password"
                }
            },
            [n("el-input", {
                staticClass: "login-form-input",
                attrs: {
                    id: "password-input",
                    autocomplete: "on",
                    name: "password",
                    "show-password": "",
                    type: "password"
                },
                model: {
                    value: t.model.password,
                    callback: function(e) {
                        t.$set(t.model, "password", e)
                    },
                    expression: "model.password"
                }
            })], 1), n("div", {
                staticClass: "el-form-item-login-actions-container"
            },
            [t.rememberMeEnabled ? n("el-checkbox", {
                staticClass: "remember-me",
                attrs: {
                    label: "Remember me"
                },
                model: {
                    value: t.model.rememberMe,
                    callback: function(e) {
                        t.$set(t.model, "rememberMe", e)
                    },
                    expression: "model.rememberMe"
                }
            }) : t._e(), t.canForgotPassword ? n("el-link", {
                staticClass: "forgot-password",
                attrs: {
                    underline: !1,
                    tabindex: "0"
                },
                on: {
                    click: t.goToForgotPassword
                }
            },
            [t._v("\n          Forgot Password?\n        ")]) : t._e()], 1), n("el-form-item", {
                staticClass: "el-form-item-button-container"
            },
            [n("el-button", {
                staticClass: "width--full",
                attrs: {
                    loading: t.loading,
                    block: "",
                    "native-type": "submit",
                    type: "brand"
                }
            },
            [t._v("\n          Login\n        ")])], 1)], 1), t.haveSsoData && !t.hideOauthSection ? n("el-form-item", {
                staticClass: "additional-signin"
            },
            [n("el-divider", {
                staticClass: "additional-signin-title",
                attrs: {
                    "data-cy": "orSignInWith"
                }
            },
            [t._v(t._s(t.ssoSignInText))]), t.haveSsoData ? n("div", {
                staticClass: "additional-signin",
                class: {
                    "flex--justify-c": t.centerSsoItems
                }
            },
            t._l(t.ssoMethods, (function(e, o) {
                return n("provider-button", {
                    key: o,
                    attrs: {
                        "button-fn": t.handleSsoClick,
                        "button-text": t.getVendorName(e.name),
                        icon: t.getIcon(e),
                        payload: e
                    }
                })
            })), 1) : t._e()], 1) : t._e()], 1) : t.isModeFetched ? n("div", {
                staticClass: "additional-signin margin--t-32 flex flex--justify-c"
            },
            [n("jf-text", [t._v("Log in using one of the following:")]), n("section", {
                staticClass: "width--full flex flex--justify-b flex--wrap"
            },
            t._l(t.ssoData, (function(e, o) {
                return n("provider-button", {
                    key: o,
                    attrs: {
                        "button-fn": t.handleSsoClick,
                        "button-text": e.name,
                        icon: t.getIcon(e),
                        payload: e
                    }
                })
            })), 1), n("el-button", {
                staticClass: "margin--t-32",
                attrs: {
                    type: "link"
                },
                on: {
                    click: t.changeScreenMode
                }
            },
            [t._v("Go to internal login")])], 1) : t._e()], 1)
        },
        r = [],
        i = n("a34a"),
        s = n.n(i),
        a = n("8bbf"),
        c = n.n(a),
        u = n("2f62"),
        l = n("b908"),
        d = n("a39c"),
        f = function() {
            var t = this,
            e = t.$createElement,
            o = t._self._c || e;
            return o("div", [t.showDetailedMessage ? o("div", {
                staticClass: "detailed-message"
            },
            [o("img", {
                staticClass: "free-tier-image",
                attrs: {
                    src: n("8b82"),
                    alt: ""
                }
            }), o("div", {
                staticClass: "header"
            },
            [t._v("Your environment is ready!")]), t.hasAuthMethodAndNotBasic ? t._e() : o("div", {
                staticClass: "subheader"
            },
            [t._v("Enter your login credentials to start your DevOps journey")])]) : o("span", {
                staticClass: "login-form-title"
            },
            [t._v("Welcome to JFrog")])])
        },
        g = [],
        h = "firstRedirect",
        p = "auth_method",
        w = c.a.extend({
            name: "LoginFormTitle",
            data: function() {
                return {
                    isRedirectFromFreeTier: !1
                }
            },
            mounted: function() {
                this.firstRedirectQuery && this.setQueryInLocalStorage(),
                this.firstRedirectLocalStorage && this.setDetailedMessage()
            },
            computed: {
                showDetailedMessage: function() {
                    return this.isRedirectFromFreeTier
                },
                firstRedirectQuery: function() {
                    return this.$route.query[h]
                },
                hasAuthMethodAndNotBasic: function() {
                    return this.$route.query[p] && "basic" !== this.$route.query[p]
                },
                firstRedirectLocalStorage: function() {
                    return localStorage.getItem(h)
                }
            },
            methods: {
                setQueryInLocalStorage: function() {
                    localStorage.setItem(h, "true");
                    var t = Object.assign({},
                    this.$route.query);
                    delete t.firstRedirect,
                    this.$router.replace({
                        query: t
                    })
                },
                setDetailedMessage: function() {
                    var t;
                    this.isRedirectFromFreeTier = !0,
                    localStorage.removeItem(h);
                    var e = document.getElementsByClassName("spacer");
                    null === (t = e[0]) || void 0 === t || t.classList.remove("spacer")
                }
            }
        }),
        m = w,
        v = (n("61d0"), n("2877")),
        b = Object(v["a"])(m, f, g, !1, null, "0144d34a", null),
        L = b.exports,
        F = n("5b1c"),
        S = n("de2e"),
        y = n("0513"),
        O = n("590d"),
        C = n("7468"),
        A = n("4a4e"),
        x = n("92ea"),
        E = n("ae99"),
        _ = n("822a"),
        k = Object(E["a"])(_["b"].ACCESS.LOGIN_FLOW, (function() {
            return {
                computed: {
                    getLoginFlow: function() {
                        return y["LoginFlow"].ACCESS
                    }
                }
            }
        })),
        P = Object(E["a"])(_["b"].COMMON.CUSTOM_CLOUD.ALIBABA, (function() {
            return {
                computed: {
                    haveSsoData: function() {
                        return ! 1
                    }
                }
            }
        })),
        T = n("fcd4");
        function R(t, e, n, o, r, i, s) {
            try {
                var a = t[i](s),
                c = a.value
            } catch(u) {
                return void n(u)
            }
            a.done ? e(c) : Promise.resolve(c).then(o, r)
        }
        function M(t) {
            return function() {
                var e = this,
                n = arguments;
                return new Promise((function(o, r) {
                    var i = t.apply(e, n);
                    function s(t) {
                        R(i, o, r, s, a, "next", t)
                    }
                    function a(t) {
                        R(i, o, r, s, a, "throw", t)
                    }
                    s(void 0)
                }))
            }
        }
        function I(t, e) {
            var n = Object.keys(t);
            if (Object.getOwnPropertySymbols) {
                var o = Object.getOwnPropertySymbols(t);
                e && (o = o.filter((function(e) {
                    return Object.getOwnPropertyDescriptor(t, e).enumerable
                }))),
                n.push.apply(n, o)
            }
            return n
        }
        function D(t) {
            for (var e = 1; e < arguments.length; e++) {
                var n = null != arguments[e] ? arguments[e] : {};
                e % 2 ? I(Object(n), !0).forEach((function(e) {
                    N(t, e, n[e])
                })) : Object.getOwnPropertyDescriptors ? Object.defineProperties(t, Object.getOwnPropertyDescriptors(n)) : I(Object(n)).forEach((function(e) {
                    Object.defineProperty(t, e, Object.getOwnPropertyDescriptor(n, e))
                }))
            }
            return t
        }
        function N(t, e, n) {
            return e in t ? Object.defineProperty(t, e, {
                value: n,
                enumerable: !0,
                configurable: !0,
                writable: !0
            }) : t[e] = n,
            t
        }
        var j = Object(u["a"])(S["namespace"]),
        G = j.mapMutations,
        $ = j.mapActions,
        U = Object(u["a"])(l["e"]),
        W = U.mapGetters,
        H = U.mapActions,
        V = Object(u["a"])(l["i"]),
        B = V.mapGetters,
        Y = "auth_method",
        q = {
            BASIC: "basic",
            GOOGLE: "google",
            GITHUB: "github"
        },
        z = c.a.extend(P(k({
            name: "LoginForm",
            components: {
                LoginFormTitle: L,
                JfIcon: C["a"],
                JfText: A["a"],
                ProviderButton: F["a"],
                HelpTooltip: x["default"]
            },
            props: {
                ssoData: {
                    type: Array,
                default:
                    function() {
                        return []
                    }
                },
                loginViewMode: String,
                serverErrorMessage: String,
                canForgotPassword: Boolean,
                loading: Boolean,
                rememberMeEnabled: Boolean,
                isLoginFailed: {
                    type: Boolean,
                default:
                    !1
                },
                handleLoginClick: {
                    type: Function,
                default:
                    function() {
                        return O["a"]
                    }
                },
                handleSsoClick: {
                    type: Function,
                default:
                    function() {
                        return O["a"]
                    }
                }
            },
            data: function() {
                return {
                    model: {
                        username: "",
                        password: "",
                        rememberMe: !1
                    },
                    PROVIDER_ICONS: {
                        GOOGLE: "Google",
                        GITHUB: "Github",
                        OPENID: "OpenID",
                        CLOUDFOUNDRY: "CloudFoundry",
                        OAUTHSSO: "SSO"
                    }
                }
            },
            created: function() {
                this.saasTooltip = d["l"]
            },
            mounted: function() {
                this.init()
            },
            watch: {
                isLoginFailed: function(t) {
                    t && this.shouldDeleteLoginWrongPassword && (this.model.password = "")
                }
            },
            computed: D(D(D({},
            W({
                isSaas: l["f"].getters.GET_IS_CLOUD,
                shouldDeleteLoginWrongPassword: l["f"].getters.GET_SHOULD_DELETE_LOGIN_WRONG_PASSWORD
            })), B({
                isCloudTrial: l["j"].getters.IS_CLOUD_TRIAL
            })), {},
            {
                haveSsoData: function() {
                    return !! Object.keys(this.ssoMethods).length
                },
                isRegularScreenMode: function() {
                    return this.loginViewMode === T["LoginMode"].internal || !this.haveSsoData
                },
                isModeFetched: function() {
                    return !! this.loginViewMode
                },
                rules: function() {
                    return {
                        username: [{
                            required: !0,
                            message: d["n"].USERNAME_REQUIRED,
                            trigger: "blur"
                        }],
                        password: [{
                            required: !0,
                            message: d["n"].PASSWORD_REQUIRED,
                            trigger: "blur"
                        }]
                    }
                },
                getLoginFlow: function() {
                    return y["LoginFlow"].ARTIFACTORY
                },
                hasPrefferedAuthMethod: function() {
                    return this.$route.query[Y]
                },
                hideBasicMode: function() {
                    return this.hasPrefferedAuthMethod && this.hasPrefferedAuthMethod !== q.BASIC
                },
                hideOauthSection: function() {
                    return this.hasPrefferedAuthMethod && this.hasPrefferedAuthMethod === q.BASIC
                },
                ssoMethods: function() {
                    var t = this;
                    return this.hasPrefferedAuthMethod && this.hideBasicMode ? this.ssoData.filter((function(e) {
                        return e.type === t.hasPrefferedAuthMethod
                    })) : this.ssoData
                },
                centerSsoItems: function() {
                    return 1 === this.ssoMethods.length
                },
                ssoSignInText: function() {
                    return this.hideBasicMode ? "Sign in with": "Or sign in with"
                }
            }),
            methods: D(D(D(D(D({},
            $({
                fetchAllLoginData: S["types"].actions.FETCH_ALL_LOGIN_DATA
            })), H({
                fetchFooter: l["f"].actions.FETCH_FOOTER
            })), {},
            {
                getVendorName: function(t) {
                    for (var e = ["GitHub", "Google"], n = 0, o = e; n < o.length; n++) {
                        var r = o[n];
                        if (new RegExp(r, "ig").test(t) && this.isCloudTrial) return r
                    }
                    return t
                },
                goToForgotPassword: function() {
                    this.$router.push({
                        name: "forgotPassword"
                    })
                },
                onLoginClick: function() {
                    var t = this;
                    this.$refs.loginForm.validate((function(e) {
                        e && (t.$set(t.model, "username", t.model.username.trim()), t.handleLoginClick(t.model, t.getLoginFlow))
                    }))
                },
                changeScreenMode: function() {
                    this.setLoginPageAsSsoProvidersList(T["LoginMode"].internal)
                },
                getIcon: function(t) {
                    var e, n, o, r, i = null === t || void 0 === t || null === (e = t.icon) || void 0 === e || null === (n = e.toUpperCase) || void 0 === n || null === (o = n.call(e)) || void 0 === o || null === (r = o.replace) || void 0 === r ? void 0 : r.call(o, "-", "");
                    return "colorful/loginProviders/".concat(this.PROVIDER_ICONS[i])
                }
            },
            G({
                setLoading: S["types"].mutations.SET_LOADING,
                setLoginPageAsSsoProvidersList: S["types"].mutations.SET_LOGIN_VIEW_MODE
            })), Object(u["c"])({
                fetchUserData: l["x"].actions.FETCH_USER_DATA
            })), {},
            {
                init: function() {
                    var t = M(s.a.mark((function t() {
                        var e;
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                e = this.$route.query.token,
                                this.fetchUserData(),
                                this.fetchAllLoginData(e),
                                this.fetchFooter();
                            case 4:
                            case "end":
                                return t.stop()
                            }
                        }), t, this)
                    })));
                    function e() {
                        return t.apply(this, arguments)
                    }
                    return e
                } ()
            }),
            destroyed: function() {
                this.setLoading(!1)
            }
        }))),
        J = z,
        Q = (n("5ada"), n("0035"), Object(v["a"])(J, o, r, !1, null, "094fc034", null));
        e["default"] = Q.exports
    },
    be47: function(t, e, n) {
        "use strict";
        n("add1");
        var o = n("5b44");
        n.o(o, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return o["LoginFlow"]
        }));
        var r = n("d424");
        n.o(r, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return r["LoginFlow"]
        }));
        var i = n("f7e1");
        n.o(i, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return i["LoginFlow"]
        }));
        var s = n("5927");
        n.o(s, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return s["LoginFlow"]
        }));
        var a = n("f53e");
        n.o(a, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return a["LoginFlow"]
        }));
        var c = n("2ebb");
        n.o(c, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return c["LoginFlow"]
        }));
        var u = n("5b71");
        n.o(u, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return u["LoginFlow"]
        }));
        var l = n("53523");
        n.o(l, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return l["LoginFlow"]
        }));
        var d = n("18c8");
        n.o(d, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return d["LoginFlow"]
        }));
        n("e217");
        var f = n("a58c");
        n.o(f, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return f["LoginFlow"]
        }))
    },
    c517: function(t, e, n) {},
    c791: function(t, e, n) {
        t.exports = n.p + "img/login_logo.590e6123.svg"
    },
    c927: function(t, e, n) {
        "use strict";
        n.r(e);
        var o = function() {
            var t = this,
            e = t.$createElement,
            n = t._self._c || e;
            return n("div", {
                staticClass: "login-page-form-container"
            },
            [n("span", {
                staticClass: "login-form-title"
            },
            [t._v("Authenticating")]), n("div", {
                staticClass: "login-page-form-content"
            },
            [n("div", {
                directives: [{
                    name: "loading",
                    rawName: "v-loading",
                    value: !0,
                    expression: "true"
                }],
                staticClass: "margin--t-44 spinner"
            })])])
        },
        r = [],
        i = n("a34a"),
        s = n.n(i),
        a = n("b908"),
        c = n("1ea8"),
        u = n("1e4c"),
        l = n("ae99"),
        d = n("822a");
        function f(t, e, n, o, r, i, s) {
            try {
                var a = t[i](s),
                c = a.value
            } catch(u) {
                return void n(u)
            }
            a.done ? e(c) : Promise.resolve(c).then(o, r)
        }
        function g(t) {
            return function() {
                var e = this,
                n = arguments;
                return new Promise((function(o, r) {
                    var i = t.apply(e, n);
                    function s(t) {
                        f(i, o, r, s, a, "next", t)
                    }
                    function a(t) {
                        f(i, o, r, s, a, "throw", t)
                    }
                    s(void 0)
                }))
            }
        }
        var h = Object(l["a"])(d["b"].ACCESS.LOGIN_FLOW, (function() {
            return {
                methods: {
                    crowdSsoLogin: function() {
                        var t = g(s.a.mark((function t() {
                            return s.a.wrap((function(t) {
                                while (1) switch (t.prev = t.next) {
                                case 0:
                                    return t.prev = 0,
                                    t.next = 3,
                                    c["a"].crowdLoginAccess(this.$store.$apiClient);
                                case 3:
                                    return t.next = 5,
                                    this.clearAndNavigate();
                                case 5:
                                    t.next = 10;
                                    break;
                                case 7:
                                    t.prev = 7,
                                    t.t0 = t["catch"](0),
                                    this.goToLogout();
                                case 10:
                                case "end":
                                    return t.stop()
                                }
                            }), t, this, [[0, 7]])
                        })));
                        function e() {
                            return t.apply(this, arguments)
                        }
                        return e
                    } (),
                    httpSsoLogin: function() {
                        var t = g(s.a.mark((function t() {
                            return s.a.wrap((function(t) {
                                while (1) switch (t.prev = t.next) {
                                case 0:
                                    return t.prev = 0,
                                    t.next = 3,
                                    c["a"].httpSsoLoginAccess(this.$store.$apiClient);
                                case 3:
                                    return t.next = 5,
                                    this.clearAndNavigate();
                                case 5:
                                    t.next = 10;
                                    break;
                                case 7:
                                    t.prev = 7,
                                    t.t0 = t["catch"](0),
                                    this.goToLogout();
                                case 10:
                                case "end":
                                    return t.stop()
                                }
                            }), t, this, [[0, 7]])
                        })));
                        function e() {
                            return t.apply(this, arguments)
                        }
                        return e
                    } ()
                }
            }
        }));
        function p(t, e, n, o, r, i, s) {
            try {
                var a = t[i](s),
                c = a.value
            } catch(u) {
                return void n(u)
            }
            a.done ? e(c) : Promise.resolve(c).then(o, r)
        }
        function w(t) {
            return function() {
                var e = this,
                n = arguments;
                return new Promise((function(o, r) {
                    var i = t.apply(e, n);
                    function s(t) {
                        p(i, o, r, s, a, "next", t)
                    }
                    function a(t) {
                        p(i, o, r, s, a, "throw", t)
                    }
                    s(void 0)
                }))
            }
        }
        var m = h({
            name: "ssoLogin",
            mounted: function() {
                switch (this.$route.params.ssoLoginType) {
                case "http":
                    this.httpSsoLogin();
                    break;
                case "crowd":
                    this.crowdSsoLogin();
                    break;
                default:
                    this.goToLogout()
                }
            },
            methods: {
                clearAndNavigate: function() {
                    var t = w(s.a.mark((function t() {
                        var e;
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                return t.next = 2,
                                this.$store.dispatch(a["x"].actions.CLEAR_INITIAL_DATA);
                            case 2:
                                return e = Object(u["b"])(),
                                t.next = 5,
                                this.$store.dispatch(a["x"].actions.NAVIGATE, e);
                            case 5:
                            case "end":
                                return t.stop()
                            }
                        }), t, this)
                    })));
                    function e() {
                        return t.apply(this, arguments)
                    }
                    return e
                } (),
                httpSsoLogin: function() {
                    var t = w(s.a.mark((function t() {
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                return t.prev = 0,
                                t.next = 3,
                                c["a"].httpSsoLogin(this.$store.$apiClient);
                            case 3:
                                return t.next = 5,
                                this.clearAndNavigate();
                            case 5:
                                t.next = 10;
                                break;
                            case 7:
                                t.prev = 7,
                                t.t0 = t["catch"](0),
                                this.goToLogout();
                            case 10:
                            case "end":
                                return t.stop()
                            }
                        }), t, this, [[0, 7]])
                    })));
                    function e() {
                        return t.apply(this, arguments)
                    }
                    return e
                } (),
                crowdSsoLogin: function() {
                    var t = w(s.a.mark((function t() {
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                return t.prev = 0,
                                t.next = 3,
                                c["a"].crowdLogin(this.$store.$apiClient);
                            case 3:
                                return t.next = 5,
                                this.clearAndNavigate();
                            case 5:
                                t.next = 10;
                                break;
                            case 7:
                                t.prev = 7,
                                t.t0 = t["catch"](0),
                                this.goToLogout();
                            case 10:
                            case "end":
                                return t.stop()
                            }
                        }), t, this, [[0, 7]])
                    })));
                    function e() {
                        return t.apply(this, arguments)
                    }
                    return e
                } (),
                goToLogout: function() {
                    var t = w(s.a.mark((function t() {
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                return t.next = 2,
                                this.$store.dispatch(a["x"].actions.NAVIGATE, {
                                    name: "logout"
                                });
                            case 2:
                            case "end":
                                return t.stop()
                            }
                        }), t, this)
                    })));
                    function e() {
                        return t.apply(this, arguments)
                    }
                    return e
                } ()
            }
        }),
        v = m,
        b = n("2877"),
        L = Object(b["a"])(v, o, r, !1, null, null, null);
        e["default"] = L.exports
    },
    cc19: function(t, e) {},
    cd82: function(t, e, n) {},
    d036: function(t, e, n) {
        "use strict";
        var o, r; (function(t) {
            t["SAML"] = "saml",
            t["OAUTH"] = "oauth",
            t["CROWD"] = "crowd",
            t["HTTP_SSO"] = "http-sso",
            t["LDAP"] = "ldap",
            t["ACCESS"] = "access",
            t["INTERNAL"] = "internal",
            t["SYSTEM"] = "system"
        })(o || (o = {})),
        function(t) {
            t["ENROLL"] = "ENROLL",
            t["VERIFY"] = "VERIFY"
        } (r || (r = {}))
    },
    d424: function(t, e) {},
    d4db: function(t, e, n) {
        "use strict";
        var o;
        n.d(e, "a", (function() {
            return o
        })),
        function(t) {
            t["ACCESS"] = "access",
            t["ARTIFACTORY"] = "artifactory"
        } (o || (o = {}))
    },
    d685: function(t, e, n) {},
    dd7a: function(t, e, n) {
        "use strict";
        n("e30b"),
        n("0566")
    },
    df72: function(t, e) {},
    dfbc: function(t, e) {},
    dfdf: function(t, e) {},
    e217: function(t, e, n) {
        "use strict";
        Symbol()
    },
    e30b: function(t, e) {},
    e336: function(t, e, n) {
        "use strict";
        var o = n("53523");
        n.o(o, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return o["LoginFlow"]
        }))
    },
    e8f2: function(t, e) {},
    ee7c: function(t, e, n) {
        "use strict";
        n.r(e);
        var o = function() {
            var t = this,
            e = t.$createElement,
            n = t._self._c || e;
            return n("div", {
                staticClass: "login center-align"
            },
            [n("mobile-welcome-screen"), n("div", {
                staticClass: "login-modal-image"
            },
            [n("img", {
                staticClass: "login-modal-image-logo",
                attrs: {
                    src: t.logoImg,
                    alt: "logo"
                }
            })]), n("div", {
                staticClass: "login-modal"
            },
            [n("div", {
                staticClass: "login-content"
            },
            [n("div", {
                staticClass: "login-header"
            },
            [t.canCloseLogin ? n("div", {
                staticClass: "close-button-container",
                on: {
                    click: t.close
                }
            },
            [n("el-button", {
                staticClass: "close",
                attrs: {
                    type: "button"
                }
            },
            [n("i", {
                staticClass: "icon-close",
                attrs: {
                    "data-cy": "anonymousLoginCloseIcon"
                }
            })])], 1) : t._e()]), n("div", {
                staticClass: "login-form-content"
            },
            [n("router-view", t._g(t._b({
                staticClass: "margin-negative--t-48"
            },
            "router-view", t.childComponentProps, !1), t.childComponentEvents))], 1)])])], 1)
        },
        r = [],
        i = n("a34a"),
        s = n.n(i),
        a = n("8bbf"),
        c = n.n(a),
        u = n("2f62"),
        l = n("de2e"),
        d = n("b908"),
        f = n("7683"),
        g = n("4f3a"),
        h = n("1e4c"),
        p = n("4360"),
        w = n("c791"),
        m = n.n(w),
        v = n("a39c"),
        b = n("1ea8"),
        L = n("734b"),
        F = n("0513");
        function S(t, e) {
            var n = Object.keys(t);
            if (Object.getOwnPropertySymbols) {
                var o = Object.getOwnPropertySymbols(t);
                e && (o = o.filter((function(e) {
                    return Object.getOwnPropertyDescriptor(t, e).enumerable
                }))),
                n.push.apply(n, o)
            }
            return n
        }
        function y(t) {
            for (var e = 1; e < arguments.length; e++) {
                var n = null != arguments[e] ? arguments[e] : {};
                e % 2 ? S(Object(n), !0).forEach((function(e) {
                    O(t, e, n[e])
                })) : Object.getOwnPropertyDescriptors ? Object.defineProperties(t, Object.getOwnPropertyDescriptors(n)) : S(Object(n)).forEach((function(e) {
                    Object.defineProperty(t, e, Object.getOwnPropertyDescriptor(n, e))
                }))
            }
            return t
        }
        function O(t, e, n) {
            return e in t ? Object.defineProperty(t, e, {
                value: n,
                enumerable: !0,
                configurable: !0,
                writable: !0
            }) : t[e] = n,
            t
        }
        function C(t, e, n, o, r, i, s) {
            try {
                var a = t[i](s),
                c = a.value
            } catch(u) {
                return void n(u)
            }
            a.done ? e(c) : Promise.resolve(c).then(o, r)
        }
        function A(t) {
            return function() {
                var e = this,
                n = arguments;
                return new Promise((function(o, r) {
                    var i = t.apply(e, n);
                    function s(t) {
                        C(i, o, r, s, a, "next", t)
                    }
                    function a(t) {
                        C(i, o, r, s, a, "throw", t)
                    }
                    s(void 0)
                }))
            }
        }
        var x = Object(u["a"])(l["namespace"]),
        E = x.mapActions,
        _ = x.mapGetters,
        k = x.mapMutations,
        P = Object(u["a"])(d["e"]),
        T = P.mapGetters,
        R = Object(u["a"])(g["b"]),
        M = R.mapActions,
        I = Object(u["a"])(f["namespace"]),
        D = I.mapActions,
        N = c.a.extend({
            name: "Login",
            components: {
                MobileWelcomeScreen: L["a"]
            },
            data: function() {
                return {
                    unwatchUser: null,
                    logoImg: m.a,
                    defaultHomeRoute: "/",
                    serverErrorMessage: null,
                    isLoginFailed: !1
                }
            },
            created: function() {
                var t = A(s.a.mark((function t() {
                    var e;
                    return s.a.wrap((function(t) {
                        while (1) switch (t.prev = t.next) {
                        case 0:
                            return t.next = 2,
                            this.resetStoreOnLogout();
                        case 2:
                            e = this.$route.query.oauthMessage,
                            e && (this.serverErrorMessage = "login with oauth error - ".concat(e)),
                            this.setLoading(!1);
                        case 5:
                        case "end":
                            return t.stop()
                        }
                    }), t, this)
                })));
                function e() {
                    return t.apply(this, arguments)
                }
                return e
            } (),
            mounted: function() {
                window.hideSplashPulse()
            },
            computed: y(y(y({
                childComponentRouteToApiMapping: function() {
                    var t;
                    return t = {},
                    O(t, v["k"].LOGIN, {
                        props: {
                            serverErrorMessage: this.serverErrorMessage,
                            ssoData: this.ssoData,
                            loginViewMode: this.loginViewMode,
                            canForgotPassword: this.canForgotPassword,
                            rememberMeEnabled: this.rememberMeEnabled,
                            loading: this.loading,
                            isLoginFailed: this.isLoginFailed,
                            handleLoginClick: this.onLoginFlow,
                            handleSsoClick: this.onSsoClick
                        }
                    }),
                    O(t, v["k"].INVITATION, {
                        props: {
                            ssoData: this.ssoData,
                            handleSsoClick: this.onSsoClick,
                            onLogin: this.login,
                            userData: this.userData,
                            isSaas: this.isSaas
                        }
                    }),
                    O(t, v["k"].OTP_LOGIN, {
                        props: {
                            serverErrorMessage: this.serverErrorMessage,
                            loading: this.loading,
                            handleOtpLoginClick: this.onOtpLoginFlow
                        }
                    }),
                    O(t, v["k"].MFA_ENROLL, {
                        props: {
                            handleEnrolNextClick: this.onEnrolNextClick,
                            handleEnrolSessionTimeout: this.onEnrolSessionTimeout
                        }
                    }),
                    O(t, v["k"].FORGOT_PASSWORD, {
                        props: {
                            loading: this.loading,
                            isSaas: this.isSaas,
                            handleForgetPasswordSubmit: this.onForgetPasswordSubmit
                        }
                    }),
                    O(t, v["k"].RESET_PASSWORD, {
                        props: {
                            title: "Reset Password",
                            loading: this.loading,
                            handleChangeResetPasswordSubmit: this.onResetPasswordFlow,
                            setUserPassword: this.setUserPassword
                        }
                    }),
                    O(t, v["k"].CHANGE_PASSWORD, {
                        props: {
                            title: "Your Password Has Expired",
                            subtitle: "Change Password",
                            showOldPassword: !0,
                            loading: this.loading,
                            handleChangeResetPasswordSubmit: this.onChangePasswordFlow
                        }
                    }),
                    O(t, v["k"].CLI, {
                        props: {
                            title: "CLI Login",
                            subtitle: "Copy the relevant command for CLI login",
                            loading: this.loading,
                            userData: this.userData
                        }
                    }),
                    O(t, v["k"].SSO_LOGIN, {
                        props: {}
                    }),
                    O(t, v["k"].REGISTRATION, {
                        props: {
                            title: "Your Environment is Ready",
                            subtitle: "We have sent you an email with your environment details.",
                            loading: this.loading,
                            userData: this.userData,
                            onLogin: this.login,
                            setUserPassword: this.setUserPassword
                        }
                    }),
                    t
                },
                childComponentProps: function() {
                    var t = this.childComponentRouteToApiMapping[this.$route.name].props,
                    e = void 0 === t ? {}: t;
                    return e
                },
                childComponentEvents: function() {
                    var t = this.childComponentRouteToApiMapping[this.$route.name].events,
                    e = void 0 === t ? {}: t;
                    return e
                },
                canCloseLogin: function() {
                    return this.isAnonymousAllowed
                }
            },
            _({
                ssoData: l["types"].getters.GET_SSO_DATA,
                loginViewMode: l["types"].getters.GET_LOGIN_VIEW_MODE,
                canForgotPassword: l["types"].getters.GET_FORGOT_PASSWORD,
                rememberMeEnabled: l["types"].getters.GET_CAN_REMEMBER_ME,
                loading: l["types"].getters.GET_LOADING,
                mfaAuthenticator: l["types"].getters.GET_MFA_AUTHENTICATOR
            })), T({
                isSaas: d["f"].getters.GET_IS_CLOUD
            })), Object(u["d"])({
                isAnonymousAllowed: p["types"].getters.IS_ANONYMOUS_ALLOWED,
                userData: p["types"].getters.GET_USERDATA
            })),
            watch: {
                $route: function() {
                    this.serverErrorMessage = null
                }
            },
            methods: y(y(y(y({},
            D({
                setUserPassword: f["types"].actions.SET_USER_PASSWORD
            })), {},
            {
                onLoginFlow: function() {
                    var t = A(s.a.mark((function t(e, n) {
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                this.resetServerValidation(),
                                t.t0 = n,
                                t.next = t.t0 === F["LoginFlow"].ACCESS ? 4 : t.t0 === F["LoginFlow"].ARTIFACTORY ? 6 : 8;
                                break;
                            case 4:
                                return this.onAccessLogIn(e),
                                t.abrupt("break", 9);
                            case 6:
                                return this.onLoginClick(e),
                                t.abrupt("break", 9);
                            case 8:
                                return t.abrupt("break", 9);
                            case 9:
                            case "end":
                                return t.stop()
                            }
                        }), t, this)
                    })));
                    function e(e, n) {
                        return t.apply(this, arguments)
                    }
                    return e
                } (),
                onResetPasswordFlow: function() {
                    var t = A(s.a.mark((function t(e, n) {
                        var o;
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                o = e.newPassword1,
                                t.t0 = n,
                                t.next = t.t0 === F["LoginFlow"].ACCESS ? 4 : t.t0 === F["LoginFlow"].ARTIFACTORY ? 6 : 8;
                                break;
                            case 4:
                                return this.onResetAccessPasswordSubmit({
                                    newPassword1:
                                    o
                                }),
                                t.abrupt("break", 9);
                            case 6:
                                return this.onResetPasswordSubmit({
                                    newPassword1:
                                    o
                                }),
                                t.abrupt("break", 9);
                            case 8:
                                return t.abrupt("break", 9);
                            case 9:
                            case "end":
                                return t.stop()
                            }
                        }), t, this)
                    })));
                    function e(e, n) {
                        return t.apply(this, arguments)
                    }
                    return e
                } (),
                onChangePasswordFlow: function() {
                    var t = A(s.a.mark((function t(e, n) {
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                t.t0 = n,
                                t.next = t.t0 === F["LoginFlow"].ACCESS ? 3 : t.t0 === F["LoginFlow"].ARTIFACTORY ? 5 : 7;
                                break;
                            case 3:
                                return this.onChangeAccessPasswordSubmit(e),
                                t.abrupt("break", 8);
                            case 5:
                                return this.onChangePasswordSubmit(e),
                                t.abrupt("break", 8);
                            case 7:
                                return t.abrupt("break", 8);
                            case 8:
                            case "end":
                                return t.stop()
                            }
                        }), t, this)
                    })));
                    function e(e, n) {
                        return t.apply(this, arguments)
                    }
                    return e
                } (),
                onOtpLoginFlow: function() {
                    var t = A(s.a.mark((function t(e, n) {
                        var o;
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                o = e.otp,
                                t.t0 = n,
                                t.next = t.t0 === F["LoginFlow"].ACCESS ? 4 : t.t0 === F["LoginFlow"].ARTIFACTORY ? 6 : 8;
                                break;
                            case 4:
                                return this.onOtpAccessLoginClick(o),
                                t.abrupt("break", 9);
                            case 6:
                                return this.onOtpLoginClick(o),
                                t.abrupt("break", 9);
                            case 8:
                                return t.abrupt("break", 9);
                            case 9:
                            case "end":
                                return t.stop()
                            }
                        }), t, this)
                    })));
                    function e(e, n) {
                        return t.apply(this, arguments)
                    }
                    return e
                } (),
                onOtpLoginClick: function() {
                    var t = A(s.a.mark((function t(e) {
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                return t.next = 2,
                                this.verifyOtp({
                                    otp: e
                                });
                            case 2:
                                this.serverErrorMessage = t.sent;
                            case 3:
                            case "end":
                                return t.stop()
                            }
                        }), t, this)
                    })));
                    function e(e) {
                        return t.apply(this, arguments)
                    }
                    return e
                } (),
                onOtpAccessLoginClick: function() {
                    var t = A(s.a.mark((function t(e) {
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                return t.next = 2,
                                this.verifyAccessOtp({
                                    otp: e
                                });
                            case 2:
                                this.serverErrorMessage = t.sent;
                            case 3:
                            case "end":
                                return t.stop()
                            }
                        }), t, this)
                    })));
                    function e(e) {
                        return t.apply(this, arguments)
                    }
                    return e
                } (),
                onAccessLogIn: function() {
                    var t = A(s.a.mark((function t(e) {
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                return t.next = 2,
                                this.accessLogin({
                                    username: e.username,
                                    password: e.password,
                                    rememberMe: e.rememberMe
                                });
                            case 2:
                                if (this.serverErrorMessage = t.sent, !this.serverErrorMessage) {
                                    t.next = 7;
                                    break
                                }
                                this.isLoginFailed = !0,
                                t.next = 9;
                                break;
                            case 7:
                                return t.next = 9,
                                this.onLoggedIn();
                            case 9:
                            case "end":
                                return t.stop()
                            }
                        }), t, this)
                    })));
                    function e(e) {
                        return t.apply(this, arguments)
                    }
                    return e
                } (),
                onLoginClick: function() {
                    var t = A(s.a.mark((function t(e) {
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                return t.next = 2,
                                this.login({
                                    username: e.username,
                                    password: e.password,
                                    rememberMe: e.rememberMe
                                });
                            case 2:
                                if (this.serverErrorMessage = t.sent, !this.serverErrorMessage) {
                                    t.next = 7;
                                    break
                                }
                                this.isLoginFailed = !0,
                                t.next = 10;
                                break;
                            case 7:
                                return t.next = 9,
                                this.onLoggedIn();
                            case 9:
                                this.setUserPassword(e.password);
                            case 10:
                            case "end":
                                return t.stop()
                            }
                        }), t, this)
                    })));
                    function e(e) {
                        return t.apply(this, arguments)
                    }
                    return e
                } (),
                onLoggedIn: function() {
                    var t = A(s.a.mark((function t() {
                        var e, n, o;
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                if (this.$route.name !== v["k"].INVITATION || null === (e = this.$route.query) || void 0 === e || !e.redirectTo) {
                                    t.next = 10;
                                    break
                                }
                                return t.prev = 1,
                                t.next = 4,
                                b["a"].redirect(this.$store.$apiClient, this.$route.query.redirectTo);
                            case 4:
                                o = t.sent,
                                window.location.href = null === o || void 0 === o || null === (n = o.data) || void 0 === n ? void 0 : n.url,
                                t.next = 10;
                                break;
                            case 8:
                                t.prev = 8,
                                t.t0 = t["catch"](1);
                            case 10:
                            case "end":
                                return t.stop()
                            }
                        }), t, this, [[1, 8]])
                    })));
                    function e() {
                        return t.apply(this, arguments)
                    }
                    return e
                } (),
                onEnrolNextClick: function() {
                    this.$router.push({
                        name: v["k"].OTP_LOGIN
                    })
                },
                onEnrolSessionTimeout: function() {
                    var t = A(s.a.mark((function t(e) {
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                return t.next = 2,
                                this.$router.push({
                                    name: v["k"].LOGIN
                                });
                            case 2:
                                this.serverErrorMessage = e;
                            case 3:
                            case "end":
                                return t.stop()
                            }
                        }), t, this)
                    })));
                    function e(e) {
                        return t.apply(this, arguments)
                    }
                    return e
                } (),
                onSsoClick: function() {
                    var t = A(s.a.mark((function t(e) {
                        var n, o, r, i, a = this;
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                return n = {
                                    type: "error",
                                    message: "Something went wrong"
                                },
                                o = this.$route.query.token,
                                t.prev = 2,
                                t.next = 5,
                                this.updateOauthProviders(o);
                            case 5:
                                r = this.ssoData.find((function(t) {
                                    return t.name === e.name
                                })),
                                i = r.url,
                                window.setTimeout((function() {
                                    i ? window.location.href = i: a.$message(n)
                                })),
                                t.next = 14;
                                break;
                            case 10:
                                t.prev = 10,
                                t.t0 = t["catch"](2),
                                console.error(t.t0),
                                this.$message(n);
                            case 14:
                            case "end":
                                return t.stop()
                            }
                        }), t, this, [[2, 10]])
                    })));
                    function e(e) {
                        return t.apply(this, arguments)
                    }
                    return e
                } (),
                resetServerValidation: function() {
                    this.serverErrorMessage = null,
                    this.isLoginFailed = !1
                },
                close: function() {
                    var t = A(s.a.mark((function t() {
                        var e;
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                if (t.prev = 0, e = Object(h["b"])(), !e) {
                                    t.next = 7;
                                    break
                                }
                                return t.next = 5,
                                this.$router.push({
                                    path: e
                                });
                            case 5:
                                t.next = 9;
                                break;
                            case 7:
                                return t.next = 9,
                                this.$router.push("/home");
                            case 9:
                                t.next = 15;
                                break;
                            case 11:
                                return t.prev = 11,
                                t.t0 = t["catch"](0),
                                t.next = 15,
                                this.$router.push("/home");
                            case 15:
                            case "end":
                                return t.stop()
                            }
                        }), t, this, [[0, 11]])
                    })));
                    function e() {
                        return t.apply(this, arguments)
                    }
                    return e
                } (),
                onForgetPasswordSubmit: function() {
                    var t = A(s.a.mark((function t(e) {
                        var n, o, r;
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                return n = e.username,
                                t.next = 3,
                                this.forgotPassword({
                                    username: n
                                });
                            case 3:
                                if (o = t.sent, r = this.onNotificationHandler(o, v["h"].EMAIL_SENT_MESSAGE), r) {
                                    t.next = 7;
                                    break
                                }
                                return t.abrupt("return");
                            case 7:
                                this.$router.push({
                                    name:
                                    v["k"].LOGIN
                                });
                            case 8:
                            case "end":
                                return t.stop()
                            }
                        }), t, this)
                    })));
                    function e(e) {
                        return t.apply(this, arguments)
                    }
                    return e
                } (),
                onResetPasswordSubmit: function() {
                    var t = A(s.a.mark((function t(e) {
                        var n, o;
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                return n = e.newPassword1,
                                t.next = 3,
                                this.resetPassword({
                                    newPassword1: n
                                });
                            case 3:
                                o = t.sent,
                                this.onNotificationHandler(o, v["h"].PASSWORD_CHANGED_MESSAGE);
                            case 5:
                            case "end":
                                return t.stop()
                            }
                        }), t, this)
                    })));
                    function e(e) {
                        return t.apply(this, arguments)
                    }
                    return e
                } (),
                onResetAccessPasswordSubmit: function() {
                    var t = A(s.a.mark((function t(e) {
                        var n, o;
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                return n = e.newPassword1,
                                t.next = 3,
                                this.resetAccessPassword({
                                    newPassword1: n
                                });
                            case 3:
                                o = t.sent,
                                this.onNotificationHandler(o, v["h"].PASSWORD_CHANGED_MESSAGE);
                            case 5:
                            case "end":
                                return t.stop()
                            }
                        }), t, this)
                    })));
                    function e(e) {
                        return t.apply(this, arguments)
                    }
                    return e
                } (),
                onChangePasswordSubmit: function() {
                    var t = A(s.a.mark((function t(e) {
                        var n;
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                return t.next = 2,
                                this.changePassword(e);
                            case 2:
                                n = t.sent,
                                this.onNotificationHandler(n, v["h"].PASSWORD_CHANGED_MESSAGE);
                            case 4:
                            case "end":
                                return t.stop()
                            }
                        }), t, this)
                    })));
                    function e(e) {
                        return t.apply(this, arguments)
                    }
                    return e
                } (),
                onChangeAccessPasswordSubmit: function() {
                    var t = A(s.a.mark((function t(e) {
                        var n;
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                return t.next = 2,
                                this.changeAccessPassword(e);
                            case 2:
                                n = t.sent,
                                this.onNotificationHandler(n, v["h"].PASSWORD_CHANGED_MESSAGE);
                            case 4:
                            case "end":
                                return t.stop()
                            }
                        }), t, this)
                    })));
                    function e(e) {
                        return t.apply(this, arguments)
                    }
                    return e
                } (),
                resetStoreOnLogout: function() {
                    var t = A(s.a.mark((function t() {
                        var e, n;
                        return s.a.wrap((function(t) {
                            while (1) switch (t.prev = t.next) {
                            case 0:
                                if (n = null === (e = this.$route.params) || void 0 === e ? void 0 : e.logout, !n) {
                                    t.next = 4;
                                    break
                                }
                                return t.next = 4,
                                this.resetStore();
                            case 4:
                            case "end":
                                return t.stop()
                            }
                        }), t, this)
                    })));
                    function e() {
                        return t.apply(this, arguments)
                    }
                    return e
                } (),
                onNotificationHandler: function(t, e) {
                    return t ? (this.$message({
                        type: "error",
                        message: t
                    }), !1) : (this.$message({
                        type: "success",
                        message: e
                    }), !0)
                }
            },
            k({
                setLoading: l["types"].mutations.SET_LOADING
            })), E({
                login: l["types"].actions.LOGIN,
                accessLogin: l["types"].actions.ACCESS_LOGIN,
                verifyOtp: l["types"].actions.OTP_VERIFY,
                verifyAccessOtp: l["types"].actions.OTP_ACCESS_VERIFY,
                forgotPassword: l["types"].actions.FORGOT_PASSWORD,
                resetPassword: l["types"].actions.RESET_PASSWORD,
                resetAccessPassword: l["types"].actions.RESET_ACCESS_PASSWORD,
                changePassword: l["types"].actions.CHANGE_PASSWORD,
                changeAccessPassword: l["types"].actions.CHANGE_ACCESS_PASSWORD,
                updateOauthProviders: l["types"].actions.FETCH_OAUTH_PROVIDERS
            })), M({
                resetStore: g["c"].actions.RESET_STORE
            }))
        }),
        j = N,
        G = (n("9812"), n("2877")),
        $ = Object(G["a"])(j, o, r, !1, null, "683c96e6", null);
        e["default"] = $.exports
    },
    f0ef: function(t, e, n) {
        "use strict";
        var o = n("70f1");
        n.o(o, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return o["LoginFlow"]
        }));
        var r = n("dfbc");
        n.o(r, "LoginFlow") && n.d(e, "LoginFlow", (function() {
            return r["LoginFlow"]
        }))
    },
    f53e: function(t, e) {},
    f7e1: function(t, e) {}
}]);
//# sourceMappingURL=login.7fa4cc98.js.map
