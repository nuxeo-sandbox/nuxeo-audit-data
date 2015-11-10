# About nuxeo-audit-data

A Polymer data element backed by the Nuxeo Audit log.

# Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

# Quickstart

A sample application is included that lists the top 10 downloaded files in a Nuxeo application.

Enable CORS in your Nuxeo application.  Example CORS for polyserve:

    <extension target="org.nuxeo.ecm.platform.web.common.requestcontroller.service.RequestControllerService" point="corsConfig">
        <corsConfig name="forPolyserve" allowOrigin="http://localhost:3000">
            <pattern>/nuxeo/.*</pattern>
        </corsConfig>
    </extension>

We recommend that you use [Polyserve](https://github.com/PolymerLabs/polyserve), which you can install via:

    npm install -g polyserve

And you can run it via:

    polyserve -p 3000

Once running, you can check out the example at [http://localhost:3000/components/nuxeo-audit-data/demo](http://localhost:3000/components/nuxeo-audit-data/demo).

# Licensing

[GNU Lesser General Public License (LGPL) v2.1](http://www.gnu.org/licenses/lgpl-2.1.html)

# About Nuxeo

Nuxeo dramatically improves how content-based applications are built, managed and deployed, making customers more agile, innovative and successful. Nuxeo provides a next generation, enterprise ready platform for building traditional and cutting-edge content oriented applications. Combining a powerful application development environment with
SaaS-based tools and a modular architecture, the Nuxeo Platform and Products provide clear business value to some of the most recognizable brands including Verizon, Electronic Arts, Netflix, Sharp, FICO, the U.S. Navy, and Boeing. Nuxeo is headquartered in New York and Paris.
More information is available at [www.nuxeo.com](http://www.nuxeo.com).
